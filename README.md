# GOMSanalysis
## 청년세대의 이직 요인 분석 및 분류 예측 모형 개발: 직장 및 개인의 특성과 환경을 중심으로

## 🏹 **핵심** 내용
<img width="541" alt="스크린샷 2025-01-27 오후 9 25 53" src="https://github.com/user-attachments/assets/a0040368-8acf-48aa-9e69-2dc635a3d3f3" />

### 1 : [Business Understanding]
<img width="556" alt="스크린샷 2025-01-27 오후 9 26 16" src="https://github.com/user-attachments/assets/bb0e9831-cf9e-493e-9c4e-6a07713b75fc" />

### 2 : [Data Understanding]

- 한국고용정보원, 대졸자직업이동경로조사(GOMS, Graduate Occupational Mobility Survey)
    - 2010~ 2022
- 각 문항 하나하나의 중요도를 판단하여 총 1,333개의 설문 문항 → 205개로 축소
<img width="548" alt="스크린샷 2025-01-27 오후 9 26 27" src="https://github.com/user-attachments/assets/c7c49471-c8df-4ef4-966f-ef92e531c53d" />

[가설 설정]

- 종속 변수: **이직 여부**
- 독립 변수: 4가지 가설을 세운 후, 가설에 따라 관련 변수 분류
    - 가설 1: 이직은 **직장의 특성**과 인과관계를 가진다.
    - 가설 2: 이직은 **직장에 대한 개인의 특성**과 인과관계를 가진다.
    - 가설 3: 이직은 **직장에 대한 개인의 만족도**가 높을수록 이직과 부(-)의 관계를 가진다.
    - 가설 4: 이직은 **개인의 환경**과 인과관계를 가진다.

### 3 : [Data Preprocessing]

[파생변수 생성- 연봉 관련 변수]
- 연도별 최저임금과 비교, **연도별 최저임금 대비 비율**로 변환
<img width="553" alt="스크린샷 2025-01-27 오후 9 26 41" src="https://github.com/user-attachments/assets/a058135c-44e6-4789-b789-b6482c2cf254" />

[파생변수 생성- 학점 관련 변수]
- 대학별 학점 만점 기준이 상이하므로, **만점 대비 비율**로 변환
<img width="549" alt="스크린샷 2025-01-27 오후 9 27 00" src="https://github.com/user-attachments/assets/fb33ffd1-91ec-424e-9b86-44eb16816eae" />

### 4 : [Modeling- Task1]
<img width="570" alt="스크린샷 2025-01-27 오후 9 27 18" src="https://github.com/user-attachments/assets/3f7e88f3-4e34-4eba-903f-439881a5bc52" />

### 5 : [Modeling- Task2]
<img width="563" alt="스크린샷 2025-01-27 오후 9 27 32" src="https://github.com/user-attachments/assets/c7c6b8bb-b64d-4ab3-878f-a2fcb4d3ea14" />

### 6 : [Evaluation]
<img width="566" alt="스크린샷 2025-01-27 오후 9 27 52" src="https://github.com/user-attachments/assets/beb4eabb-a58a-4238-9fa9-e47c80330e67" />

**[인사이트]**

- 실제 직장 생활을 통해 얻어낼 수 있는 정보가 대부분 이직 요인으로 작용함
    - 기업은 지원자에게 기업에 대한 자세한 정보를 미리 제공할 필요가 있음
- 복지와 혜택을 제공 여부와 개인의 삶의 질 관련 변수 또한 이직 여부에 큰 영향을 미침
    - 기업은 개인의 복지와 삶의 질을 향상한 기업 운영을 통해 이직률을 줄일 수 있을 것으로 기대
- 개인은 이직에 있어 근로소득을 중요하게 여김
- 전공 만족도가 높고, 대학 졸업 전부터 취업 목표를 준비해온 개인은 이직률이 상대적으로 낮음
    - 졸업 전부터 개인 스스로를 잘 파악하고, 계획적으로 취업 목표를 세울 경우 이직하는 경우를 낮출 수 있음
- 개인은 기업의 고용 안정성과 개인 발전 가능성, 직업의 전망을 고려해 이직을 결정함
