https://dacon.io/competitions/official/235626/codeshare/1555?page=1&dtype=recent&ptype=pub

컴퓨터비전학습경진대회 연습   
```   
DACON_MNIST_01(3등 모델 사용)      
ModelCheckpoint, ReduceLROnPlateau, EarlyStopping   
train, valid   
정확도 : 90%   
```

```     
DACON_MNIST_02(3등 모델 사용)      
ModelCheckpoint, ReduceLROnPlateau, EarlyStopping   
train, valid
ImageDataGenerator, flow, fit_generator
정확도 : 92%   
```   

```     
DACON_MNIST_03(3등 모델 사용)      
ModelCheckpoint, ReduceLROnPlateau, EarlyStopping   
train, valid
ImageDataGenerator, flow, fit_generator
StratifiedKFold   
다른점 : (train,validation,test가 모두 for문 안에 들어감, 여러 번 수행한 결과를 종합함)
categorical_crossentropy : 다중 분류 손실 함수, one-hot encoding 필요함   
sparse_categorical_crossentropy : 다중 분류 손실함수, one-hot encoding 따로 안해도 됨   
정확도 : 92%   
```   
