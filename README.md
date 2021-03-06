# ml-definitive-guide
《파이썬 머신러닝 완벽 가이드》 예제 코드
▣ 1장: 파이썬 기반의 머신러닝과 생태계 이해
1.1. 머신러닝의 개념
머신러닝의 분류
데이터 전쟁
파이썬과 R 기반의 머신러닝 비교
1.2. 파이썬 머신러닝 생태계를 구성하는 주요 패키지
파이썬 머신러닝을 위한 S/W 설치
1.3. 넘파이
넘파이 ndarray 개요
ndarray의 데이터 타입
ndarray를 편리하게 생성하기 - arange, zeros, ones
ndarray의 차원과 크기를 변경하는 reshape( )
넘파이의 ndarray의 데이터 세트 선택하기 – 인덱싱(Indexing)
행렬의 정렬 – sort( )와 argsort( )
선형대수 연산 – 행렬 내적과 전치 행렬 구하기
1.4. 데이터 핸들링 - 판다스
판다스 시작 - 파일을 DataFrame으로 로딩, 기본 API
DataFrame과 리스트, 딕셔너리, 넘파이 ndarray 상호 변환
DataFrame의 컬럼 데이터 세트 생성과 수정
DataFrame 데이터 삭제
Index 객체
데이터 셀렉션 및 필터링
정렬, Aggregation 함수, GroupBy 적용
결손 데이터 처리하기
apply lambda 식으로 데이터 가공
1.5. 정리
 
▣ 2장: 사이킷런으로 시작하는 머신러닝
2.1. 사이킷런 소개와 특징
2.2. 첫 번째 머신러닝 만들어 보기 – 붓꽃 품종 예측하기
2.3. 사이킷런의 기반 프레임워크 익히기
Estimator 이해 및 fit( ), predict( ) 메서드
사이킷런의 주요 모듈
내장된 예제 데이터 세트
2.4. Model Selection 모듈 소개
학습/테스트 데이터 세트 분리 – train_test_split()
교차 검증
GridSearchCV – 교차 검증과 최적 하이퍼 파라미터 튜닝을 한 번에
2.5. 데이터 전처리
데이터 인코딩
피처 스케일링과 정규화
StandardScaler
MinMaxScaler
2.6. 사이킷런으로 수행하는 타이타닉 생존자 예측
2.7. 정리
 
▣ 3장: 평가
3.1. 정확도(Accuracy)
3.2. 오차 행렬
3.3. 정밀도와 재현율
정밀도/재현율 트레이드오프
정밀도와 재현율의 맹점
3.4. F1 스코어
3.5. ROC 곡선과 AUC
3.6. 피마 인디언 당뇨병 예측
3.7. 정리
 
▣ 4장: 분류
4.1. 분류(Classification)의 개요
4.2. 결정 트리
결정 트리 모델의 특징
결정 트리 파라미터
결정 트리 모델의 시각화
결정 트리 과적합(Overfitting)
결정 트리 실습 – 사용자 행동 인식 데이터 세트
4.3. 앙상블 학습
앙상블 학습 개요
보팅 유형 – 하드 보팅(Hard Voting)과 소프트 보팅(Soft Voting)
보팅 분류기(Voting Classifier)
4.4. 랜덤 포레스트
랜덤 포레스트의 개요 및 실습
랜덤 포레스트 하이퍼 파라미터 및 튜닝
4.5. GBM(Gradient Boosting Machine)
GBM의 개요 및 실습
GBM 하이퍼 파라미터 및 튜닝
4.6. XGBoost(eXtra Gradient Boost)
XGBoost 개요
XGBoost 설치하기
파이썬 래퍼 XGBoost 하이퍼 파라미터
파이썬 래퍼 XGBoost 적용 – 위스콘신 유방암 예측
사이킷런 래퍼 XGBoost의 개요 및 적용
4.7. LightGBM
LightGBM 설치
LightGBM 하이퍼 파라미터
하이퍼 파라미터 튜닝 방안
파이썬 래퍼 LightGBM과 사이킷런 래퍼 XGBoost,
LightGBM 하이퍼 파라미터 비교
LightGBM 적용 – 위스콘신 유방암 예측
4.8. 분류 실습 - 캐글 산탄데르 고객 만족 예측
데이터 전처리
XGBoost 모델 학습과 하이퍼 파라미터 튜닝
LightGBM 모델 학습과 하이퍼 파라미터 튜닝
4.9. 분류 실습 – 캐글 신용카드 사기 검출
언더 샘플링과 오버 샘플링의 이해
데이터 일차 가공 및 모델 학습/예측/평가
데이터 분포도 변환 후 모델 학습/예측/평가
이상치 데이터 제거 후 모델 학습/예측/평가
SMOTE 오버 샘플링 적용 후 모델 학습/예측/평가
4.10. 스태킹 앙상블
기본 스태킹 모델
CV 세트 기반의 스태킹
4.11. 정리
 
▣ 5장: 회귀
5.1. 회귀 소개
5.2. 단순 선형 회귀를 통한 회귀 이해
5.3. 비용 최소화하기 – 경사 하강법(Gradient Descent) 소개
5.4. 사이킷런 LinearRegression을 이용한 보스턴 주택 가격 예측
LinearRegression 클래스 - Ordinary Least Squares
회귀 평가 지표
LinearRegression을 이용해 보스턴 주택 가격 회귀 구현
5.5. 다항 회귀와 과(대)적합/과소적합 이해
다항 회귀 이해
다항 회귀를 이용한 과소적합 및 과적합 이해
편향-분산 트레이드오프(Bias-Variance Trade off)
5.6. 규제 선형 모델 – 릿지, 라쏘, 엘라스틱넷
규제 선형 모델의 개요
릿지 회귀
라쏘 회귀
엘라스틱넷 회귀
선형 회귀 모델을 위한 데이터 변환
5.7. 로지스틱 회귀
5.8. 회귀 트리
5.9. 회귀 실습 – 자전거 대여 수요 예측
데이터 클렌징 및 가공
로그 변환, 피처 인코딩과 모델 학습/예측/평가
5.10. 회귀 실습 – 캐글 주택 가격: 고급 회귀 기법
데이터 사전 처리(Preprocessing)
선형 회귀 모델 학습/예측/평가
회귀 트리 모델 학습/예측/평가
회귀 모델의 예측 결과 혼합을 통한 최종 예측
스태킹 앙상블 모델을 통한 회귀 예측
5.11. 정리
 
▣ 6장: 차원 축소
6.1. 차원 축소(Dimension Reduction) 개요
6.2. PCA(Principal Component Analysis)
PCA 개요
6.3. LDA(Linear Discriminant Analysis)
LDA 개요
붓꽃 데이터 세트에 LDA 적용하기
6.4. SVD(Singular Value Decomposition)
SVD 개요
사이킷런 TruncatedSVD 클래스를 이용한 변환
6.5. NMF(Non-Negative Matrix Factorization)
NMF 개요
6.6. 정리
 
▣ 7장: 군집화
7.1. K-평균 알고리즘 이해
사이킷런 KMeans 클래스 소개
K-평균을 이용한 붓꽃 데이터 세트 군집화
군집화 알고리즘 테스트를 위한 데이터 생성
7.2. 군집 평가(Cluster Evaluation)
실루엣 분석의 개요
붓꽃 데이터 세트를 이용한 군집 평가
군집별 평균 실루엣 계수의 시각화를 통한 군집 개수 최적화 방법
7.3. 평균 이동
평균 이동(Mean Shift)의 개요
7.4. GMM(Gaussian Mixture Model)
GMM(Gaussian Mixture Model) 소개
GMM을 이용한 붓꽃 데이터 세트 군집화
GMM과 K-평균의 비교
7.5. DBSCAN
DBSCAN 개요
DBSCAN 적용하기 – 붓꽃 데이터 세트
DBSCAN 적용하기 – make_circles( ) 데이터 세트
7.6. 군집화 실습 – 고객 세그먼테이션
고객 세그먼테이션의 정의와 기법
데이터 세트 로딩과 데이터 클렌징
RFM 기반 데이터 가공
RFM 기반 고객 세그먼테이션
7.7. 정리
 
▣ 8장: 텍스트 분석
NLP이냐 텍스트 분석이냐?
8.1. 텍스트 분석 이해
텍스트 분석 수행 프로세스
파이썬 기반의 NLP, 텍스트 분석 패키지
8.2. 텍스트 사전 준비 작업(텍스트 전처리) - 텍스트 정규화
클렌징
텍스트 토큰화
스톱 워드 제거
Stemming과 Lemmatization
8.3. Bag of Words – BOW
BOW 피처 벡터화
사이킷런의 Count 및 TF-IDF 벡터화 구현: CountVectorizer, TfidfVectorizer __BOW 벡터화를 위한 희소 행렬
희소 행렬 - COO 형식
희소 행렬 – CSR 형식
8.4. 텍스트 분류 실습 – 20 뉴스그룹 분류
텍스트 정규화
피처 벡터화 변환과 머신러닝 모델 학습/예측/평가
사이킷런 파이프라인(Pipeline) 사용 및 GridSearchCV와의 결합
8.5. 감성 분석
감성 분석 소개
지도학습 기반 감성 분석 실습 – IMDB 영화평
비지도학습 기반 감성 분석 소개
SentiWordNet을 이용한 감성 분석
VADER를 이용한 감성 분석
8.6. 토픽 모델링(Topic Modeling) - 20 뉴스그룹
8.7. 문서 군집화 소개와 실습(Opinion Review 데이터 세트)
문서 군집화 개념
Opinion Review 데이터 세트를 이용한 문서 군집화 수행하기
군집별 핵심 단어 추출하기
8.8. 문서 유사도
문서 유사도 측정 방법 – 코사인 유사도
두 벡터 사잇각
Opinion Review 데이터 세트를 이용한 문서 유사도 측정
8.9. 한글 텍스트 처리 – 네이버 영화 평점 감성 분석
한글 NLP 처리의 어려움
KoNLPy 소개
데이터 로딩
8.10. 텍스트 분석 실습–캐글 Mercari Price Suggestion Challenge
데이터 전처리
피처 인코딩과 피처 벡터화
릿지 회귀 모델 구축 및 평가
LightGBM 회귀 모델 구축과 앙상블을 이용한 최종 예측 평가
8.11. 정리
 
▣ 9장: 추천 시스템
9.1. 추천 시스템의 개요와 배경
추천 시스템의 개요
온라인 스토어의 필수 요소, 추천 시스템
추천 시스템의 유형
9.2. 콘텐츠 기반 필터링 추천 시스템
9.3. 최근접 이웃 협업 필터링
9.4. 잠재 요인 협업 필터링
잠재 요인 협업 필터링의 이해
행렬 분해의 이해
확률적 경사 하강법을 이용한 행렬 분해
9.5. 콘텐츠 기반 필터링 실습 – TMDB 5000 영화 데이터 세트
장르 속성을 이용한 영화 콘텐츠 기반 필터링
데이터 로딩 및 가공
장르 콘텐츠 유사도 측정
장르 콘텐츠 필터링을 이용한 영화 추천
9.6. 아이템 기반 최근접 이웃 협업 필터링 실습
데이터 가공 및 변환
영화 간 유사도 산출
아이템 기반 최근접 이웃 협업 필터링으로 개인화된 영화 추천
9.7. 행렬 분해를 이용한 잠재 요인 협업 필터링 실습
9.8. 파이썬 추천 시스템 패키지 - Surprise
Surprise 패키지 소개
Surprise를 이용한 추천 시스템 구축
Surprise 주요 모듈 소개
Surprise 추천 알고리즘 클래스
베이스라인 평점
교차 검증과 하이퍼 파라미터 튜닝
Surprise를 이용한 개인화 영화 추천 시스템 구축
9.9. 정리
