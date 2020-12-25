# 2020 NLP_project

0. 실행 환경
클라우드 서버와 GPU를 제공받는 google colab 에서 진행.


1. NSMC 네이버 영화 리뷰 데이터 감정 분석
NSMC_yja_KoELECTRA.ipynb
KOELECTRA 모델 사용

실행 방법
1. 모든 셀 실행을 통해 1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환 가능.

데이터 출처
https://github.com/e9t/nsmc.git


2. Friends 영화 대본 데이터 감정 분석
Friends_yja_ELECTRA.ipynb
ELECTRA 모델 사용

실행 방법
1. friends_train.json, friends_dev.json, friends_test.json을 압축한 파일 Friends.zip을 업로드한 후 unzip 실행
2. 이후 모든 셀 실행을 통해 1) 데이터 전처리, 2) 모델 구현 및 학습, 3) test set 결과 확인 및 csv 파일 변환 가능.

데이터 출처
http://doraemon.iis.sinica.edu.tw/emotionlines/index.html



3. 다른 모델 및 학습방법 시도

1. NSMC 
   -LSTM : trial1_nsmc_lstm.ipynb
   -BERT : trial2_nsmc_bert.ipynb
2. Friends 
   -데이터 전처리 추가 : trial3_Friends_ELECTRA_전처리.ipynb
   
   
   
   
4. 참고 문헌 및 코드
[1] https://github.com/google-research/bert
[2] https://github.com/google-research/electra
[3] https://github.com/monologg/KoELECTRA
[4] https://github.com/huggingface/transformers

