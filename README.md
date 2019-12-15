pattern recognition: Bag of visual words(BOVW)
================================================
<hr/>

## contents

## data load(from kaggle)
``` ! kaggle competitions download -c 2019-ml-finalproject ```

```! unzip 2019-ml-finalproject.zip ```

## sift function(from disccusion by xown3197)
```def dense_sitf_each(gray):
  sift=cv2.xfeatures2d_SIFT.create()

  keypoints=[]
  w, h = np.array(gray).shape
  for i in range(4, h, 8):
    for j in range(4, w, 8):
      keypoints.append(cv2.KeyPoint(i, j, 8))


  kp,des=sift.compute(gray, keypoints)
  
  return kp, des 
  ```
  ## descriptor
  ``` descriptors= np.vstack(des for des in tqdm(train_des)) ```
  
  ## clustering(code book)(from disccusion by xown3197)
  ``` from sklearn.cluster import MiniBatchKMeans
codebooksize=200

seeding = kmc2.kmc2(descriptors.reshape(-1,128), codebooksize)
Kmeas = MiniBatchKMeans(codebooksize, init=seeding).fit(descriptors.reshape(-1,128))
codebook = Kmeas.cluster_centers_ 
```


## histogram
```from scipy.cluster.vq import vq

hist=[]

for i in tqdm(range(len(train_des))):
  data=train_des[i]
  words, _=vq(data, codebook)
  word_hist,_=np.histogram(words,bins=range(codebooksize+1))
  
  hist.append(word_hist)
  ```
  
## SVM
  ```
from sklearn.model_selection import train_test_split
from sklearn.svm import SVC

x_train, x_test, y_train, y_test = train_test_split(hist, train_labels)
svm = SVC(kernel='rbf',C=50,gamma=1e-5 ,class_weight='balanced').fit(x_train,y_train)
yfit = svm.predict(hist_test)
```

--------------
### Report
#### code book size=200,  SVM parameter: C=50, gamma=1e-5 -> accuaracy:41.1%
#### code book size=600,  SVM parameter: C=50, gamma=1e-5 -> accuaracy:41.5%

-----------------------------
## Thesis(reference)
### Beyond Bags of Features: Spatial Pyramid Matching for Recognizing Natural Scene Categories

