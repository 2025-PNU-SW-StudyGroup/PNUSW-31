현재 스터디 진행은 별도의 organization에서 진행 중입니다.  
아래 링크에 방문하시면 스터디에서 진행중인 스터디, 프로젝트 진행 내역을 확인하실 수 있습니다.  
https://github.com/GREEN-in-pnu

---

# PNU SW학습공동체 최종(중간)보고서

## 1. 프로젝트 소개

### 가. 배경 및 필요성

부산시는 민선 8기 도시 비전으로 "그린 스마트 도시"를 제시하며, 그 핵심 전략 중 하나로 저탄소 그린도시 조성을 적극적으로 추진하고 있다. 실제로 대중교통 인프라 확충, 보행 친화 도시계획 등 도보 및 대중교통 중심의 교통 체계 개선은 꾸준히 진전되고 있으며, 이는 일상생활 영역에서의 온실가스 배출 저감 및 에너지 효율 향상에 긍정적인 영향을 주고 있다.

하지만 관광 측면에서는 여전히 친환경 관광을 유도할 수 있는 데이터 기반 시스템이 부족한 실정이다. 특히 부산과 같은 인기 관광도시에서는 특정 지역에 관광객이 집중되는 오버투어리즘(overtourism) 문제가 심화되고 있는데, 이는 단순한 혼잡을 넘어서 자연환경의 훼손, 문화 자원의 소모, 지역 주민과의 갈등 등 여러 문제를 야기한다. 예를 들어, 좁은 골목이나 해안 산책로에 대량의 관광객이 몰리면서 쓰레기 증가, 소음 공해, 생태계 교란 등이 발생하고, 이는 해당 지역의 지속 가능한 관리와 보호를 어렵게 만든다.

이러한 상황은 결국 관광의 지속가능성을 위협하며, 동시에 지역 주민들의 삶의 질을 저하시켜 관광지에 대한 반감과 사회적 마찰로 이어질 수 있다. 따라서 오버투어리즘 문제를 해결하는 것은 단지 환경 보전을 위한 조치일 뿐 아니라, 지역 사회와의 조화로운 관광 생태계를 구축하기 위한 핵심 과제이기도 하다.

이와 같은 맥락에서 친환경 관광 설계는 단순히 탄소배출을 줄이는 기술적 접근을 넘어, 관광 흐름을 분산시키고, 덜 알려진 지역으로의 유입을 유도하여 지역 간 균형 있는 개발을 도모하는 방향으로 발전해야 한다. 이는 환경 보전과 동시에 지역경제 활성화, 사회적 수용성 확보라는 다층적인 효과를 기대할 수 있으며, 지속가능한 도시 관광 모델을 실현하는 중요한 방법론이 될 수 있다.

### 나. 개발 목표 및 주요 내용

본 프로젝트는 지역민들 사이에서 입소문이 나 있는 숨겨진 명소, 일명 ‘몰방곳곳’(몰래 방문하는 곳곳)을 발굴하고, 기존의 대중적 관광 명소와 연계하여 친환경성과 지역 균형을 동시에 고려한 관광 코스를 추천하는 것을 목표로 한다. 

이를 위해 아래와 같은 주요 내용을 포함한다.

- 관광지, 버스정류장, 지하철역 등의 위치 데이터를 지도에 시각화하고, 이 데이터를 바탕으로 다양한 관광 경로를 생성한다.

- 생성된 경로에 대해 이동 수단별 탄소 배출량을 산출하고, 관광 중 발생하는 식음 및 숙박 활동에 대한 감점 또는 가점 요소를 반영하여 종합적인 친환경 점수를 계산한다.

- 이 점수를 기준으로 친환경성이 높은 상위 N개의 관광 코스를 추천하며, 각 코스의 탄소 절감 효과도 수치화 및 시각화하여 사용자에게 직관적으로 전달한다.

이를 통해 탄소 배출을 줄이면서도 다채롭고 의미 있는 관광 경험을 제공하고자 한다.

### 다. 사회적 가치의 도입 계획

이 프로젝트는 단순히 관광 경로를 제시하는 것을 넘어, 모든 세대의 시민과 관광객이 친환경적인 선택을 자연스럽게 실천할 수 있도록 유도하는 공공적 가치를 지향한다. 특히 환경 문제에 대한 민감도와 실천 의지가 높은 MZ세대 또한 타깃으로 삼아, 탄소 감축, 지속 가능한 소비, 지역 균형 발전에 대한 긍정적인 인식을 강화하고자 한다.

나아가, 전 세대를 대상으로도 숨은 명소의 재조명과 분산된 관광 유도, 그리고 친환경 점수를 반영한 경로 추천을 통해 혼잡 지역의 부담을 완화하고 지역 내 다양한 장소로의 이동을 촉진함으로써, 관광 수요의 공간적 분산을 실현할 수 있다. 이를 통해 이동 수단, 식음·숙박 활동 등의 친환경 요소를 정량화한 점수 체계를 기반으로 사용자에게 직관적인 선택지를 제공하며, 지역 경제 활성화와 환경 보호라는 두 가지 사회적 목표를 동시에 달성하는 것이 본 프로젝트의 핵심적인 사회적 가치이다.



## 2. 상세 설계

### 가. 수행 과정

본 프로젝트는 **데이터 수집 → 경로 생성 → 친환경 점수 산정 → 코스 추천**의 흐름으로 구성된다. 각 단계의 세부 내용은 다음과 같다.

#### 1) 관광경로 생성

**(1) 관광지 및 교통 인프라 시각화**
- 관광지, 버스 정류장, 지하철역의 위치 데이터를 지도 위에 시각화
- 지도 시각화 도구: `Folium`, `Plotly`, `Geopandas` 등 활용

**(2) 관광 경로 생성**
- 관광지 간 거리 기반으로 **최소 거리** 또는 **접근성 최적화 알고리즘**을 적용하여 다양한 경로 생성
- `NetworkX` 기반 그래프 알고리즘을 사용하여 경로 내 노드(장소) 간 이동 거리, 시간, 접근성을 평가
- 일정 시간(예: 반나절, 하루)에 맞는 **경로 시나리오(3~5개 지점 연결)** 구성

#### 2) 친환경 점수 산정

**(1) 이동 수단별 탄소배출량 계산**
- 도보, 지하철, 버스 등 이동 수단별 평균 탄소배출 계수를 반영하여 경로 전체의 탄소배출량 산정

**(2) 식음/숙박 활동의 감점/가점 처리**
- 친환경 인증(로컬푸드, 비건 옵션, 제로웨이스트 등)을 받은 식당/숙소 여부에 따라 가중치 부여
- 정보 부족 시 평균 감점 요인 반영 또는 추정치 활용

**(3) 종합 친환경 점수 계산**
- `이동수단 탄소배출 + 소비활동 탄소 영향`을 점수화하여 **100점 만점 기준 친환경 점수**로 환산

#### 3) 경로 추천 및 시각화

- 산출된 경로의 친환경 점수를 **내림차순 정렬**
- **상위 N개 코스**를 추천
- 추천 코스는 **직관적인 UI**를 통해 지도 상에 시각화되어 사용자에게 제공
  - 이동 경로, 소요 시간, 탄소절감 효과 등을 시각적으로 표현

---

### 나. 흐름도

```text
[관광지, 교통 데이터 수집]
        ↓
[그래프 기반 연결 (NetworkX)]
        ↓
[거리 및 이동 수단 계산]
        ↓
[탄소 배출량 계산]
        ↓
[친환경 점수 산출]
        ↓
[상위 경로 추천 + 지도 시각화]
```






## 3. 개발결과

### 1. 데이터 소개
본 프로젝트는 부산 지역 내 숨은 명소(‘몰방곳곳’)를 발굴하고, 이를 기존 관광지와 연계하여 친환경 관광 경로를 설계하는 것을 목표로 한다. 이를 위해 다음과 같은 다양한 형태의 공공데이터를 수집하였다. (출처-부산 빅데이터 혁신센터)

사용된 주요 데이터셋은 아래와 같다:

관광명소_좌표: 각 관광명소의 코드와 위도·경도 정보를 포함

관광지_연령별_방문객: 관광명소별로 연령대(10대 단위)별 방문객 수

관광지_외국인_방문객: 국가별 외국인 방문객 수

관광지_유입지별_방문객: 지역별 내국인(타 시도) 방문객 수

관광지_총_방문객: 전체 방문객 수

버스정류장_좌표 / 지하철역_좌표: 대중교통 인프라 위치

집계구_좌표: 공간 분석을 위한 집계구 단위 좌표 정보

이 데이터들은 관광객 분포 분석, 로컬 관광지 후보 발굴, 대중교통 접근성 평가, 그리고 최종적으로 친환경 점수 기반 경로 추천 알고리즘 개발에 활용된다.

### 2. 데이터 문제점 및 처리방안
현재 수집된 관광 통계 데이터는 구조적으로 “외부 유입” 중심으로 설계되어 있어, 현지 방문객(부산 시민)의 행동 데이터가 포함되어 있지 않다는 한계가 있다. 구체적으로는 다음과 같다

총 방문객 수는 외국인 방문객과 유입지별 내국인 방문객의 합과 같으며,

부산 시민은 외국인도 아니고 타 지역 거주자도 아니므로, 해당 집계에서 완전히 누락되어 있다.

따라서 실제 지역민이 주로 찾는 장소, 즉 우리가 정의하고자 하는 ‘몰방곳곳’을 직접적으로 파악하기 어렵다.

(1) 기존 데이터 내에서 대체 기준 정의
직접적인 부산 시민 데이터가 없는 상황에서는, “로컬 중심 공간일 가능성”이 높은 장소를 간접적 지표로 추정하는 전략이 필요하다. 이를 위해 다음과 같은 기준을 활용한다.

외국인 비율이 낮고, 총 방문객 수가 적은 장소
→ 외부 관광객의 유입이 적은 곳은 상대적으로 지역민 중심 이용 공간일 가능성이 높다.

20~40대 방문 비율이 높은 장소
→ MZ세대가 주로 방문하는 트렌디하거나 활동적인 장소일 수 있으며, 로컬의 최신 문화/취향 반영 가능

대중교통 접근성이 높은 장소
→ 버스 정류장 및 지하철역에서 500m 이내에 위치한 장소는 일상 속 접근 가능성이 높다.

위 기준을 정량화하여, 다음과 같은 점수 기반 필터링 로직을 구성할 수 있다:
```python
score = (
    (2030비율) * 0.4 +
    (1 - 외국인방문비율) * 0.3 +
    (1 - 총방문객정규화) * 0.2 +
    (지하철/버스 근접도) * 0.1
)
```
해당 스코어를 기준으로 일정 기준 이상인 관광지를 ‘숨은 명소’ 후보로 간주하고, 이후 경로 연결 및 친환경 점수 계산에 포함한다.

(2) 부산 시민 소비 데이터 확보 시도
위의 간접적 기준만으로는 한계가 있기 때문에, 부산 시민의 실질적 이동 및 소비 데이터 확보를 위한 시도도 병행된다. 구체적으로는 다음과 같다:

신한카드 소비 데이터: 부산 거주자의 카드 소비 기록을 분석하여, 지역민이 실제로 방문한 장소를 추정

데이터 기간: 2019년 1월 ~ 2023년 12월

행정기관코드 매칭: 통계청의 2023년 부산광역시 행정기관 행정구역 매칭 테이블과 카드사 데이터의 행정기관코드를 비교하여 지역 일치 여부 확인

집계구 기반 보정: 카드 데이터의 공간 단위를 집계구 코드로 변환할 때, 코드의 앞 10자리와 행정기관코드를 매칭하여 정확도 향상

이 과정을 통해 실제 지역민 소비 기반의 로컬 명소 데이터셋 확보가 가능하며, ‘몰방곳곳’ 정의의 타당성과 신뢰도를 보완할 수 있다.  

### 3. 최적 경로 탐색 알고리즘

최적 경로 탐색은 사용자가 설정한 여행 계획에 따라 가장 효율적인 이동 경로를 제시하는 과정이다. 본 프로젝트에서는 부산을 기반으로 도보 및 대중교통을 활용한 친환경 관광을 목표로 하며, 다음과 같은 단계를 통해 경로를 탐색한다.

경로 탐색 과정

```text

[ 1. 여행지 및 숙소 선택 ]
사용자가 방문하고자 하는 주요 관광지와 숙박 위치를 지도 상에서 직접 선택한다.
이는 경로 탐색의 출발점 및 경유지, 도착지를 설정하는 기준이 된다.
        ↓
[ 2. 후보 관광지 자동 추천 및 필터링 ]
사용자가 선택한 장소 외에도, 부산 내 몰방(몰랐던) 명소나 추천 POI(Point of Interest)를 일부 자동 선별하여 경로 탐색 후보지로 추가한다.
이때 사용자 선호도, 이동 거리, 교통 접근성 등을 고려한다.
        ↓
[ 3. 최적 경로 탐색 실행 ]
도보 및 대중교통 이용을 가정해 시간과 공간 효율성을 기준으로 최적 경로를 계산한다.
도보 이동의 경우 거리와 소요 시간을, 대중교통은 환승 횟수, 배차 시간, 도보 연계 등을 함께 고려한다.
이와 같은 상황에 적합한 경로 탐색 알고리즘을 다음 절에 설명한다.

```


---

경로 탐색에 적합한 알고리즘

#### (1) A* 알고리즘 (A-Star Algorithm)

원리: 휴리스틱 함수와 실제 비용을 조합하여 최적 경로를 계산한다. 시작 지점에서 목표 지점까지의 경로 중, 예상 총 비용(f(n) = g(n) + h(n))이 가장 낮은 노드를 우선 탐색한다.

대표적 사용처: 내비게이션 시스템, 게임 AI, 지도 기반 경로 탐색 등

장점: 정확성과 속도 모두 우수하며, 휴리스틱 함수 설계를 통해 효율을 크게 높일 수 있다. 도보 + 대중교통처럼 혼합된 경로에서 사용자 경험을 최적화할 수 있음.


#### (2) 다익스트라 알고리즘

원리: 하나의 시작점에서 모든 정점까지의 최단 경로를 구하는 알고리즘. 각 노드까지의 거리를 반복적으로 갱신하여 최종적으로 가장 짧은 경로를 구한다.

대표적 사용처: 교통망 분석, 통신 네트워크, 도시 내 최단 거리 계산

장점: 정확도가 매우 높고, 모든 경로에서 최단 거리를 보장한다. 휴리스틱 없이도 안정적인 결과를 제공하며, A*와 달리 모든 경로의 최소 비용을 알고 싶을 때 유용하다.


#### (3) 벨만-포드 알고리즘

원리: 음수 가중치가 존재하는 그래프에서도 최단 경로를 구할 수 있는 알고리즘. 각 간선을 반복적으로 업데이트하며 최단 거리를 계산한다.

대표적 사용처: 환승 패널티, 시간 제약 등 복잡한 제약조건이 있는 네트워크 환경

장점: 음수 가중치를 허용하고, 특정 조건(예: 혼잡 시간대에 따른 가중치 변화 등) 하에서도 안정적인 경로 탐색이 가능하다. 하지만 다익스트라보다 계산 속도는 느리다.


#### (4) DWA (Dynamic Window Approach)

원리: 로봇 또는 자율주행 기기가 주어진 물리적 제약(속도, 가속도 등)을 고려하여 실시간으로 충돌 없이 이동 가능한 경로를 탐색하는 알고리즘.

대표적 사용처: 자율주행 차량, 로봇 내비게이션 등 실시간 이동 경로 탐색

장점: 실시간 환경에 적합하며, 예측 기반 경로 계획이 가능하다. 복잡한 도시 구조나 보행자·장애물이 많은 환경에서 안전성과 유연성을 보장한다. 향후 로봇 가이드, 보행자 시뮬레이션 등에 응용 가능성이 있음.



---

관련 참고 논문 예시

「다중 목적을 고려한 최적 경로 탐색 알고리즘」

관광지 선호도, 시간, 비용, 환경 영향 등을 동시에 고려한 멀티옵티멀 경로 탐색을 제안한다.


「연비 최적 경로 결정 알고리즘」

차량의 에너지 효율성을 기준으로 최적 경로를 탐색하는 알고리즘이며, 이는 친환경 목적과도 일치한다.

본 프로젝트에서도 ‘탄소 절감 우선 경로’를 설정할 때 활용 가능성이 있다.




---

### 4. 친환경 관광 점수 산출

본 프로젝트에서는 단순한 관광지 추천이 아니라, 환경을 고려한 지속가능한 여행을 유도하고자 한다. 이를 위해 사용자 경로 및 활동 유형에 따라 친환경 점수를 산출하며, 점수는 다음과 같은 요소에 기반한다.

① 식음활동에 따른 탄소 점수

감점 요소:

고탄소 식품(예: 육류 위주의 패스트푸드, 수입산 메뉴 등)을 주로 선택할 경우 감점

일회용품 사용이 많은 매장 이용 시 추가 감점


가점 요소:

지역 친환경 식당, 비건·로컬푸드 매장 이용 시 가점

다회용기 사용, 음식물 쓰레기 줄이기 실천 매장 선택 시 가점



② 숙소 이용에 따른 탄소 점수

감점 요소:

대형 체인형 숙소, 에너지 낭비가 많은 고급 시설 위주 선택 시 감점


가점 요소:

탄소중립 숙소 인증, 지역 자원순환형 게스트하우스, 대중교통 접근성이 좋은 숙소는 가점



③ 종합 친환경 점수 산출 방식

식음활동 점수(40%) + 숙소 점수(40%) + 이동 경로의 친환경성(20%)을 종합하여 총 점수를 계산

이동 경로 점수에는 도보·대중교통 이용 비율이 높을수록 가중치를 높인다.


## 4. 설치 및 사용방법


## 5. 소개 영상 또는 시연 영상


## 6. 팀 소개

본 팀 그린(GREEN)은 의생명융합공학과 소속 학생들로 구성된 팀으로, 지속 가능한 도시 관광 모델을 제안하고자 모인 친환경 데이터 분석 프로젝트 팀이다. ‘그린’이라는 팀명에는 환경 보호, 균형잡힌 개발, 그리고 녹색 미래를 이끄는 기술적인 실천이라는 가치를 담고 있으며, 이를 실제 데이터 기반의 문제 해결로 구현하는 것을 목표로 활동하고 있다. 

### 구성원 역할

- **김세이(팀장)** 데이터 사이언스 전공

팀장을 맡아 프로젝트의 기획 전반과 친환경 점수 산정 기준을 설계하고, 팀의 핵심 논리를 정립하였다. 주요 데이터를 수집하며 프로젝트 구조를 설계하는 데 주도적으로 참여하였고, 지도 기반 데이터를 다루기 위한 API, QGIS, Python 기반의 Folium 등의 활용법을 학습하며 실제 분석에 적용하고자 노력하였다.

- **명준휘** 데이터 사이언스 전공

친환경 점수 산정 기준에 대해 깊이 고민하였으며, 프로젝트에 필요한 관광지, 교통 인프라 등의 주요 데이터를 수집하였습니다. 데이터 기반 경로 추천의 논리를 함께 구상하고 실현 가능성에 대해 지속적으로 논의하였다.

- **정유진** 전공 미정

친환경 점수와 관련된 다양한 사례 및 평가 기준을 조사하여 프로젝트의 기준 정립에 기여하였다. 데이터 수집의 효율성을 높이기 위해 웹 크롤링 기술을 학습 중이며, 실제 프로젝트에 이를 적용하고자 하는 적극적인 자세를 보여주고 있다.

- **황지순** 전공 미정

프로젝트 관련 문헌 및 유사 사례에 대한 자료조사를 담당하였다. 또한 지도 기반 데이터 분석에 필요한 API, QGIS 활용법을 학습 중이며, 수집된 위치 데이터를 효과적으로 시각화하고 분석하기 위한 기반을 다지고 있다.

‘그린’ 팀은 단순히 정해진 역할을 수행하는 데 그치지 않고, 모든 구성원이 데이터 수집, 분석, 시각화, 기준 설계까지 전 과정에 걸쳐 서로 협력하며 능동적으로 참여하고 있다. 무엇보다 각자 부족한 부분은 함께 학습하고 보완해가며 현실 적용 가능한 데이터사이언스 프로젝트로 발전시켜 나가고 있다는 점에서 큰 의미가 있다.



## 7. 참여후기
김세이:
스터디 활동을 하면서 연속적으로 프로젝트 작업이 이루어지는 것이 얼마나 중요한 일인지 깨닫게 되었다. 기존에 학부 수업에서 진행했던 프로젝트는 대부분 단기간에 완료되는 경우가 많았기 때문에, 다루는 범위가 비교적 제한적이었다. 그래서 일주일에 한 번 대면 모임을 갖고 팀원들이 각자 내용을 조사해와 프로젝트를 이어가는 방식에도 큰 어려움이 없었다.
하지만 이번 학습 공동체 프로젝트는 상황이 달랐다. 데이터 반출과 가공 같은 초기 준비 단계부터 우리가 직접 수행해야 했고, ‘친환경 관광 점수’처럼 기존에 존재하지 않는 창의적인 요소를 도입하다 보니, 논의해야 할 내용도 많고 조원들 각자의 의견을 조율하는 과정도 결코 간단하지 않았다. 무엇보다 이전 논의 내용을 체계적으로 정리하고 그에 대한 후속 작업이 이뤄지지 않으면, 다음 단계를 어떻게 진행해야 할지 막막해지는 순간이 반복되었다.
이런 경험을 통해 회의 내용을 보다 구체적으로 기록하고, 특히 각 조원들의 생각을 정리해두는 것이 얼마나 중요한지 절실히 느꼈다. 또한 우리가 프로젝트를 어디까지 공통적으로 이해하고 있는지를 정기적으로 점검하는 과정도 필수적임을 깨달았다. 결국 프로젝트의 성패는 단순히 작업을 나누는 데 있는 것이 아니라, 서로의 생각을 공유하고 그 흐름을 끊기지 않게 유지하는 ‘의사소통’에 달려 있다는 사실을 깊이 체감할 수 있었다.


명준휘:
빅데이터 활용 대회를 준비하며 여러가지를 배우고 이를 통해 많은 것을 느끼고 있지만, 지역성과 지속가능성을 함께 고려한 관광 데이터를 다루며, 사회적 가치를 반영한 분석의 중요성을 체감할 수 있었다. 단순한 수치가 아닌 사람과 도시의 맥락을 읽는 시도가 흥미로웠고, 데이터 활용의 확장 가능성도 엿볼 수 있었다.
실제 정책이나 서비스 설계와 연결될 수 있는 프로젝트이기에 앞으로 더 꼼꼼히 분석하여 완성도 있게 마무리하고 싶다.

정유진:
이번 활동에서 공공데이터를 활용해 지역 관광 문제를 친환경 관점에서 해결하고자 고민했다. 데이터셋의 한계로 인해 주제가 살짝 바뀌긴 했지만, 우리가 가지고 있는 데이터셋의 성격에 맞는 주제가 된것 같아 좋았다. 매주 팀원들과 함께 문제를 하나씩 해결 해나가는 과정이 의미있는 것 같다.

황지순:
 빅데이터 활용 대회는 친환경 관광 코스 추천이라는 궁극적인 목표를 달성하기 위해 팀원들과 함께 학습하고 협업하는 소중한 경험었다. 
 혼자 공부하는 데이터 분석이라는 교재를 통해 데이터 분석에 대한 기초를 함께 학습하고, 이후로는 지속적인 티미팅을 통해 구체적인 계획을 세웠다. 특히, 친환경 점수를 어떻게 정의하고 도출할지, 어떤 데이터 셋을 사용할지, 지도 데이터를 어떻게 활용할지와 같은 문제들을 팀원들과 함께 고민하는 과정에서 개인적으로는 생각하지 못했던 다양한 아이디어가 나왔고, 이를 통해 협업의 중요성을 체감할 수 있었다.       
 아직 해결해야 할 과제들이 남아 있지만, 끝까지 최선을 다해 좋은 결과물을 만들어 가고자 한다. 


## 8. 참고문헌 및 출처

* 부산 빅데이터 혁신센터, IPCC, 식당 탄소발출 계산 해외 데이터 기본
* 신한카드 카드소비 패턴 데이터 (201901\~202312)
* 통계청 행정구역 메타 데이터 (집계구, 행정군산역 및 범위 연계)
