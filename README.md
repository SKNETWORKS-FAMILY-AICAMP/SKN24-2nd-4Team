# 🔖2nd_PROJECT_4TEAM

# **프로젝트 명 : 패션 산업 고객 이탈 예측 모델 개발** 📚

## 💡**팀 스티치(Stitch)**
*“고객과 브랜드를 다시 잇는 데이터 한 땀.”*


---

## 🌟 팀원 소개

| 이름 | 깃허브 계정 |
| :--- | :--- |
| **조아름** |[areum117](https://github.com/areum117) |
| **정재훈** |[JeaHoon-J](https://github.com/JeaHoon-J) |
| **정석원** |[JeongSW123](https://github.com/JeongSW123) |
| **김민준** |[miin-jun](https://github.com/miin-jun) |
| **정준하** |[junhaj27](https://github.com/junhaj27) |

---

## 1. 프로젝트 개요

### 1.1 프로젝트 주제 선정 배경


<img src='./img/news1.png' width='600'> <br>
<img src='./img//news3.png' width='600'>

#### 1. 패션 산업의 구조적 침체와 고객 이탈 가속화

  경기 침체 속에 패션업계엔 먹구름이 드리워졌다. 소비 쿠폰 효과에 일시적으로 소비 심리가 반등했지만, 경기 침체의 원인이 해소되지 않은 만큼 매출 감소세는 이어지고 있습니다. 

  코로나 이후 일시적인 회복에도 불구하고 국내 패션 소비 시장은 2019년 이전 수준을 간신히 회복한 뒤 정체 국면에 머물러 있으며, 소비자는 더 이상 감성적 마케팅보다 **‘지금 나에게 얼마나 유용한가’** 를 따져 지갑을 여는 양상을 보이고 있습니다.

  중저가·초저가 온라인 플랫폼으로의 이동이 가속화되면서 글로벌 SPA 브랜드 H&M 역시 예외가 아닙니다. 한국 1호 매장인 명동점 폐점을 포함해 오프라인 매장 구조조정을 단행했습니다. 이는 단순 매출 감소를 넘어 수익성 악화, 재고 부담 증가, 기존 고객 기반의 이탈 가능성 등 구조적인 문제로 이어지고 있습니다.

<br>
<img src='./img//news2.png' width='600'>

<img src='./img//news4.png' width='600'>

#### 2. 데이터 기반 고객 이탈 예측의 필요성

  시장을 잘 안다는 것은 시장을 구성하고 있는 핵심 데이터를 잘 알고 잘 이해하고 있다는 것입니다. 
  좋은 전략, 경쟁력 있는 전략은 직관이나 경험에 의존하기보다, 객관적이고 치밀한 핵심 요소의 데이터 분석과 확률 높은 예측을 전제로 합니다.
  
  그러나, 현재 국내 패션 산업은 디지털 기술 및 데이터 활용 능력이 낮아, 글로벌 주요 브랜드에 비해 CRM(고객 관계 관리) 시스템의 정교함, 고객 데이터 분석 체계, 데이터 기반 의사결정 구조가 부족하다는 지적이 이어지고 있습니다.

  이러한 상황에서 고객 데이터를 실시간으로 통합 및 분석을 하지 못할 경우, 빠르게 변화하는 소비 트렌드와 경쟁 환경에 능동적으로 대응하기 어렵습니다.
  특히 고객 이탈을 사전에 예측하지 못하면, 마케팅 비용 증가와 수익성 악화로 이어질 가능성이 큽니다.

  따라서 데이터 기반 고객 이탈 예측은 선택이 아닌, 지속 가능한 성장을 위한 필수 전략 요소입니다.

---

### 1.2 프로젝트 주제 필요성

- 따라서 본 프로젝트는
    - 패션 산업 환경에서 발생하는 고객 이탈 정의
    - 고객 구매 데이터를 기반으로 이탈 분류 
    - 이탈 예측 모델을 통해 선제적 CRM 전략 수립 가능성 탐색
  
  이를 목적으로 하여 단순히 이탈 여부를 예측하는 데 그치지 않고, 이탈 고객의 패턴과 원인을 설명하는 데 초점을 둡니다.
  
  그리고 이를 통해 신규 고객과 기존 고객의 이탈 원인을 구조적으로 이해하고, 궁극적으로 패션 산업의 데이터 기반 성장 전략 수립에 기여하고자 합니다.

---

## 2.  **기술 스택** 🛠️

| **분류**| **기술/도구** |
|---|---|
| **언어** | ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python&logoColor=yellow)     |
| **라이브러리** | ![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy) ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas) ![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib) <br> ![Seaborn](https://img.shields.io/badge/seaborn-0C5A5A?style=for-the-badge&logo=Seaborn) ![scikitlearn](https://img.shields.io/badge/scikitlearn-green?style=for-the-badge&logo=scikitlearnlogo=xgboost) ![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-FF6B6B?style=for-the-badge) ![Joblib](https://img.shields.io/badge/Joblib-2E8B57?style=for-the-badge)
| **협업 툴** | ![GitHub](https://img.shields.io/badge/github-121011?style=for-the-badge&logo=github) ![Git](https://img.shields.io/badge/git-F05033?style=for-the-badge&logo=git&logoColor=white) ![Notion](https://img.shields.io/badge/notion-000000?style=for-the-badge&logo=notion) ![Discord](https://img.shields.io/badge/discord-5865F2?style=for-the-badge&logo=discord&logoColor=white)|

---

## 3. WBS 📋
<img src='./img/wbs.png'>

### 요구사항 명세서
<img src='./img/requirements.png'>

---

## 4. 데이터 선택 및 특징 🗃️

### 4.1 데이터 선택

- **H&M Personalized Fashion Recommendations**
    - 2018년 9월부터 2020년 9월까지 H&M 기업 온라인& 오프라인 매장 데이터
    - column : 35개
    - row : 약 3100만 개

<**출처**>
https://www.kaggle.com/competitions/h-and-m-personalized-fashion-recommendations/data

---

### 4.2 이탈 정의

### 4.2.1 계약 고객과 비계약 고객
- **계약 고객** : 서비스 이용을 위해 명시적 계약을 체결한 고객
- **비계약 고객** : 상품을 구매하기로 결정하면, 계약의 필요성 없이 최소한의 등록만으로 거래를 하는 고객

    | 구분       | 계약 설정     | 비계약 설정          |
    | -------- | --------- | --------------- |
    | 계약 존재 여부 | 있음        | 없음              |
    | 이탈 기준    | 계약 해지     | 일정 기간 비활성       |
    | 정의 난이도   | 비교적 명확    | 도메인별 정의 필요      |
    | 주요 변수    | 해지일, 약정기간 | 마지막 활동일, 재구매 주기 |
    | 적용 산업 예시|통신, 은행, 보험 등| 이커머스, 온라인 게임 등


---

## 5. 데이터 전처리 및 EDA

### 5.1 데이터 병합 (Data Integration)

- `articles.csv`

    <img src='./img/articles.png' width='400'>


<br>

- `customers.csv`

    | 컬럼명                          | 의미(정확한 정의)            | 값 형태         |
    | ----------------------------  | --------------------- | ------------ |
    | customer_id                     | 고객 고유 식별자             | string       |
    | FN                              | 패션 뉴스/마케팅 메시지 수신 여부   | 1 / NaN      |
    | Active                          | 온라인 계정 및 커뮤니케이션 활성 상태 | 1 / NaN      |
    | club_member_status              | H&M 멤버십 상태            | categorical  |
    | fashion_news_frequency          | 뉴스레터 수신 빈도            | categorical  |
    | age                             | 고객 나이                 | numeric      |
    | age_cut                         | 나이를 구간화한 범주           | categorical  |
    | postal_code                     | 익명화된 지역 식별 코드(해시)     | string(hash) |

<br>

- `transactions_train.csv`

    | 컬럼명                          | 구분     | 의미(정확한 정의)            | 값 형태         |
    | ---------------------------- | ------ | --------------------- | ------------ |
    | customer_id                     | 고객 고유 식별자             | string       |
    | t_dat                           | 구매 발생 날짜              | date         |
    | article_id                      | 구매된 상품의 고유 ID         | integer      |
    | price                           | 구매 가격                 | float        |
    | sales_channel_id                | 구매 채널 구분              | integer      |


<br>

#### **병합 데이터**

| 단계 | 대상 데이터 | 조인 키 | 방법 | 목적 |
| --- | --- | --- | --- | --- |
| **1차 병합** | `customers` + `transactions` | `customer_id` | Inner Join | 고객별 구매 이력 결합 |
| **2차 병합** | `병합본` + `articles` | `article_id` | Inner Join | 구매한 상품 정보 결합 |

### 5.2 결측치 처리 및 데이터 정제

| 컬럼명 | 처리 방법 | 상세 내용 |
| --- | --- | --- |
| **FN** | `fillna(0)` | 패션 뉴스레터 수신 여부 미기입 시 '수신 안 함' 처리 |
| **Active** | `fillna(0)` | 온라인 마케팅 활성화 여부 미기입 시 '비활성' 처리 |
| **club_member_status** | `dropna` | 'nan' 문자열 변환 후 결측치(0.21%) 제거 |
| **fashion_news_frequency** | `fillna('UNKNOWN')` | 뉴스레터 수신 빈도 정보 없음 고객 분류 |
| **age** | `pd.cut` | 10대~60대 이상 구간화, 결측치는 `UNKNOWN` 처리 |

### 🔹주요 변수
1) **이탈 파생 변수**
- 고객별 **상대적 구매 주기**를 고려한 **API(Average Purchase Interval)** 방식을 채택

    - `API(AveragePurchasing Interval)` : 개인 고객별 구매주기의 평균
    - `LPL(LastPurchasing Lapse)` : 최종구매경과 

    - <img src='./img//api_img.png' width='400'>
    - $$LPL = \text{Dataset Max Date} - \text{Customer's Last Purchase Date}$$
    - $$Churn =\begin{cases}1 & \text{if } API < LPL \\0 & \text{otherwise}\end{cases}$$

    | 지표명 | 산출 로직 | 분석적 의미 |
    | --- | --- | --- |
    | **API ratio** | `gap 합계` / (`거래일수` - 1) | 고객별 **평균 구매 주기** (구매 간격의 평균) |
    | **LPL** | `last_date` - `최종 구매 시점` | 고객별 최종 구매 시점부터 데이터의 마지막 날짜까지 경과한 기간|
    | **이탈여부(churn)** | `API ratio < LPL` | LPL 값이 API 값보다 큰 경우 이탈로 정의 |
    | **신규고객이탈** | `구매 횟수 == 1` | 첫 구매 이후 추가 구매가 없는 일회성 고객 |
    | **전체고객이탈여부** | `churn + only_first_tran` | 주기적 이탈자와 일회성 고객을 통합한 최종 라벨 |

---

### 5.3 피처 엔지니어링 (Feature Engineering)

### 5.4 최종 데이터 구조 
전처리가 완료된 데이터는 분석 목적에 따라 두 가지 파일로 저장

1.  **`total_churn.csv`**: 전체 고객을 대상으로 한 이탈 예측용 데이터
2.  **`new_churn.csv`**: 신규 가입 고객의 초기 이탈 방지를 위한 예측용 데이터


## 📊 EDA

### 1. 이탈률 분포

<img src='./img/eda1.png'>

- 공통으로 높으면 -> 신규든 기존이든 이탈률이 많이 나오는 상품
- 시간이 지나면서 재구매로 이어지지 못해 이탈이 됐을 가능성을 보여줌
- bag는 신규 고객에서 이탈이 가장 많이 생겼지만 전체 고객으로 봤을 때 이탈순위에서 상대적으로 떨어짐

<br>
<img src='./img/eda_age.png'>
- 10~20대 이탈률이 상대적으로 많이 높음

<br>
<img src='./img/eda_member.png'>
- 비멤버십 고객 이탈률이 매우 높음
- 고객을 멤버십으로 전환시키는 전략이 필요할 것으로 보임

### 2. 상관관계 분석

---



---

## 6. 머신러닝 파이프라인 🔧

### 6.4 모델

#### 6.4.1 Model


## 7. 하이퍼 파라미터 조정 모델 성능 결과 🖨️
---

#### 7.1.1 성능 비교

---

## 8. 인사이트 🔦

### 8.1 이용자 이탈 방지 전략

---

## 9. 한계점 🧩

- 패션 즉 의류업은 개인적인 관점이 들어가며 브랜드별 혹은 트랜드에 민감하다는 특징이 있어서 해당 부분에 대한 전략이나 해결책 제시는 불가능합니다.
- 각 브랜드의 구체적인 손익에 대한 프로모션은 고려가 불가능합니다.(10% 할인을 해도 몇 퍼센트 이상 판매한다면 이득이다 등)
- 또한 설문·리뷰 등 정성 데이터가 부족해, 정량 분석만으로는 고객의 ‘왜 떠나는지(WHY)’를 완전히 설명하기 어렵다는 한계가 있습니다
- 너무 많은 데이터 양 떄문에 메모리 부족으로 
---

## 10. 수행 결과 페이지 📌


### **팀원 한 줄 회고** 🧑‍💻
 
| **이름** | **회고 내용** |
| :---: |---|
| 조아름 | |
| 정재훈 | |
| 정석원 | |
| 김민준 | | 
| 정준하 | |


## 참고 문헌
#### 기사
- https://biz.newdaily.co.kr/site/data/html/2024/05/08/2024050800361.html
- https://v.daum.net/v/ySVjF0rRCF
- https://www.ktnews.com/news/articleView.html?idxno=136611
- https://m.apparelnews.co.kr/news/news_view/?idx=178576%3Fcat%3DCAT180

#### 논문
- https://uark.pressbooks.pub/ampdglobalsourcing/chapter/10-3-the-importance-of-data-analytics-in-modern-fashion-industry
- [비계약 서비스 산업의 효율적인 이탈예측 모형의 개발](https://dspace.hansung.ac.kr/handle/2024.oak/9834)
- [인공지능 기반 고객 이탈 예측 기술 동향 및 발전방향](http://journal.dcs.or.kr/xml/37355/37355.pdf)