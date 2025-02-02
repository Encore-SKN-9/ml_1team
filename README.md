# ml_1team
# 0.팀 소개

### 팀명 : 밸런스(Balance)

학업과 음주의 균형을 맞추자는 의미를 가짐




<table align=center>
<tbody>
<tr>
<td align=center><b>김도연</b></td>
<td align=center><b>박주은</b></td>
<td align=center><b>서예찬</b></td>

</tr>

<tr>
<td><a href="https://github.com/youngseo98"><div align=center>@doyeon158</div></a></td>
<td><a href="https://github.com/yujitaeng"><div align=center>@pprain1999</div></a></td>

<td><a href="https://github.com/Hack012"><div align=center>@syc9811</div></a></td>

</tr>
</tbody>
</table>

<br><br><br>



# 성적 예측 모델 개발 프로젝트

## 1. 프로젝트 주제
- **주제:** 학생들의 성적을 예측하는 머신러닝 모델 개발
- **목표:** 학습자의 과거 성적 및 관련 데이터를 활용하여 성적을 예측함으로써, 학습 성과를 미리 파악하고 개선 방향을 제시할 수 있는 도구를 제공.

---

## 2. 주제 선정 배경
- **교육적 필요성:** 학업 성취도를 미리 예측하면 학생들에게 맞춤형 학습 전략을 제시할 수 있음.
- **데이터 활용 가능성:** 학생들의 성적, 출석률, 과제 점수 등 다양한 데이터를 통해 학습 성과와 관련된 패턴을 분석할 기회.
- **미래의 활용 가능성:** 교육기관이 데이터를 활용하여 교육 품질을 높이고, 학습자 개인의 성장 방향을 제시할 수 있는 가능성.

---

# 3. 사용한 데이터셋 개요 및 전처리 과정
## **데이터셋 개요:**
### **데이터명:**
  **[Student Alcohol Consumption]**
### **데이터 출처:**
[https://www.kaggle.com/datasets/uciml/student-alcohol-consumption/data]
### **데이터 내용**
  - 포함된 주요 변수: 학생의 시험 점수, 출석률, 과제 점수, 수업 참여도 등.
  - 데이터 크기: 총 395명의 학생 데이터, 33개의 변수.
  
- **데이터 전처리 과정:**
 - **컬럼확인**
  





 ![columns](https://github.com/user-attachments/assets/19c7dea8-5fad-4f02-ac0d-20baf6a43260)

  - **결측치 및 이상치 처리:**






    ![G1hist](https://github.com/user-attachments/assets/63ac3f3d-8445-4e91-b597-4ef1ddbcf170)

    
    ![G2hist](https://github.com/user-attachments/assets/886f7137-ae27-421e-b4be-ba57e8f48f27)

  
  
    ![G3hist](https://github.com/user-attachments/assets/83614fb3-e85f-4999-becf-8fbd67dc024c)

  
  
  
  
  
  
  
  
  - **스케일링:** 모델 학습 성능 향상을 위해 변수 정규화/표준화.
  - **특성 선택:** 주요 변수(Feature)만을 선정하여 데이터 차원 축소.

---

## 4. 사용한 모델과 학습 성능 측정 결과
- **모델 개요:**
  - 사용된 모델: 선형 회귀, 랜덤 포레스트, XGBoost, LIGHTFGBM, Gradient Boosting,HistGradientBoosting,LinearRegression
   

- **성능 평가 결과:**
  - 사용된 평가 지표: RMSE, MAE, R² 등.
  - 베스트 모델의 성능 결과:
    - RMSE: XX
    - MAE: YY
    - R²: ZZ

- **성능 향상을 위한 노력:**
  - 데이터 전처리 개선(예: 추가 특성 생성).
  - 하이퍼파라미터 최적화.
  - 앙상블 기법 적용.

---

## 5. 실제 예측 결과
- **예측 예시:**
  - 예측값과 실제값 비교 표/그래프 제공.
  - 특정 학생 데이터에 대한 예측 결과:
    - 실제 성적: XX점
    - 예측 성적: YY점
    - 오차: ZZ점

---

## 6. 프로젝트 기대 효과
- **학습 성과 개선:** 학생들이 자신의 학습 성과를 사전에 예측하고, 필요한 학습 전략을 세울 수 있는 도구 제공.
- **교육 데이터 활용 확대:** 교육기관이 데이터를 기반으로 한 의사결정을 내리는 데 기여.
- **확장 가능성:** 더 많은 데이터 및 변수를 추가하여 다양한 환경에서의 성적 예측 가능.
