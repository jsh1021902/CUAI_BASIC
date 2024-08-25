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
- chatbot 데이터 출처는 아래 데이터를 사용했습니다
  ```text
  Youngsook Song.(2018). Chatbot_data_for_Korean v1.0)[Online].
  Available : https://github.com/songys/Chatbot_data (downloaded 2022. June. 29.)
  ```
<br>

## 사용 용도
- [korean-chatbot-Transformer.ipynb](korean-chatbot-Transformer.ipynb)
  - Transformer에 대한 자세한 구조를 코드를 통해 확인해보고 싶다면 이 코드를 통해 학습할 수 있습니다
  - 또한, 이 파일에는 custom model을 저장하는 코드가 추가되어 있습니다
  - learning rate, model 구조를 customize 했을 때 어떻게 모델을 저장하고 불러오는지 참고하기 좋을 것 같습니다
- [korean-chatbot-GPT.ipynb](korean-chatbot-GPT.ipynb)
  - 위 transformer notebook을 보고 GPT를 이해하고 싶다면 이 파일을 통해 쉽게 이해할 수 있을 것입니다

<br>

# CUAI_BASIC
- CUAI_Basic 스터디 1조
- 채용공고 텍스트 마이닝과 생성형AI를 통한 취업 인사이트 도출 및 제공 

## ✍ 요약
- SBERT와 비지도학습을 기반으로 채용공고의 문장단위 분석을 진행하였다.
- KeyBERT, BERTopic을 활용한 군집해석을 통해 인사이트를 도출하였다.
- Django Framework와 생성형 AI를 통해 분석 결과의 활용성을 높혔다. 이를 통해 취업준비생에게 실질적인 도움을 줄 것으로 기대한다.
- 서비스 시현 영상은 <a href="https://youtu.be/UoOJSfqcg98?si=edA7vfTpR70IqVL4"> <img src="https://img.shields.io/badge/-video-8AC926?style=for-the-badge" height="20px" style="margin-bottom: -5px" /> </a>이곳을 통해 확인 하실 수 있습니다!

##
<img src="https://github.com/tgwon/Recruitment_Text_Mining/assets/102985590/0d82da35-9e6e-44b3-87ef-27937bcb28b8"  width="760" height="430">

##
<a href="https://youtu.be/UoOJSfqcg98?si=edA7vfTpR70IqVL4">
  <img src="https://github.com/tgwon/Recruitment_Text_Mining/assets/102985590/8f9e24ab-ebdb-41da-a64c-19e4f3c8153d"  width="830" height="700">
</a>

## 🏆 최종결과
- 제 4회 응용통계학과 분석 공모전 최우수상
