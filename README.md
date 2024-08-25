# CUAI_BASIC

## 개요
> **CUAI_Basic 스터디 1조** <br/> 
> **프로젝트 기간: 2023.03.14 ~ 2023.05.22** <br/>
<br>

## 프로젝트 소개
- 캐글의 Spaceship Titanic 데이터를 바탕으로 어떤 승객들이 다른 차원으로 이동되었는지 예측해보는 프로젝트틀 진행했습니다.
- `Data Preprocessing / Feature Engineering`
  - 누락된 값을 채우고 'Cabin'열을 세 개의 개별 열로 분할하고 그룹 및 그룹 크기와 같은 추가 기능을 생성하였습니다.
  - 'Cabin' 정보를 처리하고 그룹 특성을 사용하여 누락된 데이터를 처리하였습니다.
  - [Cabin_Destination_데이터전처리.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/Cabin_Destination_%EB%8D%B0%EC%9D%B4%ED%84%B0%EC%A0%84%EC%B2%98%EB%A6%AC.ipynb)
  - [train_test cabin_destination 결측치 처리.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/train_test%20cabin_destination%20%EA%B2%B0%EC%B8%A1%EC%B9%98%20%EC%B2%98%EB%A6%AC.ipynb)
  - [결측치 처리 합병.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/%EA%B2%B0%EC%B8%A1%EC%B9%98%20%EC%B2%98%EB%A6%AC%20%ED%95%A9%EB%B3%91.ipynb)
    
- `Model Training and Tuning / Prediction and Submission`
  - LightGBM, SVC(Support Vector Classifier), XGBoost 및 RandomForest를 포함한 여러 기계 학습 모델을 훈련하고 조정했습니다.
  - pycaret을 사용하여 다양한 하이퍼파라미터를 탐색했습니다. 모델의 정확성을 평가하고 최종 예측을 위해 가장 성능이 좋은 모델을 선택했습니다.
  - 테스트 데이터에 가장 적합한 모델을 적용하고 결과를 형식화하여 제출용으로 저장했습니다.
  - [LightGBM 모델.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/LightGBM%20%EB%AA%A8%EB%8D%B8.ipynb)
  - [SVC_0.80313.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/SVC_0.80313.ipynb)
  - [Spaceship_Titanic_XGBoost_최종.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/Spaceship_Titanic_XGBoost_%EC%B5%9C%EC%A2%85.ipynb)
  - [space_titanic_랜덤포레스트.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/space_titanic_%EB%9E%9C%EB%8D%A4%ED%8F%AC%EB%A0%88%EC%8A%A4%ED%8A%B8.ipynb)
  - [Spaceship_Titanic_Pycaret.ipynb](https://github.com/jsh1021902/CUAI_BASIC/blob/main/%EA%B3%B5%EB%AA%A8%EC%A0%84/%EC%B5%9C%EC%A2%85%20%EC%A0%84%EC%B2%98%EB%A6%AC/Spaceship_Titanic_Pycaret.ipynb)



### 데이터셋 출처
- 데이터 출처는 아래 데이터를 사용했습니다
  ```text
  Spaceship Titanic-Predict which passengers are transported to an alternate dimension
  (https://www.kaggle.com/competitions/spaceship-titanic)
  ```
<br>

----

## 사용 기술

### Environment
![Jupyter](https://img.shields.io/badge/Jupyter-F37626.svg?&style=for-the-badge&logo=Jupyter&logoColor=white)
![Github](https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=GitHub&logoColor=white)

### Development
![Python](https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white)
![keras](https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=Keras&logoColor=white)
![Tensorflow](https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white)
![Pandas](https://img.shields.io/badge/Pandas-2C2D72?style=for-the-badge&logo=pandas&logoColor=white)
![Numpy](https://img.shields.io/badge/Numpy-777BB4?style=for-the-badge&logo=numpy&logoColor=white)
![scikit](https://img.shields.io/badge/scikit_learn-F7931E?style=for-the-badge&logo=scikit-learn&logoColor=white)
<br>
----

회고 및 결론
---
### 회고
<details>
  <summary><b>구현 회고</b></summary>
  <div markdown="1">
    <li> 배운 점 </li>
      <ul>
        <li>모델링 과정에서 전처리가 수행하는 중요한 역할에 대해 더 깊이 이해하게 되었습니다.</li>
        <li>각 모델을 수동으로 구축하고 테스트할 필요 없이 PyCaret과 같은 AutoML 도구를 활용하여 효과적으로 모델을 선택하는 방법을 배웠습니다.</li>
      </ul>
    <li> 느낀 점 </li>
      <ul>
        <li>복잡한 개념이라도 노력을 기울이면 이해할 수 있다는 것을 깨달았습니다.</li>
        <li>학습률과 같은 하이퍼 파라미터의 조정에 따라 모델 성능이 크게 달라질 수 있음을 관찰했습니다.</li>
      </ul>
  </div>
</details>

### 결론
- 전처리 및 모델 선택에 대한 경험은 모델 성능에 영향을 미치는 요소를 이해하는 데 매우 중요했습니다.
<br>

---
## 디렉토리 구조
```bash
CUAI_BASIC/
├── README.md
└── 공모전/
    ├── 1차 전처리/
    ├── 2차 전처리/
    ├── 최종 전처리/
    │   ├── Cabin_Destination_데이터전처리.ipynb
    │   ├── train_test cabin_destination 결측치 처리.ipynb
    │   ├── 결측치 처리 합병.ipynb
    │   ├── LightGBM 모델.ipynb
    │   ├── SVC_0.80313.ipynb
    │   ├── Spaceship_Titanic_XGBoost_최종.ipynb
    │   ├── SVC_0.80313.ipynb
    │   ├── space_titanic_랜덤포레스트.ipynb
    │   └── Spaceship_Titanic_Pycaret.ipynb
    └── submission.csv
```
