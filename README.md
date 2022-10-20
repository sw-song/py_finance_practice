# Py-Finance Tutorials - Practice
금융, 비즈니스 데이터 분석 튜토리얼입니다. 파이썬 및 데이터 분석 기초, 시계열 데이터에 대한 기초 수준의 이해를 전제로 합니다.

---

**[01. ffn(Financial Functions for Python)으로 퀀트 분석 시간을 아껴보자](https://github.com/sw-song/ds-study/blob/main/tutorials/01/ffn.ipynb)**
```
Step 1. 데이터 추출
Step 2. 기준일 스케일링
Step 3. 수익률
Step 4. 기술통계
Step 5. 손실률
Step 6. 기타 기술통계
```

**[02. 파이썬 bt 패키지를 활용한 미국 주식 포트폴리오 백테스트](https://github.com/sw-song/ds-study/blob/main/tutorials/02/bt.ipynb)**
```
Step 1. 작업 흐름
Step 2. 사용 예시
Step 3. display() 함수
Step 4. 분석 및 결론
```

**[03. 파이썬으로 최적의 포트폴리오 비율 찾기(한국 주식, 국채 + 미국 주식, 국채)](https://github.com/sw-song/ds-study/blob/main/tutorials/03/portfolio(3).ipynb)**
```
Step 1. 야후 파이낸스 데이터 추출
Step 2. 일일 수익률 및 최종 수익률 확인
Step 3. 일일 수익률간 상관관계 시각화
Step 4. 변동성(위험) 대비 수익률 시각화
Step 5. 샤프 지수에 따른 포트폴리오 비율 시각화
Step 6. 사프 지수에 따른 포트폴리오 수익률 및 변동성 시각화
Step 7. 최적의 포트폴리오 비율
```

**[04. 패턴 검색 - 과거 주가 데이터로 미래 주가를 예측할 수 있을까?](https://github.com/sw-song/ds-study/blob/main/tutorials/04/pattern_search.ipynb)**
```
Step 0. 패턴 검색
Step 1. 코스피 종가 가져오기
Step 2. 기준 구간 지정 및 시각화
Step 3. 패턴 검색기 구현
Step 4. 검색 구간 이후의 추세 확인
```

**[05. 개별 종목에 대한 단순 보유와 골든 크로스 전략의 수익률 비교 (feat. 카카오)](https://github.com/sw-song/ds-study/blob/main/tutorials/05/kakao_backtesting.ipynb)**
```
Step 0. 전략
Step 1. 데이터 불러오기
Step 2. 장기 보유 성과 확인
Step 3. 장단기 이동평균 그래프 확인
Step 4. 보유 구간 표기
Step 5. 매매 시점 표기
Step 6. 전략 수익률 계산
```

**[06. 파이썬 비트코인 가격 예측 - 1,2,3차 지수 평활](https://github.com/sw-song/ds-study/blob/main/tutorials/06/bitcoin_predict.ipynb)**
```
Step 1. 데이터 전처리
Step 2. 이동평균과 단순 지수평활
     2-1. 일별 비트코인 가격
     2-2. 일별 비트코인 가격의 이동평균
     2-3. 일별 비트코인 가격의 단순 지수평활
     2-4. 이동평균과 단순 지수평활의 비교
Step 3. 추세와 계절성을 추가한 2차, 3차 지수평활
     3-1. 2차 지수평활
     3-2. 3차 지수평활
Step 4. (결론) 비트코인 가격 전망
```

**[07. 회귀 모형을 활용한 이더리움 가격 예측](https://github.com/sw-song/ds-study/blob/main/tutorials/07/linear_reg.ipynb)**
```
Step 1. 시계열 데이터와 추세
Step 2. 모델 학습
     2-1. 데이터 불러오기
     2-2. 학습 및 평가 데이터 생성
     2-3. 모델 적합
Step 3. 모델 평가
```

**[08. 뉴스 기사와 주가의 상관분석 - 엔비디아](https://github.com/sw-song/ds-study/blob/main/tutorials/08/nvda.ipynb)**
```
Step 1. 데이터 추출
     1-1. 뉴스 기사 수집
     1-2. 주가 정보 수집
Step 2. 감성 분석
     2-1. 감성 분석 모델 불러오기
     2-2. 감성 계량화
Step 3. 주가 데이터 스케일링
Step 4. 상관 분석
```

**[09. 지금 달러는 얼마나 비싼 걸까? 그럼 코스피는? - 데이터 수집 및 차트 시각화](https://github.com/sw-song/ds-study/blob/main/tutorials/09/kospi_analysis.ipynb)**
```
Step 0. XHR이란
Step 1. KOSPI 200 거래 정보 가져오기
Step 2. 환율 정보 가져오기
Step 3. 데이터 병합
Step 4. 평균 및 표준편차를 포함한 시계열 데이터 그리기
Step 5. 표준화를 통해 시계열 겹쳐보기
```

**[10. 키움증권 API를 활용한 주식 정보 및 일봉 데이터 수집](https://github.com/sw-song/ds-study/blob/main/tutorials/10/pykiwoom_test.ipynb)**
```
Step 0. 주식 데이터 수집 방법
Step 1. 환경 설정
Step 2. 자동 로그인
Step 3. 종목 코드 수집
Step 4. 개별 종목 정보 수집
Step 5. 개별 주식 정보 수집
Step 6. 개별 주식 일봉 차트 조회
```

**[11. 단타 vs 장기보유 - 자기상관분석 및 정상성 검정](https://github.com/sw-song/ds-study/blob/main/tutorials/11/acf_pacf.ipynb)**
```
Step 1. 데이터 불러오기
Step 2. 종가 데이터
     2-1. 차트 시각화
     2-2. 자기상관성
Step 3. 차분 데이터
     3-1. 차분 데이터 시각화
     3-2. 차분 데이터의 자기상관성
     3-3. 정상성
Step 4. 결론
```

**[12. 넷플릭스의 콘텐츠 보유 현황과 수급 전략 분석](https://github.com/sw-song/ds-study/blob/main/tutorials/12/analysis_strategy_in_netflix.ipynb)**
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

**[13. 커머스 고객의 연간 지출액 분석을 통한 매출 개선 시뮬레이션](https://github.com/sw-song/ds-study/blob/main/tutorials/13/ecommerce.ipynb)**
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

**[14. 딥러닝이 언제나 좋을까? - 소득 구간 예측](https://github.com/sw-song/ds-study/blob/main/tutorials/14/predict_income.ipynb)**
```
Step 1. EDA
     1-1. 수치형, 범주형 컬럼 구분
     1-2. 범주형 데이터 분포 시각화
     1-3. 수치형 데이터 분포 시각화
     1-4. 범주형 데이터 Null 값 확인
     1-5. Null 값에 대해 최빈값 채우기
Step 2. 데이터 전처리
     2-1. Feature X와 예측값 y로 구분
     2-2. 예측값 y에 대해 원핫 인코딩
     2-3. 범주형 Feature X에 대해 원핫 인코딩
     2-4. 학습, 평가 데이터 구분
     2-5. 수치형 Feature 표준화
     2-6. 범주형 Feature 차원축소(PCA) 및 표준화
     2-7. 수치형 Feature와 범주형 Feature 병합
     2-8. Feature 분포 확인
Step 3. 모델링 및 예측
     3-1. Logistic Regression
     3-2. Random Forest
     3-3. XGBoost
     3-4. Light GBM
     3-5. Deep Learning
```

**[15-(1). 광고 프로모션 효율 증진을 위한 커머스 고객 세분화 - 문제 상황 가정 및 데이터 전처리](https://github.com/sw-song/ds-study/blob/main/tutorials/15/customer_analysis_1.ipynb)**
```
Step 1. 문제 상황 가정 및 데이터 전처리 
     1-1. 라이브러리 호출 및 데이터 확인 
     1-2. 일부 컬럼 제거 
     1-3. 컬럼명, 데이터타입 형식 통일 
     1-4. 현재 날짜 가정 
     1-5. 이상치 처리
```

**[15-(2). 광고 프로모션 효율 증진을 위한 커머스 고객 세분화 - 고객 군집 분석](https://github.com/sw-song/ds-study/blob/main/tutorials/15/customer_analysis_2.ipynb)**
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

**[16. 블로그 포스팅을 활용한 주식 시장 동향 분석](https://github.com/sw-song/ds-study/blob/main/tutorials/16/blog-sent-analysis.ipynb)**
```
Step 1. 블로그 정보 수집
     1-1. 웹사이트 구조 및 데이터 호출 정보 확인
     1-2. 단일 페이지 데이터 호출
     1-3. 다중 페이지 데이터 호출(함수)
Step 2. 블로그 내용 수집
     2-1. HTML 태그 정보 확인
     2-2. 데이터 호출 정보 확인
     2-3. 단일 페이지 데이터 호출(함수)
Step 3. 감성 분류
     3-1. 허깅페이스 모델 검색
     3-2. 추론 모델 인스턴스 생성 및 테스트
     3-3. 단일 포스팅 내 텍스트 감성 분류
     3-4. 전체 7일간 포스팅 감성 분류
     3-5. 결과
```