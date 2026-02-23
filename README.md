# 🔖2nd_PROJECT_4TEAM

# **프로젝트 명 : 패션 산업 고객 이탈 예측 모델 개발** 📚

## 💡**팀 스티치(Stitch)**
*“고객과 브랜드를 다시 잇는 데이터 한 땀.”*


---

## 🌟 팀원 소개

| 이름 | 역할 | 깃허브 계정 (Link) |
| :---:| :--- | :--- |
| **조아름** |  | [areum117](https://github.com/areum117) |
| **정재훈** |  | [JeaHoon-J](https://github.com/JeaHoon-J) |
| **정석원** |  | [JeongSW123](https://github.com/JeongSW123) |
| **김민준** |  | [miin-jun](https://github.com/miin-jun) |
| **정준하** |  | [junhaj27](https://github.com/junhaj27) |

---

## 1. 프로젝트 개요

### 1.1 프로젝트 주제 선정 배경


<img src='./img/news1.png' width='600'> <br>
<img src='./img//news3.png' width='600'>

  경기 침체 속에 패션업계엔 먹구름이 드리워졌다. 소비 쿠폰 효과에 일시적으로 소비 심리가 반등했지만, 경기 침체의 원인이 해소되지 않은 만큼 매출 감소세는 이어지고 있습니다. 

  코로나 이후 일시적인 회복에도 불구하고 국내 패션 소비 시장은 2019년 이전 수준을 간신히 회복한 뒤 정체 국면에 머물러 있으며, 소비자는 더 이상 감성적 마케팅보다 **‘지금 나에게 얼마나 유용한가’** 를 따져 지갑을 여는 양상을 보이고 있습니다.

  중저가·초저가 온라인 플랫폼으로의 이동이 가속화되면서 글로벌 SPA 브랜드 H&M 역시 예외가 아닙니다. 한국 1호 매장인 명동점 폐점을 포함해 오프라인 매장 구조조정을 단행했습니다. 이는 단순 매출 감소를 넘어 수익성 악화, 재고 부담 증가, 기존 고객 기반의 이탈 가능성 등 구조적인 문제로 이어지고 있습니다.

<br>
<img src='./img//news2.png' width='600'>

<img src='./img//news4.png' width='600'>

  시장을 잘 안다는 것은 시장을 구성하고 있는 핵심 데이터를 잘 알고 잘 이해하고 있다는 것입니다. 
  좋은 전략, 경쟁력 있는 전략은 보다 객관적이고 치밀한 핵심 요소의 데이터 분석과 확률 높은 예측을 전제로 함은 물론입니다.
  
  그러나, 현재 많은 패션 기업들은 "어떤 고객이, 어떤 구매 패턴을 보이다가, 왜 이탈하는가?" 에 대해 충분한 데이터 기반 분석으로 수행하지 못하고 있습니다.

---

### 1.2 프로젝트 주제 필요성

- 따라서 본 프로젝트는
    - 한국 패션 산업 환경에서 발생하는 고객 이탈 정의
    - 데이터 기반으로 이탈 패턴 분석
    - 이탈 예측 모델을 통해 선제적 CRM 전략 수립 가능성 탐색
  
  이를 목적으로 하여 데이터를 통해 신규/전체 고객의 이탈 원인을 설명하고, 더 나아가 전체적인 패션 업계의 성장을 바라본다.

---

## 2.  **기술 스택** 🛠️

| **분류**| **기술/도구** |
|---|---|
| **언어** | ![Python](https://img.shields.io/badge/python-3670A0?style=for-the-badge&logo=python)     |
| **라이브러리** | ![NumPy](https://img.shields.io/badge/numpy-013243?style=for-the-badge&logo=numpy) ![Pandas](https://img.shields.io/badge/pandas-150458?style=for-the-badge&logo=pandas) ![Matplotlib](https://img.shields.io/badge/Matplotlib-ffffff?style=for-the-badge&logo=Matplotlib) <br> ![Seaborn](https://img.shields.io/badge/seaborn-0C5A5A?style=for-the-badge&logo=Seaborn) ![scikitlearn](https://img.shields.io/badge/scikitlearn-green?style=for-the-badge&logo=scikitlearnlogo=xgboost) ![imbalanced-learn](https://img.shields.io/badge/imbalanced--learn-FF6B6B?style=for-the-badge) ![Joblib](https://img.shields.io/badge/Joblib-2E8B57?style=for-the-badge)
| **협업 툴** | ![GitHub](https://img.shields.io/badge/github-121011?style=for-the-badge&logo=github) ![Git](https://img.shields.io/badge/git-F05033?style=for-the-badge&logo=git)|

---

## 3. WBS 📋
<img src='./img/wbs.png'>

---

## 4. 데이터 선택 및 특징 🗃️

### 4.1 데이터 선택

- **H&M Personalized Fashion Recommendations**



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
    - `LPL(Last Purchasing Lapse)` : 최종구매경과

    - <img src='./img//api_img.png' width='400'>
    | 지표명 | 산출 로직 | 분석적 의미 |
    | --- | --- | --- |
    | **API ratio** | `gap 합계` / (`거래일수` - 1) | 고객별 **평균 구매 주기** (구매 간격의 평균) |
    | **이탈여부(churn)** | `API ratio > 90` | 평균 주기가 90일을 초과하여 이탈로 판단되는 고객 |
    | **신규고객이탈** | `구매 횟수 == 1` | 첫 구매 이후 추가 구매가 없는 일회성 고객 |
    | **전체고객이탈여부** | `churn + only_first_tran` | 주기적 이탈자와 일회성 고객을 통합한 최종 라벨 |


2) **RFM**
    - 고객 데이터를 최종 구매 시점(Recency), 구매 빈도(Frequency), 구매 금액(Monetary)을 통해 분석
    - 고객 등급을 매기고, 고객 유형을 파악할 수 있다. 구매 가치가 높거나, 잠재력을 가진 고객, 혹은 이탈을 주의해야 하는 고객을 묶고 분류할 수 있음

    |요소 (RFM)|정의|평가에 미치는 영향|마케팅 활용 방안|
    |:--|:--|:--|:--|
    |`Recency`|고객이 마지막으로 구매한 시점이 얼마나 최근인지|최근 구매 고객은 브랜드와의 관계가 활발하여 긍정적 반응 가능성 높음|재방문 유도, 리마인더 이메일, 한정 프로모션 제공
    |`Frequency`|일정 기간 내 구매 횟수|구매 빈도가 높을수록 충성도가 높고 지속적 수익 창출 가능성 큼|VIP 혜택, 로열티 프로그램 등으로 관계 강화|
    |`Monetary`|일정 기간 동안 지출한 총 금액|높은 구매 금액 고객은 큰 수익을 제공하는 핵심 고객|고가 상품 추천, 개인화 서비스, 맞춤형 제안 제공|
---

### 5.3 피처 엔지니어링 (Feature Engineering)

#### 5.3.1 타겟 인코딩 (Target Encoding)
범주형 변수의 각 클래스를 해당 클래스의 **평균 이탈률**로 변환하여 모델이 카테고리별 위험도를 학습할 수 있게 했습니다.
* **의미**: 특정 그룹(예: 특정 상품군)의 값이 0.3이라면, 해당 그룹 구매 고객의 이탈 확률이 30%임을 의미합니다.
* **과적합 방지**: `TargetEncoder(smooth="auto")`를 적용하여 데이터 편향을 최소화했습니다.


#### 5.3.2 고객 단위 집계 (Aggregation)
거래(Transaction) 단위 데이터를 모델 학습에 적합한 고객(Customer) 단위로 집계했습니다.

| 분석 지표 | 집계 로직 | 비고 |
| :--- | :--- | :--- |
| **RFM 지표** | `first` | 집계된 Recency, Frequency, Monetary 값 유지 |
| **인코딩 피처** | `mean` | 다회 구매 고객의 경우 구매한 상품군/시점의 평균 위험도 반영 |
| **Target(라벨)** | `first` | 최종 이탈 여부 라벨링 |

### 5.4 최종 데이터 구조 
전처리가 완료된 데이터는 분석 목적에 따라 두 가지 파일로 저장됩니다.

1.  **`total_churn.csv`**: 전체 고객을 대상으로 한 이탈 예측용 데이터
2.  **`new_churn.csv`**: 신규 가입 고객의 초기 이탈 방지를 위한 예측용 데이터

| 주요 컬럼명 | 설명 |
| :--- | :--- |
| `API_ratio_mean` | 고객별 평균 구매 주기 (활동성 지표) |
| `최근구매경과일_R` | 마지막 구매로부터 흐른 시간 (최신성 지표) |
| `총구매횟수_F` | 총 거래 건수 (충성도 지표) |
| `총구매금액_M` | 고객 생애 가치 (수익성 지표) |
| `*_라벨인코딩_*` | 상품군, 멤버십, 연령대별 이탈 위험도 확률값 |

## 📊 EDA

### 5.3 상관관계 분석

---

### 5.4 이탈률 분포

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

#### 기타
- [데이터 분석가 Seongbin이 말하는 RFM 정의](https://www.fanruan.com/ko-kr/blog/rfm)
- [스토어 성장 전략 전문 미디어 및 팟캐스트](https://ecommercefastlane.com/ko/what-is-customer-churn-3-effective-strategies-to-reduce-it)