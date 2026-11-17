---
title: "[해운·물류 Weekly 01] 11월 3주차 해운·물류 AI·데이터 소식"
date: 2026-11-17 18:00:00 +0900
categories: [해운·물류 Weekly]
tags: [해운, 물류, 항로최적화, 해빙예측, 자율운항]
description: "2026.11.10~11.17 해운·물류 AI·데이터 소식. DNV 선박 데이터, 목포해양대 AI 항법 실해역 시험, UNIST 북극 해빙 예측, 머스크 IoT, PIER71 스마트포트 챌린지"
image:
  path: /assets/img/posts/2026-11-17-shipping-weekly-01/thumbnail.png
  alt: "해운·물류 Weekly 01 썸네일"
---

> 대상 기간 `2026.11.10 ~ 11.17`
>
> 해운·물류에서 AI와 데이터로 무언가를 예측하거나 분석한 소식을 모았다. 이번 주는 북극 해빙 예측, AI 항법 실해역 시험처럼 국내 연구 쪽 소식이 많았다.

| 날짜 | 소식 | 예측·분석 대상 |
| --- | --- | --- |
| `11.17` | DNV, 선박 센서·운항 데이터로 연료·전력 사용 최적화 | 연료 소비, 탄소 배출 |
| `11.16` | 목포해양대, 디지털 수로 정보 기반 AI 항법 실해역 시험 | 항행 위험, 선박 교통 흐름 |
| `11.16` | 해양교통안전공단·전자기술연구원, AI 해양안전 기술 협약 | 어선 안전, 자율운항선 안전 |
| `11.15` | UNIST, 북극 해빙 예측 AI '아이스네스트' | 북극항로 해빙 분포 |
| `11.11` | 머스크, 연간 25억 건 넘는 IoT 데이터로 운항 예측 | 접안 시간, 연료, 운항 위험, 공급망 지연 |
| `11.11` | 싱가포르 PIER71 스마트포트 챌린지 수상 기업 발표 | 연료가 덜 드는 항로 |

---

## 01. DNV, 선박 데이터로 연료와 전력 사용을 줄인다

`11.17` · [ZDNet Korea](https://zdnet.co.kr/view/?no=20261117093217)

선급 DNV가 선박에 달린 센서 값과 운항 기록으로 연료와 전력 사용을 최적화하는 방식을 소개했다. 배출 관리 플랫폼에 연결된 선박은 **6만 5천 척이 넘는다**.

## 02. 목포해양대, AI 항법 시스템 실해역 시험 마쳐

`11.16` · [IndexBox](https://www.indexbox.io/ko/blog/south-korean-researchers-complete-sea-trials-of-ai-navigation-system-using-digital-hydrographic-data/) (원 보도 Splash247)

디지털 수로 데이터를 받아 항해 판단을 돕는 시스템이다. Kongsberg 시뮬레이터에서 먼저 검증하고 실습선으로 실제 바다에서 시험했다. 시스템이 계산하는 것은 네 가지다.

- 다리 밑을 지날 때 남는 높이(동적 에어 드래프트)
- 부표가 원래 자리에서 얼마나 밀렸는지
- 기상과 해상 상태에 따른 위험도
- 주변 선박 교통 밀도

삼성중공업 자율운항 기술과 호환되도록 만들고 있고, 국제수로기구(IHO)의 S-129 표준에 맞추는 작업도 진행 중이다. 성능 수치는 기사에 나오지 않았다.

## 03. 해양교통안전공단·전자기술연구원, AI 해양안전 협약

`11.16` 보도 (협약 체결 11.13) · [뉴스핌](https://www.newspim.com/news/view/20261116000310)

두 기관이 함께 개발하기로 한 분야는 세 가지다. 어선 설계 데이터를 모은 AI 플랫폼과 어선 자가진단 기술, 전기추진선·자율운항선의 AI 안전 기술, 그리고 등대·부표 같은 항로표지의 AI 전환이다. 아직 협약 단계라 구체적인 모델이나 데이터 규모는 나오지 않았다.

## 04. UNIST, 북극 해빙을 30일 앞까지 예측하는 '아이스네스트'

`11.15` · [KPI뉴스](https://www.kpinews.kr/newsView/1065584546072810)

북극 바다를 6.25km 격자로 나누고, 칸마다 바다가 얼음으로 덮일지 최대 30일 앞까지 예측한다. 북극항로를 언제까지 다닐 수 있는지(통항 종료일) 맞히는 오차가 **3.5일에서 2.75일로** 줄었다.

UNIST, 한국수자원공사, 캐나다 연구팀이 함께 만들었다. 격자마다 시간에 따라 바뀌는 값을 예측하는 구조라, 시계열 예측을 공간으로 넓힌 문제로 볼 수 있다.

## 05. 머스크, 1년에 IoT 데이터 25억 건 넘게 처리

`11.11` · [한국해사주간](https://www.monthlymaritimekorea.com/news/articleView.html?idxno=58120) (2026 첨단 해양모빌리티 국제포럼 발표)

- 처리하는 IoT 데이터가 1년에 **25억 건이 넘는다**.
- 이 데이터로 항만 선석이 언제 빌지 예측하고, 그에 맞춰 운항 속도를 조절한다.
- 연료 소비, 운항 위험, 공급망 지연도 같은 데이터로 예측한다.

## 06. 싱가포르 PIER71 스마트포트 챌린지, 항로 최적화 스타트업이 1위

`11.11` · [MarineLink](https://www.marinelink.com/news/smart-port-challenge-draws-record-544290)

싱가포르 해사항만청(MPA)과 싱가포르국립대가 여는 해운 스타트업 대회다. 올해 10회째로, 39개국 281개 스타트업이 586건을 제안해 역대 가장 많았다.

| 상 | 기업 | 하는 일 |
| --- | --- | --- |
| 최고 스타트업상 | Ocean Intelligence (호주) | 해류·기상·선박 특성을 합쳐 연료가 덜 드는 항로 계산 |
| 최고 스케일업상 | 뷰런테크놀로지 (한국) | AI 라이다 인지 기술 |
| 특별상 | Trunk Technology (중국) | 항만 자율주행·차량 관리 |

참가 스타트업들은 해운사 28곳과 시범 사업 의향서를 맺었다.

---

## 출처

<details markdown="1">
<summary>출처 6개 펼치기 (날짜는 각 페이지의 게재일·발표일)</summary>

- `11.17` [ZDNet Korea: 친환경 선박의 숨은 무기 AI…연료비·탄소배출 동시에 줄인다](https://zdnet.co.kr/view/?no=20261117093217)
- `11.16` [IndexBox: 한국 연구진, 디지털 수로 데이터 활용 AI 항법 시스템 실해역 시험 완료](https://www.indexbox.io/ko/blog/south-korean-researchers-complete-sea-trials-of-ai-navigation-system-using-digital-hydrographic-data/)
- `11.16` [뉴스핌: 해양교통안전공단·전자기술연구원, AI로 선박사고 예방](https://www.newspim.com/news/view/20261116000310)
- `11.15` [KPI뉴스: UNIST, 북극항로 선박운항 돕는 AI 개발](https://www.kpinews.kr/newsView/1065584546072810)
- `11.11` [한국해사주간: 2026 첨단 해양모빌리티 국제포럼](https://www.monthlymaritimekorea.com/news/articleView.html?idxno=58120)
- `11.11` [MarineLink: Smart Port Challenge Draws Record 586 Proposals, Names 2026 Winners](https://www.marinelink.com/news/smart-port-challenge-draws-record-544290)

</details>

---

데이터 사이언스 소식은 같은 날 올린 [DS Weekly 01]({% post_url 2026-11-17-ds-weekly-01 %})에 따로 모았다.
