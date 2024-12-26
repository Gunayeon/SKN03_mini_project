## ⭐️ 3rd Project ⭐️

### 📱 통신사 고객 이탈 분석 및 예측 시스템 📲
<br>
<h4>📌 설명</h4> 
이 프로젝트는 통신사 고객 데이터를 활용하여 고객 이탈 여부를 예측하고, 이탈 고객의 주요 특성을 분석하여 솔루션을 제시하는 웹 애플리케이션이다. <br>
머신러닝과 딥러닝 두 가지 방법으로 데이터를 분석했으며, 랜덤 포레스트보다 LSTM을 활용한 딥러닝 모델이 더 높은 성능을 보였다. 특히, 시계열 데이터를 적용하여 기존의 데이터 활용 방식을 확장한 점에서 차별화된 접근 방식을 시도했다.<br>
또한, Django 기반의 웹 애플리케이션을 통해 관리자 페이지, 예측 페이지, 이탈 방지 솔루션 페이지를 제공하여 실질적인 비즈니스 활용성을 높였다.<br>

<br>
 
#### 📌 개발 기간
 2024.09.23 ~ 2024.09.24

<br>

#### 📌 프로젝트 주요 내용
① **이탈 고객 예측 모델 개발**
> 머신러닝 `Random Forest`와 딥러닝 `LSTM`을 활용해 고객 이탈 여부를 예측<br>
> 그 결과, 딥러닝 모델(LSTM)이 랜덤 포레스트보다 f1-score, accuracy 등 4개의 평가지표에서 더 높은 성능을 기록<br>

② **시계열 데이터를 활용한 분석**
> 주어진 데이터뿐 아니라 이전 데이터를 추가 활용하여 시계열 데이터를 기반으로 고객 이탈을 분석<br>
> 기존 방식보다 정교한 예측 모델을 개발하여 차별화된 결과 도출<br>

③ **관리자 페이지**
> 고객 이탈 예측 결과와 주요 feature importance를 시각화하여 관리자에게 제공<br>
> 이를 통해 고객 관리 전략 수립에 필요한 구체적 인사이트를 제공<br>

④ **예측 및 솔루션 페이지**
> 제주도 지역별 실시간 날씨와 기간별 날씨 데이터를 통해 관광객들에게 유용한 정보를 제공할 수 있음<br>
> 날씨 데이터를 기반으로 여행 일정을 조율하고 불필요한 불편함을 줄일 수 있음

⑤ **지역별 방문 인구수와 매출액 정보 제공**
> **이탈 고객 예측 페이지** : 모델을 연동해 실시간으로 고객 이탈 여부를 확인<br>
> **이탈 방지 솔루션 페이지** : 이탈 고객의 주요 특성을 기반으로 맞춤형 솔루션을 제시<br>

<br>

#### 📌 프로젝트 주요 사용기술
① 데이터 수집 및 활용
> 주어진 데이터셋: Kaggle의 통신사 고객 데이터 활용<br>
> 데이터 전처리 및 분석 : `Pandas`, `Numpy`, `scikit-learn`

② 모델 개발
> 머신러닝 : `Random Forest`<br>
> 딥러닝 : `LSTM`, `Keras`, `TensorFlow`

⓷ 웹 프레임워크
> `Django` : 백엔드 및 웹 애플리케이션 개발<br>

⓸ 데이터 시각화 및 UI 
> `chart.js`, `apeaxcharts` : 데이터를 기반으로 생성된 차트를 html에 동적으로 랜더링
> `HTML`, `CSS`, `JavaScript`: 기본 UI 구성 및 동적 웹 요소 구현
<br> 

#### 📚 모델 결과

| Random Forest 결과 | LSTM 결과 | 
|--|--|
| ![image](https://private-user-images.githubusercontent.com/91773184/370141889-fc24e0cd-da5b-4b34-b1d8-bedc19f356e6.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUxOTU4MTgsIm5iZiI6MTczNTE5NTUxOCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDE4ODktZmMyNGUwY2QtZGE1Yi00YjM0LWIxZDgtYmVkYzE5ZjM1NmU2LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDA2NDUxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTg5MjQ3NWI2OTQ1YzI4NjM5NzUwNzgyMzk1ZDlhY2M2ZWZkYzEyMmMzMjhmMTA5OTU0Y2ZjMjQ4M2FjN2UyZGYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.fh98wkVt9edscGitjqlEOaraTe5wIfdidOI11EgtB6A) | ![image](https://private-user-images.githubusercontent.com/91773184/370141992-fc26a240-8913-4b83-9f97-a6746f0f2225.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUxOTU4MTgsIm5iZiI6MTczNTE5NTUxOCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDE5OTItZmMyNmEyNDAtODkxMy00YjgzLTlmOTctYTY3NDZmMGYyMjI1LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDA2NDUxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTgyZmZmOTExYWFjYTljMjUwOWQ2ODE1ZTZmYjg3NjU0Y2ExNDdkZTM2MWZkNjlhMzQxMDAwNDBhNTVkZmQzNGEmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.5LWJECbSALHN2du1EGrLsKai3Suw7iS4BF8IDSf-pho) |
| 주요 변수 | LSTM 성능|
| ![image](https://private-user-images.githubusercontent.com/91773184/370141926-9bc211b1-9d90-4e14-8b40-422eb78e7d9e.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUxOTU4MTgsIm5iZiI6MTczNTE5NTUxOCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDE5MjYtOWJjMjExYjEtOWQ5MC00ZTE0LThiNDAtNDIyZWI3OGU3ZDllLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDA2NDUxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTZhNjU3OGMwN2Q5NjkyY2U5Y2EzMjAyMDk2ZGVkNTYyYWQ3MTM3NTRlYzNmNDI1M2VhYzVmOThiOTRkODYwN2UmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.9dY6M3NvjbtfDdeyOEAG5QPpTyVdL5NxNUZbfuzVUD0) | ![image](https://private-user-images.githubusercontent.com/91773184/370142036-6b8bc69d-be69-4b91-a7f2-8065a40dd63b.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUxOTU4MTgsIm5iZiI6MTczNTE5NTUxOCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDIwMzYtNmI4YmM2OWQtYmU2OS00YjkxLWE3ZjItODA2NWE0MGRkNjNiLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDA2NDUxOFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPWQ4NjRhNWJmNjI5Nzg0MmZmNTg3MWUxM2NhMmQ3MGI1NTVlZWZkMDY4N2Y3Yzc1MjZjYzRjMWQwZWU0MmU2ODYmWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.jU3cLtDXv57DJnWUAcLnGmfO4zQU1CcAIOsPbQX4xMI)
| LSTM LOSS | Attention 가중치 시각화 |
| ![image](https://private-user-images.githubusercontent.com/91773184/370142001-72834889-bbd7-459f-a214-eb6cd79b0fa4.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUyMDk0MjQsIm5iZiI6MTczNTIwOTEyNCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDIwMDEtNzI4MzQ4ODktYmJkNy00NTlmLWEyMTQtZWI2Y2Q3OWIwZmE0LnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDEwMzIwNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTY0NThhZGY0YjcwMmUyM2E5YjlhMWQ3YmFiNGM0ZTlkNGU1YjIxN2IxYzE4NzBiMzVkOThiZThjOTA2MWVmNGImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.xpKPUNBjDgJnrSI2dARE53aAJts7ok8YZqmCOtp2RjQ) | ![image](https://private-user-images.githubusercontent.com/91773184/370142089-fa0caf86-0b0a-4f3d-b4b1-579584eacf6c.png?jwt=eyJhbGciOiJIUzI1NiIsInR5cCI6IkpXVCJ9.eyJpc3MiOiJnaXRodWIuY29tIiwiYXVkIjoicmF3LmdpdGh1YnVzZXJjb250ZW50LmNvbSIsImtleSI6ImtleTUiLCJleHAiOjE3MzUyMDk0MjQsIm5iZiI6MTczNTIwOTEyNCwicGF0aCI6Ii85MTc3MzE4NC8zNzAxNDIwODktZmEwY2FmODYtMGIwYS00ZjNkLWI0YjEtNTc5NTg0ZWFjZjZjLnBuZz9YLUFtei1BbGdvcml0aG09QVdTNC1ITUFDLVNIQTI1NiZYLUFtei1DcmVkZW50aWFsPUFLSUFWQ09EWUxTQTUzUFFLNFpBJTJGMjAyNDEyMjYlMkZ1cy1lYXN0LTElMkZzMyUyRmF3czRfcmVxdWVzdCZYLUFtei1EYXRlPTIwMjQxMjI2VDEwMzIwNFomWC1BbXotRXhwaXJlcz0zMDAmWC1BbXotU2lnbmF0dXJlPTJlMDAyNDhiOGY1N2MzYjBiYjZiZTY3YjEwZjkxMDdmNjU3YjY2MzIzYjAzMDgyNDRmN2U3ZjBjNDU2MGQxNmImWC1BbXotU2lnbmVkSGVhZGVycz1ob3N0In0.W-Uasy_6aDAWYPlGVn3o9pmdSKE_zkRBoTh0O8FZAJE)

<br>

#### 🎯 프로젝트 주요 가치 및 활용점
> 이 시스템은 고객 이탈 문제를 효과적으로 예측하고 분석하여, 통신사 관리자에게 실질적인 솔루션을 제공하는 데 중점을 둔 프로젝트이다.
특히, 시계열 데이터를 활용한 정교한 분석, 딥러닝 기반의 고성능 예측 모델, 관리자와 실무자를 위한 직관적 웹 UI를 통해, 데이터 분석 결과를 실질적인 비즈니스 의사결정에 연결한 점이 큰 의의가 있다.<br><br>
> 개인적으로, 이 프로젝트를 통해 머신러닝과 딥러닝 모델을 비교·분석하며 모델 선택의 중요성을 학습할 수 있었고, Django를 활용한 웹 개발 경험을 통해 데이터 분석과 서비스 구현을 통합하는 능력을 기를 수 있었다.
팀원들과 함께 작업하며, 효율적인 데이터 활용 전략과 역할 분담의 중요성을 체감한 프로젝트였다.<br><br>
> 다만 아쉬웠던 점은, 주어진 기간은 짧으나 우리가 구현해야하는 추가 범위가 점점 늘어나니 기한 내에 개발하는 것이 쉽지않았다. 모델개발을 조금 더 일찍 마쳐 중요 feature들을 조금 더 일찍 파악했더라면 더욱 효과적인 관리자 페이지를 만들 수 있었을 거 같다.
