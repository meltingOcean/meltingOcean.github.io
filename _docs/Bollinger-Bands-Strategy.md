---
title: "Bollinger Band Strategy"
permalink: /docs/bollinger-bands-strategy/
excerpt: "Bollinger-Bands Strategy"
last_modified_at: 2021-10-02T22:54:05-04:00
redirect_from:
  - /theme-setup/
toc: true
---

# Bollinger Band

해당 문서는 볼린저밴드를 활용한 전략을 포함하고있다.

## 볼린저 밴드(Bollinger Bands) 란?
볼린저 밴드(Bollinger Bands) 는 1980년대 Jhon A. Bollinger 에 의해 개발된 주가 기술분석 도구이다. 굉장히 단순해 보이는 지표이지만 강력한 지표이다.

볼린저 밴드를 알기 전에 우선 이동 평균선 개념에 대해서 알아야한다. 이동 평균선이란 일정 기간동안의 데이터의 평균으로, 해당 기간동안의 추세를 관찰할 수 있다.

볼린저 밴드는 중단밴드와 상단밴드, 하단밴드로 이루어져있다. 이동평균선의 기간(window)는 보통 20일로 잡고 중단밴드와 상,하단과의 차이는 2 * 20일 표준편차로 잡는다

상단밴드 = 중간밴드 + 20일 이동표준편차 * 2
중단밴드 = 20일 이동 평균선
하단밴드 = 중간밴드 = 20일 이동표준편차 * 2


## [기본전략](/posts/2021/09/24/20210924_1/)

## 특성추출


## 머신러닝 전략
### Regression
### Clustering


## 딥러닝 전략
### 단층 퍼셉트론
### CNN
### RNN
### LSTM