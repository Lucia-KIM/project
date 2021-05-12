# [데이터분석 프로젝트]

## 1. 국민연금DB를 이용해서 유니콘 기업 발굴하기  
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




## 2. 세종시 인구 및 부동산 데이터 분석
해당 프로젝트는 한국토지주택공사의 도시데이터 분석 대회 COMPAS에서 제공하는 데이터를 활용하여 진행하였다. 
대회의 분석 목적 및 해결과제는 아래와 같다.
> 과제 개요: 본 과제는 과거 *4개년도(2017-2020)의 부동산 실거래정보와 전입‧전출 등 거주인구 정보, 상권정보 및 건물 등 공간데이터를 활용*, 세종시 주택 시장 특성을 직관적으로 이해 할 수 있는 다양한 모델을 도출하는데 목적을 두고 있으며, __세종시 주택 시장 특성을 쉽고 명확히 보이도록 시각화 모델 제시__ 하는 것을 해결과제로 한다. 
> 참고- [대회페이지](https://compas.lh.or.kr/subj/past/info?subjNo=SBJ_2102_001)

분석을 위한 데이터 전처리는 파이썬 언어를 사용한 Jupyter notebook환경에서 진행하였으며, 시각화는 Tableau를 사용하였다. 사용한 데이터에 분류와 최종 결과물은 아래 링크 참조
> [최종결과물 확인!](https://public.tableau.com/profile/.13254526#!/vizhome/_1_16165808190810/1_2) / 
> [사용데이터 분류 외](https://www.notion.so/5759c624ee96450084a2eebd2bdc7277) /
> [전처리 소스코드](https://github.com/Lucia-KIM/project/tree/main/%E1%84%89%E1%85%A6%E1%84%8C%E1%85%A9%E1%86%BC%E1%84%89%E1%85%B5_%E1%84%87%E1%85%AE%E1%86%AB%E1%84%89%E1%85%A5%E1%86%A8)
> 







# [예측 모델링 프로젝트]

