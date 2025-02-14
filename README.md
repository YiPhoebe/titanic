# Titanic Surivor Pediction

이 프로젝트는 https://www.kaggle.com/competitions/titanic 의 타이타닉 데이터셋을 사용하여 생존자를 예측해보는 프로젝트.

## 🗂️ 프로젝트 구조

```
|--titanic
    |--gender_submission.csv	# 승객 성별
    |--test.csv	  	  	# 모델 검증용
    |--titanic.ipynb	  	# 데이터셋 분석 ipynb
    |--train.csv	  	# 모델 훈련용




```

## 1. 주요기능

### titani.ipynb

- 타이타닉 데이셋을 불러와 데이터의 통계적 정보를 시각화하여 그래프로 보여줍니다.
- 각 칼럼 별 결측치를 확인하고, 평균을 만들어 처리
- 성별, 객실 등급 간 생존율 차이가 통계적으로 유의한지 확인
- 생존율 그래프, 통계검정 결과, 분류 모델 정확도, 혼동행렬 등

### gender_submission.csv

- gender_submission.csv' 파일은 **남자를 모두 사망, 여자를 모두 생존으로 분류**하여 나온 결과.

### test.csv

- Survived 행  존재 하지  않음.

### train.csv

- 실제 모델 훈련용 데이터

## 🚀 실행 방법

1. 필요한 라이브러리 설치

```
bash
pip install -r requirements.txt
```
