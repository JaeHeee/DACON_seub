# Train platform

## 사용법

- Preprocessing
    -
    Preprocessing_MNIST 파일로 전처리를 진행합니다.  
    data 폴더에 전처리된 pikle 파일이 생성됩니다.

- Choose your model
    -
    Choose your model 파일에서 모델 부분에 원하는 모델을 함수형태로 만들어서 넣습니다.  
    이 파일로 train을 하면 new_data 폴더에 스태킹할 데이터가 만들어집니다.

- Ensemble_And_Submission
    -
    Ensemble_And_Submission을 실행해서 원하는 new_data에 pikle파일을 불러와 마지막 train을 하고 submission을 생성합니다.