# AI 와 함께하는 Python 데이터 분석 첫걸음

> **강사:** 김판다  
> **주최 / 운영:** 전남대학교 이차전지특성화대학사업단 / SEN Lab


## 📚 데이터 분석 입문

### 1. 데이터 분석이란?
**데이터 분석**은 원시 상태의 데이터를 정리, 변환, 모델링하여 의미 있는 정보를 찾아내고, 이를 바탕으로 현명한 의사결정을 지원하는 과정
* **목적:** 데이터 속에 숨겨진 인사이트(Insight) 발견 및 미래 예측
* **핵심 흐름:** 수집 ➔ 정제(Cleaning) ➔ 열 가공(Feature engineering) ➔ 그룹화(Groupby) ➔ 분석(Analysis) ➔ 시각화(Visualization)

---

### 2. 파이썬 데이터 분석 4대 모듈
파이썬 생태계에서 데이터 분석을 수행할 때 반드시 사용되는 4가지 핵심 라이브러리

<img src=https://i.postimg.cc/nrhYDFMf/deiteo-bunseog-modyul-jonglyu.jpg, width=600>

| 라이브러리 | 주요 역할 |
| :--- | :--- |
| **NumPy** | 고차원 행렬 데이터를 처리 |
| **Pandas** | 표 형태의 데이터 관리 및 조작 |
| **Matplotlib** | 가장 기본적인 데이터 시각화 라이브러리 |
| **Seaborn** | 통계 기반의 고수준 시각화 도구 |

---

### 3. 넘파이(NumPy) vs 판다스(Pandas)

<img src=https://i.postimg.cc/02r05yLw/deiteo-bunseog-modyul-jonglyu2.jpg, width=600>

데이터를 처리하는 양대 산맥인 두 모듈은 비슷해 보이지만 사용 목적이 다름.

#### 3.1. NumPy (Numerical Python)
* **특징:** 모든 데이터가 **동일한 자료형**(예: 모두 숫자)일 때 효율적
* **장점:** 수학적 계산이 매우 빠르며 대규모 행렬 연산에 최적화
* **용도:** 딥러닝 모델의 가중치 계산, 복잡한 통계 수식 구현 등.

#### 3.2. Pandas (Panel Data)
* **특징:** 행(Row)과 열(Column)이 있는 **DataFrame** 구조를 사용하며, 열마다 서로 다른 자료형을 가질 수 있음.
* **장점:** 데이터에 이름(Label)이 붙어 있어 사람이 이해하기 쉽고, 데이터 정제 기능이 강력.
---

### 4. 요약: 어떤 상황에 무엇을 쓸까?
> - **숫자 위주의 고성능 연산**이 필요하다면? ➔ **NumPy**
> - **현실의 복잡한 표 데이터**를 가공하고 분석한다면? ➔ **Pandas**



- [데이터 분석 패키지 버전 안내](https://github.com/KimPandas/ok/blob/main/md/version.md)

- [데이터 분석 패키지 설치 안내](https://github.com/KimPandas/ok/blob/main/md/install.md)

---

## 📚 파이썬으로 빅데이터 다루기 체험


* **[파이썬으로 빅데이터 다루기](https://github.com/KimPandas/ss/blob/main/ipynb/01_%ED%8C%90%EB%8B%A4%EC%8A%A4%EB%A1%9C_%EB%8D%B0%EC%9D%B4%ED%84%B0_%EB%8B%A4%EB%A3%A8%EA%B8%B0_%EC%B2%B4%ED%97%98.ipynb)**
* 🔗 [실습 자료 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ex/01_%ED%8C%90%EB%8B%A4%EC%8A%A4%EB%A1%9C_%EB%8D%B0%EC%9D%B4%ED%84%B0_%EB%8B%A4%EB%A3%A8%EA%B8%B0_%EC%B2%B4%ED%97%98(%EC%97%B0%EC%8A%B5).ipynb)



---
## 📊 시각화

* **[파이썬 시각화](https://github.com/KimPandas/ss/blob/main/ipynb/%ED%8C%8C%EC%9D%B4%EC%8D%AC_%EC%8B%9C%EA%B0%81%ED%99%94.ipynb)**
* 🔗 [실습 자료 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ipynb/%ED%8C%8C%EC%9D%B4%EC%8D%AC_%EC%8B%9C%EA%B0%81%ED%99%94.ipynb)


---

## 📊 문제 해결 방법 (with AI)

* [문제 확인](https://github.com/KimPandas/ok/blob/main/md/question.md)
  
* [해결 방법](https://github.com/KimPandas/ok/blob/main/md/sol1.md)
  
* [공식 문서 활용 방법](https://github.com/KimPandas/ok/blob/main/md/doc1.md)

---

## 📊 Case Study 및 EDA

* **[머니볼](https://github.com/KimPandas/ss/blob/main/ipynb/%EB%A8%B8%EB%8B%88%EB%B3%BC.ipynb)** 🔗 [코랩 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ipynb/%EB%A8%B8%EB%8B%88%EB%B3%BC.ipynb)
* **[평점 분석](https://github.com/KimPandas/ss/blob/main/ipynb/%EC%8B%9D%EB%8B%B9_%ED%8F%89%EC%A0%90_%EA%B2%B0%EA%B3%BC_%EB%B6%84%EC%84%9D.ipynb)** 🔗 [코랩 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ipynb/%EC%8B%9D%EB%8B%B9_%ED%8F%89%EC%A0%90_%EA%B2%B0%EA%B3%BC_%EB%B6%84%EC%84%9D.ipynb)
* **[빅데이터 다루기(증권사 데이터)](https://github.com/KimPandas/ss/blob/main/ipynb/%EC%A6%9D%EA%B6%8C%EC%82%AC_%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0_%EC%9E%94%EA%B3%A0_%EB%B6%84%EC%84%9D.ipynb)** 🔗 [코랩 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ipynb/%EC%A6%9D%EA%B6%8C%EC%82%AC_%EB%B9%85%EB%8D%B0%EC%9D%B4%ED%84%B0_%EC%9E%94%EA%B3%A0_%EB%B6%84%EC%84%9D.ipynb)
* **[타이타닉 EDA](https://github.com/KimPandas/ss/blob/main/ipynb/%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89_EDA.ipynb)** 🔗 [코랩 링크](https://colab.research.google.com/github/KimPandas/ss/blob/main/ipynb/%ED%83%80%EC%9D%B4%ED%83%80%EB%8B%89_EDA.ipynb)

