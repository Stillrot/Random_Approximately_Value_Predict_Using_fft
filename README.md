# Random_Approximately_Value_Predict_Using_fft
Using fft and LSTM to predict the next value.
로또 숫자를 fft변환과 LSTM을 이용해 다음값을 예측해보는 프로그램이다. 
각각의 주파수들을 모두 LSTM으로 예측해내기 때문에 기존값과 유사한 흐름의 값이 나온다. 
활용방안으로는 LSTM의 정확도를 높여서 다음 값을 정확하게 예측시켜 볼 수 있다. 
다른 방법으로는 이 알고리즘을 사용 시 유사한 값의 흐름이 나온다는 점을 이용하여 테스트 데이터를 기준으로 유의미한 랜덤 데이터(예측 데이터)를 추가로 생성시킬 수 있다.



