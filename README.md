# 농사직설
- 활동명 : [2021 데이터 청년 캠퍼스](https://dataonair.or.kr/bigjob/)
- 기간 : 2021.06.28 ~ 2021.08.27
- 팀명 : 농4직설(4조)
  - 이도영
  - 박지홍
  - [양예원](https://github.com/YangYangYewon)
  - [이주형](https://github.com/yamiblack) 
- 기술 멘토 : [강민구](https://github.com/minqukanq)
<br>

## 주제 및 기대효과
- Transformer 기반의 농산물 가격 예측 모델
  - 비교를 위해 LSTM까지 구현 
  - PyTorch 활용하여 Transformer 및 LSTM 구현
- 농산물 수급 조절 가능
- 한정되지 않은 품종 및 지역 예측
<br>

## 발표 영상
[![Video Label](https://user-images.githubusercontent.com/50551349/131089824-34440ddd-9d32-44f6-ba30-4d9deb1e1b98.png)](https://www.youtube.com/watch?v=1unGjcdArFs)
<br>

## Overview
![image](https://user-images.githubusercontent.com/50551349/131090174-4e8cf676-e319-4d5e-9b2d-7bce5d29c873.png)
<br>

## 변수 선정
![image](https://user-images.githubusercontent.com/50551349/131014654-ac4e23a6-090d-4ecd-bd08-03eabc2f8669.png)
<br>

## 데이터 출처
![image](https://user-images.githubusercontent.com/50551349/131014702-3f8fee9f-6853-4e51-ad07-0393bce02e2b.png)
<br>

## 프로젝트 결과
### 1. Transformer vs LSTM
![image](https://user-images.githubusercontent.com/50551349/131090333-10f839b7-2993-431c-9abb-1efe87b7adc4.png)
- RMSE 비교시 양파는 Transformer, 대파는 LSTM에서 비교적 좋은 성능 확인 가능

### 2. LSTM_대파
![image](https://user-images.githubusercontent.com/50551349/131091809-4b60f8ac-9e97-4fea-95dd-461edafa01ea.png)
- LSTm에서 lagging 심하게 발생

### 3. Transformer_양파
![image](https://user-images.githubusercontent.com/50551349/131091521-9e003758-c5f9-4d2c-90f6-a7f1625ec01f.png)
- Transformer에서는 lagging 발생X

![image](https://user-images.githubusercontent.com/50551349/131091892-20ea87cc-ad1b-4bbf-bc8c-05480c99f2ba.png)
- LSTM과 다르게 Transformer에서는 epoch가 증가할수록 성능도 상승 
<br>

## 사용 기술 스택
- Python
- PyTorch
- Pandas
- NumPy
<br>




