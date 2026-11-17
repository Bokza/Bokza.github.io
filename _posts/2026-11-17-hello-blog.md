---
title: 블로그를 시작합니다
date: 2026-11-17 20:00:00 +0900
categories: [Blog, Notice]
tags: [intro, data-science]
math: true
---

데이터 사이언스와 머신러닝 공부·실험 기록을 남기는 블로그입니다.

## 앞으로 쓸 글

- 추천시스템, 수요예측 실습 정리
- 데이터 분석 대회 참가 회고
- 사이드 프로젝트 개발기

## 기능 테스트

코드 하이라이팅:

```python
import pandas as pd

df = pd.read_csv("train.csv")
df.groupby("item_id")["sales"].mean().head()
```

수식 (`math: true`일 때 렌더링):

$$
\text{RMSE} = \sqrt{\frac{1}{n}\sum_{i=1}^{n}(y_i - \hat{y}_i)^2}
$$

> 글은 `_posts/YYYY-MM-DD-제목.md` 형식으로 추가하면 됩니다.
{: .prompt-tip }
