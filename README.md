# Dacon 컴퓨터 비전 학습 경진대회

<br>

[Dacon 컴퓨터 비전 학습 경진대회 Home](https://dacon.io/competitions/official/235626/overview/)

 MNIST 변형 데이터 세트로 알파벳에 의해서 가려진 숫자를 예측하기


<br>

## To do

- Data preprocessing
    -
    digit image : 이미지에서 숫자만 부분만 추출하기  
    alpabet image : 이미지에서 알파벳 부분만 추출하기  
    deskew : 이미지가 올바르게 정렬해주기  
    Autoencoder : 가려진 이미지를 숫자형태로 생성하기

- Data augmentation
    -
    ImageDataGenerator : 데이터 늘려주기  
    Autoencoder : 숫자형태로 생성된 데이터 늘려서 사용하기

- Callback
    -
    EarlyStopping  
    ReduceLROnPlateau  
    ModelCheckpoint

- Model
    -
    DenseNet 121  
    ReXNet

<br>

## 대회 결과

- Public
    -
    전체 840팀 중 62등  
    점수 : 0.92647

- Private
    -
    전체 840팀 중 41등  
    점수 : 0.90762	