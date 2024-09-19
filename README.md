## ☞ [Onlilne Retail 고객데이터 분석]
- 개발언어 및 프레임워크 : `Python`, `SQL`
- 작업툴 : `Jupyter Notebook`, `DBeaver`, `Tableau`
- 인원 : 1명
- 기간 : 24.09.13 ~ 
- 담당 역할 : 데이터 전처리, 데이터 추출, EDA, Cohort 분석, 가설 설정
- 주요 내용 :
    - 데이터 전처리
      - 같은 제품 코드를 기준으로 상품명 통일화
      - 날짜 컬럼을 (년-월-일) (시:분:초)로 나눈 파생변수 생성
      - scikit-learn의 TF-IDF로 상품명 카테고리화 진행
        - 상품명의 종류가 3775개 였기 때문에 구매 물품에 대한 고객간의 차별점을 찾기 어려울 것이라고 판단했기 때 
      - 고객 구매주기 구매주기 분석
        - 고객 구매주기를 BoxPlot과 ViolinPlot으로 시각화
        - 이상치가 상당수 존재 해서 이상차의 영향을 받지 않는 중앙 값으로 고객 구매주기의 기준을 정함
  - 시각화
    - Pandas 라이브러리# ☞ [Onlilne Retail 고객데이터 분석]
- 개발언어 및 프레임워크 : `Python`, `SQL`
- 작업툴 : `Jupyter Notebook`, `DBeaver`, `Tableau`
- 인원 : 1명
- 기간 : 24.09.13 ~ 
- 담당 역할 : 데이터 전처리, 데이터 추출, EDA, Cohort 분석
- 주요 내용 :
    - 데이터 전처리
      - 같은 제품 코드를 기준으로 상품명 통일화
      - 날짜 컬럼을 (년-월-일) (시:분:초)로 나눈 파생변수 생성
      - scikit-learn의 TF-IDF로 상품명 카테고리화 진행
        - 상품명의 종류가 3775개 였기 때문에 구매 물품에 대한 고객간의 차별점을 찾기 어려울 것이라고 판단했기 때 
      - 고객 구매주기 구매주기 분석
        - 고객 구매주기를 BoxPlot과 ViolinPlot으로 시각화
        - 이상치가 상당수 존재 해서 이상차의 영향을 받지 않는 중앙 값으로 고객 구매주기의 기준을 정함
  - 시각화
    - Pandas 라이브러리를 사용하여 데이터 추출 후 matplotlib으로 시각화
    - SQL로 데이터 추출 후 Tableau로 시각화
  - Cohort 분석
    - 각 년/월별 유입된 신규고객을 기준으로 Retention Rate 분석
  - 가설 설정
      1. ㅂ
      2. ㅠ
      
  - 전처리 기법 및 모델 사용 이유, 웹 페이지 구성의 보다 자세한 내용은 ☞ [요약 보고서]() 에서 확인 하실 수 있습니다.
  
- 결과물 바로가기: ☞ [요약 보고서](), ☞ [EDA 및 전처리](https://github.com/jjhwk/Online-Retail/blob/main/Online%20Retail/EDA.ipynb),
          ☞ [Cohort 분석](https://github.com/jjhwk/Online-Retail/blob/main/Online%20Retail/Cohort.ipynb)
