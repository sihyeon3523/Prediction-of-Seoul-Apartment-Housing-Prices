# Prediction-of-Seoul-Apartment-Housing-Prices
<pre>
Project : 머신러닝을 활용한 서울특별시 아파트 매매가 예측 / 대학교 졸업작품으로 진행 
Date : 2019.01 ~ 2019.07
Role : 데이터 수집 / EDA / 논문 분석 / 산출물 제작 
</pre>
<br>

## 분석 설명
> 분석의 범주
  - Training Set : 2013년 ~ 2017년 서울특별시 아파트 실거래가 데이터
  - Test Set : 2018년 서울특별시 아파트 실거래가 데이터
<br> 

> 분석 과정 
  - 데이터 수집 
  
| 데이터셋         | 설명                               | 형태        | 데이터 출처                 |
| ---------------- | ---------------------------------- | ----------- | --------------------------- |
| 행정동 특성 변수     | 행정동별 기초수급자 수/인구 분포 등의 정보 포함 | 정형 데이터 | 외부(통계청, 국토교통부)            |
| 시설 특성 변수 | 아파트 단지별 학교/교통시설 등의 주변 시설 정보             | 정형 데이터 | 외부(공공데이터포털, 자체 정제)            |
| 아파트 특성 변수         | 층 수/공시지가/전용면적 등의 아파트 특성 정보                | 정형 데이터 | 외부(공공데이터포털, 자체 정제)          |
| 경제 관련 변수      | 국내 총생산/경제 성장률 등의 경제 관련 변수            | 정형 데이터 | 외부(우리은행, 통계청)             |
<br>

- 데이터 전처리 및 분석
   - 상관계수 파악 및 변수 제거
   - 군집화 관련 변수 설정
   - 결측치 및 이상치 제거
   - 군집화
<br>

- 모델링
   - 3개의 군집으로 나눠, 군집별 적절한 모델 적용
<br>

> 웹 사이트 제작 
  - [웹 사이트 URL](https://whdzl1213.wixsite.com/hanyang)
<br>

## 분석 산출물
- [분석산출물_판넬.pdf](https://github.com/sihyeon3523/Prediction-of-Seoul-Apartment-Housing-Prices/blob/f017c42247614772e2f63baa29c76ea9284ceade/%EB%B6%84%EC%84%9D%20%EC%82%B0%EC%B6%9C%EB%AC%BC/%EB%B6%84%EC%84%9D%EC%82%B0%EC%B6%9C%EB%AC%BC_%ED%8C%90%EB%84%AC.pdf)
- [분석산출물_보고서.pdf](https://github.com/sihyeon3523/Prediction-of-Seoul-Apartment-Housing-Prices/blob/7cd1d5ca8ad53e8b27121512120e471f7de5a2a5/%EB%B6%84%EC%84%9D%20%EC%82%B0%EC%B6%9C%EB%AC%BC/%EB%B6%84%EC%84%9D%EC%82%B0%EC%B6%9C%EB%AC%BC_%EB%B3%B4%EA%B3%A0%EC%84%9C.pdf)

