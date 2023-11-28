# Evaluation-of-Generalized-Performance-of-Korean-Machine-Reading-According-to-the-Evaluation-Dataset
✏KSC2022 - 각 도메인별 평가 데이터셋에 따른 한국어 표 기계독해 일반화 성능 평가

# Abstract
표 데이터는 일반적인 텍스트 데이터와 다르게 구조적인 특장점으로 정보를 압축해 표현할 수 있다. 이는 표가 다양한 도메인에서 활용되는 것으로 이어지며, 기계독해 영역에서의 표 기계독해 능력이 차지하는 비중은 점점 커지고 있다. 하지만 도메인마다 표의 구조와 요구되는 지식이 달라 언어모델을 단일 도메인으로 학습했을 때 다른 도메인에서의 모델의 평가 성능이 하락해 일반화 성능이 낮게 나타날 가능성이 크다. 본 논문에서는 법령 문서, 공문서, 제품 스펙 문서의 3가지 도메인에서 평가 데이터셋을 구축하여 KorQuAD 2.0으로 학습한 언어모델의 표 기계독해 일반화 성능을 비교하는 평가 실험을 진행했다. 본 논문의 실험을 통해서 KorQuAD와 같이 범용적인 도메인을 다루는 데이터셋의 일반화 성능이 가장 좋았으며, 공문서와 같이 도메인에 따라서 표의 형태가 달라지는 경우보다, 법령이나 제품 스펙 문서와 같이 도메인에 특화된 지식을 요구하는 평가 데이터셋이 가장 일반화가 되지 않는 것을 확인할 수 있었다

---
## Model Structure
![image](https://github.com/HyeLynnKIM/Evaluation-of-Generalized-Performance-of-Korean-Machine-Reading-According-to-the-Evaluation-Dataset/assets/64192139/9499c570-d11c-485f-a3c1-79df9ca54267)

---
## Dataset
- 연구실에서 직접 구축한 법령/공문서/제품스펙 데이터

  ![image](https://github.com/HyeLynnKIM/Evaluation-of-Generalized-Performance-of-Korean-Machine-Reading-According-to-the-Evaluation-Dataset/assets/64192139/6003611f-661c-4471-8d4c-ac44810919d8)

- KorQuAD 2.0 테이블 데이터

---
## Result
![image](https://github.com/HyeLynnKIM/Evaluation-of-Generalized-Performance-of-Korean-Machine-Reading-According-to-the-Evaluation-Dataset/assets/64192139/ad11ae41-0562-4c05-a251-f199d7a0a9db)
