---
layout: post
title: "[데이터 블로그 챌린지] 2일차"
subtitle: "데이터분석가에게 코딩테스트가 필요할까?"
date: 2023-04-26 00:00:00 -0100
background: '/img/posts/06.jpg'
---

이 post는 데분당태 메이커스 클럽의 데이터 블로그 챌린지 3일차 글입니다

다음의 링크를 참고하였습니다: [통계학이 제품 분석의 실제 도구가 되는 과정](https://yongsquant.github.io/2022/08/15/statistics-to-fields.html)

## 제목
#### 통계학이 제품 분석의 실제 도구가 되는 과정


## 요약
#### 1. 기존과 다른 도메인에서 사용되는 모델
   - Cox Proportional-Hazards Model
   - 암환자의 생존율을 예측하던 모델 > 고객 이탈 분석

#### 2. PCA,SVD 의 산업 분야 활용
  - 이미지나 음향의 압축에 사용.
  - 아마존, Netflix 의 matrix factorization 시스템 (User의 contents에 대한 반응 예측)

#### 3. Instrumental variable
  - 대학 입학이 임금에 미치는 영향(Card, 1995) 을 분석할 때 사용
  - 제품 A/B test (User의 내재적인 특성을 분리하기 어려울 때)

#### 4. Machine learning
  - 기존 방법들을 linear model로 해석할 수 있다. (ex. Decision tree)
  - Deep learning의 weight를 추정하기 위해 MLE, Autoregression 등이 사용.


## 인사이트
* 기존 방법들이 전혀 다른 domain에서도 활용 가능하다.
* 데이터 분석에 있어 통계학에 대한 이해가 바탕이 되어야 한다.
* 그러나, 통계학 또한 세상을 이해하는 하나의 철학으로 절대적인 지표가 아니다.
