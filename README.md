# [데이터분석 프로젝트]

## 1. 패션 상품 구매 데이터 분석을 통한 브랜드 및 고객 분석
분석 목표 : 신규 구매 전반 분석 및 결과 도식화
> [프로젝트 최종 결과물(분석 인사이트 및 전략)](https://github.com/Lucia-KIM/project/blob/main/%ED%8C%A8%EC%85%98%EA%B8%B0%EC%97%85%20%EA%B5%AC%EB%A7%A4%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/%E1%84%83%E1%85%A6%E1%84%8B%E1%85%B5%E1%84%90%E1%85%A5%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8%E1%84%8B%E1%85%B3%E1%86%AF%20%E1%84%90%E1%85%A9%E1%86%BC%E1%84%92%E1%85%A1%E1%86%AB%20%E1%84%8B%E1%85%B5%E1%86%AB%E1%84%89%E1%85%A1%E1%84%8B%E1%85%B5%E1%84%90%E1%85%B3%E1%84%86%E1%85%B5%E1%86%BE%20%E1%84%8C%E1%85%A5%E1%86%AB%E1%84%85%E1%85%A3%E1%86%A8.pdf) / 데이터분석 최종코드([Stpe1](https://nbviewer.jupyter.org/github/Lucia-KIM/project/blob/main/%ED%8C%A8%EC%85%98%EA%B8%B0%EC%97%85%20%EA%B5%AC%EB%A7%A4%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/STEP1_Final_Version.ipynb)/[Stpe2](https://nbviewer.jupyter.org/github/Lucia-KIM/project/blob/main/%ED%8C%A8%EC%85%98%EA%B8%B0%EC%97%85%20%EA%B5%AC%EB%A7%A4%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/STPE2_Final_Version.ipynb)/[Stpe3](https://nbviewer.jupyter.org/github/Lucia-KIM/project/blob/main/%ED%8C%A8%EC%85%98%EA%B8%B0%EC%97%85%20%EA%B5%AC%EB%A7%A4%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/STEP3_Final_Version.ipynb))

** _본 프로젝트는 원티드 프리온보딩 코스에서 데이터를 제공받았으며, 5명의 팀원들과 함께 작업한 내용입니다._

#### 1)데이터 정보 
> 패션상품(의류 및 가방)의 2021년 1분기 신규 구매 데이터
- 데이터 건수: 1471 개 
- 데이터 포함 정보(컬럼) : 주문 상품 브랜드 및 아이템명, 주문일자, 유저 가입일자, 상품 타입, 주문 상품 종류 외

#### 2)프로젝트 접근 방향
> ### **기업을 위한 3Step + 1 마케팅 전략 제안**

**Step 1 - 신규고객 유치를 위한 전략**
 : 베스트 브랜드 및 상품 분석을 통한 접근
 
**Step 2 - 잠수고객을 구매고객으로 연결하기 위한 전략**
 : 고객 전환기간(가입일과 구매일간의 차이)에 따른 고객 분류 접근
 
**Step 3 - 우량고객 확보를 위한 전략**
 : 1회 구매수량에 따른 고객 분류 접근

**Jumping Step - 기업의 비즈니스 모델 스터디를 통한 전사적 경영 전략 제안**

---
## 2.공유 주차장 앱 이용자 분석
분석목표 : 이용자 별 결제 이력 분석을 통한 마케팅 포인트 도출
> [분석 최종 코드](https://github.com/Lucia-KIM/project/blob/main/%EA%B3%B5%EC%9C%A0%EC%A3%BC%EC%B0%A8%EC%9E%A5%20%EA%B8%B0%EC%97%85%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/Final_code_Marketing.ipynb) / [분석 결과 Insight & Action Plan](https://github.com/Lucia-KIM/project/blob/main/%EA%B3%B5%EC%9C%A0%EC%A3%BC%EC%B0%A8%EC%9E%A5%20%EA%B8%B0%EC%97%85%20%EB%8D%B0%EC%9D%B4%ED%84%B0%20%EB%B6%84%EC%84%9D/Data%20Analysis%20Insight_Marketing_1.pdf)

#### 1)데이터정보
- 데이터 수 : 약 879천여 건의 결제 데이터
- 기간 : 2020.01.01 ~ 2020.12-31
- 유저 가입정보 : id, 가입일
- 소비 행동 정보: 상품id, 점포 주소, 결제일, 결제건수

#### 2)분석 접근 방법
1. Cohort 분석을 통한 Insight 및 Action Plan 제시
 - 유저의 첫번째 사용일을 토대로 코호트 그룹 설정
 - 코호트 그룹과 주문 기간으로 집계

2. RFM Score Analysis
 - Monetary 포인트 생성을 위해 가격 데이터 별도 수집 
 - 15점 만점 기준 각 유저별 점수표 생성

---
## 3. 국민연금DB를 이용해서 유니콘 기업 발굴하기  
프로젝트 목표는 국민연금고지금액, 연매출액, 직원수를 포함한 데이터를 가지고 유니콘기업으로 보이는 기업들을 나름의 방식으로 찾아내는 것!
> [프로젝트 최종 결과물 확인](https://nbviewer.jupyter.org/github/Lucia-KIM/project/blob/main/%E1%84%8B%E1%85%B2%E1%84%82%E1%85%B5%E1%84%8F%E1%85%A9%E1%86%AB%E1%84%80%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%B8%E1%84%8E%E1%85%A1%E1%86%BD%E1%84%80%E1%85%B5/final.ipynb) / [시각화 및 데이터 탐색 과정 코드](https://github.com/Lucia-KIM/project/tree/main/%E1%84%8B%E1%85%B2%E1%84%82%E1%85%B5%E1%84%8F%E1%85%A9%E1%86%AB%E1%84%80%E1%85%B5%E1%84%8B%E1%85%A5%E1%86%B8%E1%84%8E%E1%85%A1%E1%86%BD%E1%84%80%E1%85%B5)

** _본 프로젝트는 원티드 프리온보딩 코스에서 데이터를 제공받았으며, 5명의 팀원들과 함께 작업한 내용입니다._ 

#### 1)데이터정보
- 회사수: 약5,000개
- 연도 : 2015 ~ 2019
- 월별데이터: 직원수, 국민연금보험료(인원 수에 대한 상한선_최대고지금액이 존재함)
- 년단위데이터: 매출액(천 원 단위)
> 유니콘 기업 정의 : 유니콘 기업(Unicorn)은 기업 가치가 10억 달러(=1조 원) 이상이고 창업한 지 10년 이하인 비상장 스타트업 기업을 말한다.

#### 2)프로젝트 접근 방향
1. 구직사이트 CATCH에서 제공하는 국내 [매출액 TOP10 스타트업](https://m.catch.co.kr/Comp/CompThemeRank?TCode=163) 자료를 바탕으로 유니콘 기업에 대한 가설을 정한다. 
2. 데이터 탐색을 통해 변수간 상관관계를 살핀다. 
3. 캐치 데이터를 바탕으로 세운 가설과 비슷한 성향을 보이는 기업을 선택한다. 
4. 실제 유니콘 기업의 정보를 크롤링으로 수집하여 비교한다.
5. 유니콘 기업으로 예상되는 최종 5곳을 선정한다.
---
## 4. 주식가격 분석하기
본 프로젝트는 익명화된 2274 기업의 주가 데이터를 가지고 나름의 방식으로 데이터를 살펴보는 것이다. 
> [프로젝트 결과물 확인!](https://nbviewer.jupyter.org/github/Lucia-KIM/project/blob/main/%E1%84%8C%E1%85%AE%E1%84%80%E1%85%A1%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8/wanted_stock_price_analysis.ipynb)

#### 1) 데이터 정보
- 데이터는 2274 종목의 568일 간(2018-06-01~2020-09-18)의 주가를 포함하고 있다.
- 익명처리된 Symbol로 기업이 구분되며, Symbol은 알파벳 A와 6자리 숫자로 구성, 오름차순으로 정렬되어 있다.

#### 2) 분석 접근 방법
1. 데이터 살펴보기
2. 데이터 분류
 - NaN 값 포함 여부에 따른 분류 : NaN 값이 포함된 데이터만 따로 추출하여 비교한다.
 - 종목별 가격 구간에 따른 분류 : 종목(Symbol)에 따라 데이터 내 가장 최신일자(마지막 일자 : 2020-09-18 )를 기준으로 가격대(고/중/저)를 구분 한다.
  > * 고가 : 100,000 이상인 종목 
  > * 중가 : 10,000 ~ 100,000 사이인 종목    
  > * 저가 : 10,000 미만인 종목
3. 가격대별 샘플 비교 : 
앞서 정의한 (고/중/저)가격대를 기준으로 각 그룹 샘플 10개 종목을 무작위 추출하여 비교한다.
 - 각 샘플별 가격 변동 그래프
 - 각 샘플별 일간 변동률과 주가 변동 그래프

---
## 5. 세종시 인구 및 부동산 데이터 분석
해당 프로젝트는 한국토지주택공사의 도시데이터 분석 대회 COMPAS에서 제공하는 데이터를 활용하여 진행하였다. 
대회의 분석 목적 및 해결과제는 아래와 같다.
> 과제 개요: 본 과제는 과거 *4개년도(2017-2020)의 부동산 실거래정보와 전입‧전출 등 거주인구 정보, 상권정보 및 건물 등 공간데이터를 활용*, 세종시 주택 시장 특성을 직관적으로 이해 할 수 있는 다양한 모델을 도출하는데 목적을 두고 있으며, __세종시 주택 시장 특성을 쉽고 명확히 보이도록 시각화 모델 제시__ 하는 것을 해결과제로 한다. 
> 참고- [대회페이지](https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2102_001)

분석을 위한 데이터 전처리는 파이썬 언어를 사용한 Jupyter notebook환경에서 진행하였으며, 시각화는 Tableau를 사용하였다. 사용한 데이터에 분류와 최종 결과물은 아래 링크 참조
> [최종결과물 확인!](https://public.tableau.com/profile/.13254526#!/vizhome/_1_16165808190810/1_2) / 
> [사용데이터 분류 외](https://www.notion.so/5759c624ee96450084a2eebd2bdc7277) /
> [전처리 소스코드](https://github.com/Lucia-KIM/project/tree/main/%E1%84%89%E1%85%A6%E1%84%8C%E1%85%A9%E1%86%BC%E1%84%89%E1%85%B5_%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8)
> 




---
---


# [예측 모델링 프로젝트]
## 1. 미국 성인 인구조사 소득 예측 대회(캐글)
미국 성인 인구조사 데이터셋을 이용하여 소득이 50K를 넘을지 예측하는 대회이다. [대회정보](https://www.kaggle.com/c/kakr-4th-competition/overview)

** _본 대회는 캐글코리아에서 주최한 데이터분석 캠프에 참여하여 학습한 내용으로 실제 대회는 아니라는 점을 말씀드립니다._

> [최종 제출결과물](https://gist.github.com/Lucia-KIM/b11709f11f15acce8a94eaa3294e1b42)  /
> [EDA 내용](https://gist.github.com/Lucia-KIM/1099f2625f7cd98134fa79693534f2b8)
> > - 사용모델 : XGBoost 
> > - F1 Score : 0.8717

#### 1) 데이터 정보
train/test는 다음의 columns으로 구성되어 있고, train은 예측해야 하는 target 값 컬럼 1개를 더 포함하고 있다. 각 데이터가 의미하는 바는 아래와 같다. 
> - age : 나이
> - workclass : 고용 형태
> - fnlwgt : 사람 대표성을 나타내는 가중치 (final weight의 약자)
> - education : 교육 수준
> - education_num : 교육 수준 수치
> - marital_status: 결혼 상태
> - occupation : 업종
> - relationship : 가족 관계
> - race : 인종
> - sex : 성별
> - capital_gain : 양도 소득
> - capital_loss : 양도 손실
> - hours_per_week : 주당 근무 시간
> - native_country : 국적
>> - income : 수익 (예측해야 하는 값)


#### 2) Feature engineering 주요 방향

1. fnlwgt
> - 변수간의 상관관계를 살펴본결과 fnlwgt 변수의 p-value 값이 0.07로 애매함. 
> - Kmeans기법으로 군집화 시도했으나 유의미한 내용을 찾기 어려웠음. 
> - 최종적으로 fnlwgt는 drop하기로 함. 

2. Race
> - 두 그룹으로 분리
>> * White + Asian-Pac-Islander  == 1
>> * Black + Amer-Indian-Eskimo + Other == 0

3. capital gain/loss
> 구간화, 상계처리
> - (파생변수)capital _gain 0 초과는 1로
> - (파생변수)capital_loss 1700 이상이면 1로 

4. age
> - 구간화(20세부터 5세 단위) 20세 이하, 65세 이상 카테고리화

5. education_num : scale(minmax) 
> - (파생변수)13 이상으로 변수 추가 (hight_education) 1로

6. hours_per_week : scale(minmax) 
> - (파생변수)주당 50시간 이상 근로 여부를 가진 변수 추가 1로

7. marital_status
> - Married-civ-spouse와 나머지는 묶기
>> * 참고] Married-spouse-absent : 배우자가 현지에 없는 경우 / 
>> Married-AF-spouse : 기혼이나 배우자 군인으로 동거하지 않는 경우





