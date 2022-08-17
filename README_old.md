# TIA(Today I Analyzed) - My Project
## Description
가설 검정을 통한 데이터 분석 뿐만 아니라 웹 스크래핑이나 API를 사용한 데이터 수집, 머신러닝 예측 모델링 등의 다양한 분석 프로젝트를 진행하고 있습니다.

**[1. 넷플릭스의 콘텐츠 보유 현황과 수급 전략 분석](https://github.com/sw-song/TIA/blob/main/00_01_netflix_trend_analysis/analysis_strategy_in_netflix.ipynb)**
```
Step 1. 가설 설정
Step 2. 기본 전처리
     2-1. 불필요한 컬럼 제거
     2-2. 불필요한 행 제거
     2-3. 데이터 타입 변환
     2-4. 시계열 데이터 변환
     2-5. 데이터 구간(시간) 분할
Step 3. 가설 검정
     3-1. 특정 콘텐츠 유형에 대한 집중 수급 여부 분석
     3-2. 특정 국가를 겨냥한 콘텐츠 현황 분석
     3-3. 콘텐츠 수급 대상 연도 분석
     3-4. 넷플릭스의 주요 소비자 타겟(연령대) 분석
     3-5. 콘텐츠 평균 재생 시간 분석
     3-5. 넷플릭스에서 주로 수급하는 콘텐츠 장르 분석
Step 4. 종합 결론
```

**[2. 커머스 고객의 연간 지출액 분석을 통한 매출 개선 시뮬레이션](https://github.com/sw-song/TIA/blob/main/00_02_ecommerce/ecommerce.ipynb)**
```
Step 1. 가설 설정
Step 2. 가설 검정
     2-1. 평균 세션 접속 시간에 따른 연간 지출액 확인
     2-2. 가입 기간에 따른 연간 지출액 확인
     2-3. 앱, 웹 사용 시간 비교
     2-4. 앱 사용 시간에 따른 연간 지출액 확인
     2-5 웹 사용 시간에 따른 연간 지출액 확인
     2-6. 가입 기간에 따른 구매 경로에 대한 선호도 차이 분석
     2-7. 가입 기간에 따른 구매 경로 별 연간 지출액 확인
Step 3. 분석 결과
Step 4. 매출 개선 시뮬레이션
```

**[3. 증권사(키움증권) API를 활용한 비 실시간(Batch) 주가 정보 수집](https://github.com/sw-song/TIA/blob/main/00_03_pykiwoom/pykiwoom_test.ipynb)**
```
Step 1. 개요
     1-1. 주식 데이터 수집 방식 비교
     1-2. pykiwoom
Step 2. 로그인 및 접속 상태 조회
     2-1. 환경 설정
     2-2. 자동 로그인 실행
Step 3. 기본 종목 정보 수집
     3-1. 종목 코드 수집
     3-2. 개별 종목 정보 수집
Step 4. 주가 정보 수집
     4-1. 개별 주식 정보 수집
     4-2. 개별 주식 일봉 차트 조회
```

**[4. 가설 검정을 통한 카카오 주식 매매 백테스팅](https://github.com/sw-song/TIA/blob/main/00_04_backtesting/kakao_backtesting.ipynb)**
```
Step 1. 카카오 주식을 1999년 11월 11일에 100만원 치 샀다면 오늘 얼마일까?
     1-1. 라이브러리 호출 및 데이터 확인
     1-2. 가설 검정
Step 2. 카카오 주가는 언제나 상승장이었을까?
     2-1. 가설 검정(일봉 차트)
     2-2. 가설 검정(365일 이동평균선)
Step 3. 수면제 먹고 자는 것보다 더 나은 수익을 낼 수 있을까?
     3-1. 이동 평균 데이터 추가
     3-2. 데이터 전처리(change 컬럼)
     3-3. 백테스팅 전략 설계
     3-4. 데이터 전처리(매매 구간 처리 - overs 컬럼)
     3-5. 데이터 전처리(매매 신호 표기 - signal 컬럼)
     3-6. 가설 검정(매입액 현재가 비교)
```

**[5. (1) 문제 상황 가정 및 데이터 전처리 | 광고 프로모션 효율 증진을 위한 커머스 고객 세분화](https://github.com/sw-song/TIA/blob/main/00_05_customer_segmentation/customer_personality_analysis.ipynb)**
```
Step 1. 문제 상황 가정 및 데이터 전처리 
     1-1. 라이브러리 호출 및 데이터 확인 
     1-2. 일부 컬럼 제거 
     1-3. 컬럼명, 데이터타입 형식 통일 
     1-4. 현재 날짜 가정 
     1-5. 이상치 처리
```

**[5. (2) 고객 군집 분석 | 광고 프로모션 효율 증진을 위한 커머스 고객 세분화](https://github.com/sw-song/TIA/blob/main/00_05_customer_segmentation/customer_personality_analysis.ipynb)**
```
Step 2. 고객 그룹 세분화
     2-1. 나이에 따라 분류하기
     2-2. 최근 구매일자에 따라 분류하기
     2-3. 가입 기간에 따라 분류하기
     2-4. 컴플레인 여부에 따라 분류하기
     2-5. 온/오프라인 선호도에 따라 분류하기
     2-6. 프로모션 동의 여부에 따라 분류하기
     2-7. 머신러닝으로 분류하기
```

**[6. 과거 주가 데이터로 미래 주가를 예측할 수 있을까? | 파이썬 패턴 검색기 구현](https://github.com/sw-song/TIA/blob/main/00_06_pattern_search/pattern_search.ipynb)**
```
Step 1. 라이브러리 호출 및 코스피 지수 추출
Step 2. 기준 구간 지정 및 시각화
Step 3. 패턴 검색기 구현
Step 4. 검색 구간 이후의 추세 확인
```

**[7. AI, 딥러닝으로 주가를 예측할 수 있다고?](https://github.com/sw-song/TIA/blob/main/00_07_price_forecasting/linear_reg.ipynb)**
```
Step 1. 시계열 데이터와 예측
Step 2. 예측 실험
Step 3. 결과 해석
```

**[8. (코드)Bitcoin price forecasting](https://github.com/sw-song/TIA/blob/main/00_08_holt_winters/bitcoin_predict.ipynb)**
```
Step 1. 데이터 전처리
Step 2. 이동 평균과 지수 평활
     2-1. 단순 종가
     2-2. 120일, 300일 이동 평균
     2-3. 단순 지수 평활
Step 3. 추세와 계절성을 추가한 2차, 3차 지수 평활
     3-1. 2차 지수 평활
     3-2. 3차 지수 평활
```

**[9. (코드)Time series - autocorrelation](https://github.com/sw-song/TIA/blob/main/00_09_ts_autocorrelation/acf_pacf.ipynb)**
```
Step 1. 데이터 불러오기
Step 2. 종가 데이터 분석
     2-1. 차트 시각화
     2-2. 자기상관성
Step 3. 차분 데이터 분석
     3-1. 자기상관성
     3-2. 정상성
```

**[10. (코드)Predict Income](https://github.com/sw-song/TIA/blob/main/00_10_predict_income/predict_income.ipynb)**
```
Step 1. Prepare datasets and EDA
     1-1. Seperate columns with numerical columns and categorical columns
     1-2. Visualize distribution of data in categorical columns
     1-3. Show distribution of data in numerical columns
     1-4. Null check for categorical values
     1-5. Replace Null value with the mode of each column data
Step 2. Data Preprocessing for ML
     2-1. Seperate X(Input) and y(Output, forcasting)
     2-2. Transform y's value to number(one-hot-encoding)
     2-3. Transfer X's categorical value to text(one-hot-encoding)
     2-4. Split X data to train-set and test-set
     2-5. Standard Scailing for numerical values - train and test dataset
     2-6. PCA(Principal Component Analysis) and Standard Scailing for sparse values - train and test dataset
     2-7. Concatenation numerical values and sparse values
     2-8. Check the distribution of two datasets - train and test dataset
Step 3. Modeling and Prediction
     3-1. Logistic Regression
     3-2. Random Forest
     3-3. XGBoost
     3-4. Light GBM
     3-5. Deep Learning
```

**[11. 코스피, 달러 정보 수집부터 시각화까지](https://github.com/sw-song/TIA/blob/main/00_11_kospi_analysis/kospi_analysis.ipynb)**
```
Step 1. KOSPI 200 거래정보 가져오기
Step 2. 환율정보 가져오기
Step 3. 데이터 병합
Step 4. 시계열 데이터 그려보기 with 평균, 편차
```

**[12. 파이썬으로 최적의 포트폴리오 찾기](https://github.com/sw-song/TIA/blob/main/00_12_portfolio/portfolio(3).ipynb)**
```
Step 1. 야후 파이낸스 데이터 추출
Step 2. 일일 수익률 및 최종 수익률 확인
Step 3. 일일 수익률간 상관관계 시각화
Step 4. 변동성(위험) 대비 수익률 시각화
Step 5. 샤프 지수에 따른 포트폴리오 비율 시각화
Step 6. 사프 지수에 따른 포트폴리오 수익률 및 변동성 시각화
Step 7. 최적의 포트폴리오 비율
```

**[13. ffn 사용 퀀트 분석](https://github.com/sw-song/TIA/blob/main/00_13_backtest/ffn.ipynb)**
```
Step 1. 데이터 가져오기
Step 2. 기준일 베이스 스케일링
Step 3. 수익률 확인
Step 4. 기술통계
Step 5. 객체 다루기
```

**[14. 뉴스 기사와 주가의 상관분석](https://github.com/sw-song/TIA/blob/main/00_14_stock_sentiment_analysis/nvda.ipynb)**
```
Step 1. 데이터 추출
     1-1. 뉴스 기사 수집
     1-2. 주가 데이터 수집
Step 2. 감성 분석
     2-1. 사전 학습 모델
     2-2. 감성 계량화
Step 3. 시각화 및 상관 분석
     3-1. 데이터 스케일링
     3-2. 상관 분석
```