# Classification_of_climate_technology  

## '자연어 기반 기후 기술 분류' By DACON

### Log  
* 7/23  
참가 시작 / 데이터 셋 확인 및 분석  
불필요하다고 생각하는 Column에 대한 삭제  

* 7/24  
주제 분류를 위한 CNN 모델 구현 및 Test(GELU)  

* 7/25  
다른 활성화 함수로 훈련(Relu, tanh..)  

* 7/26  
데이터 불균형을 바로 잡기 위한 아이디어 고민, 관련 레포지토리 생성  

* 7/27  
Train Data에 대한 데이터 증폭 기능 구현, 코드 수정, 배치 사이즈 추가  

* 7/28  
증폭한 데이터를 대상으로 훈련 진행 -> 성능 향상은 미비  

* 7/29  
형태소 분석기 : Komoran -> Okt  
LSTM 구현 및 테스트  

* 7/30  
'train.csv' 파일의 '과제명'을 기준으로, 단어의 빈도 수 확인 및 불용어 리스트에 추가  
이후 '요약문 - 한글 키워드'를 대상으로, 텍스트 데이터를 합쳐 새로 구성하는 방안 실행 계획 중  
내일, 모레를 사용해 각각 훈련 예정