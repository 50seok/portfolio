# 👋 Intro

> **항상 새로운 것을 배우고, 협력하는 오영석입니다.**

새로운 기술을 빠르게 익히고 팀과 함께 문제를 풀어가는 것을 좋아합니다.

<br>

# 📝 Projects

## 1. 도파민 체크 (DopaCheck)

> 배달 한 번, 스크롤 한 시간 — 내 도파민 소비를 숫자로 마주하는 서비스

배달 영수증을 올리면 **"치킨 1.2마리값, 러닝 28분어치"** 로, SNS·게임 시간을 입력하면 **"책 2권"** 으로 환산해 보여줍니다. AI가 공감 코멘트와 맞춤 챌린지를 제안하고, 종합 도파민 점수로 소비 패턴 변화를 추적합니다.

- **개발 기간** : 2026.06 (AI 심화 과정 6인 팀 프로젝트, 약 1주)
- **담당 역할** : AI 모듈 + 챌린지 (FR-32~45)
  - 영수증 OCR 파싱 (`ai/ocr.py`)
  - 음식 칼로리 추론 (`ai/calorie.py`)
  - 공감 코멘트 생성 (`ai/comment.py`)
  - 도파민 점수 산출 (`ai/score.py`)
  - 히스토리 기반 맞춤 챌린지 추천 (`ai/challenge.py`)
  - AI 호출 실패 시 수동 입력 fallback 처리
- **기술 스택** : `Python` `Flask` `Jinja2` `MariaDB` `Claude API` `OAuth(Google·Kakao)` `Cloudtype`
- **링크** : [GitHub](https://github.com/luma-team-ai/dopacheck)

<br>

## 2. SeoulEVCheck — 서울 전기차 충전 인텔리전스

> 서울시 전기차 충전 데이터로 수요를 예측하고 운영을 권고하는 데이터 인텔리전스 프로젝트

한국전력공사 공공데이터 63만 건의 충전 세션을 분석해 자치구·충전소 단위 충전 수요를 예측합니다. 한 주제를 ML → DL → LLM으로 3주에 걸쳐 점진 확장하는 머신러닝 심화 개인 프로젝트입니다.

- **개발 기간** : 2026.06 ~ (머신러닝 심화 3주 커리큘럼, 개인 프로젝트)
- **담당 역할** : 전 과정 단독 수행
  - 데이터 전처리 · EDA (63만 세션, 주소→자치구 추출)
  - 충전 수요 예측 모델링 (자치구 모델 RandomForest **R²=0.940**, 2026년 실데이터 검증 **R²=0.806**)
  - 충전소 핫스팟 랭킹(TOP-N) 분석
  - Streamlit 앱 (수요 예측 · 구별 지도 · 핫스팟)
- **기술 스택** : `Python` `pandas` `scikit-learn` `XGBoost` `Streamlit`
- **링크** : [GitHub](https://github.com/50seok/SeoulEVCheck)

<br>

## 3. (프로젝트명)

> 한 줄 소개

- **개발 기간** :
- **담당 역할** :
- **기술 스택** :
- **링크** :

<br>

## 4. (프로젝트명)

> 한 줄 소개

- **개발 기간** :
- **담당 역할** :
- **기술 스택** :
- **링크** :

<br>

## 5. (프로젝트명)

> 한 줄 소개

- **개발 기간** :
- **담당 역할** :
- **기술 스택** :
- **링크** :

<br>

# 🎞 Youtube

[![DopaCheck 시연 영상](https://img.youtube.com/vi/v-mCKvA6tYQ/maxresdefault.jpg)](https://youtu.be/v-mCKvA6tYQ)

▶️ [영상 보기](https://youtu.be/v-mCKvA6tYQ)

<br>

# 📞 Contact

[![Naver](https://img.shields.io/badge/Naver-03C75A?style=flat-square&logo=Naver&logoColor=white)](mailto:dhdudtjr61@naver.com)
[![GitHub](https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=GitHub&logoColor=white)](https://github.com/50seok/portfolio)
[![YouTube](https://img.shields.io/badge/YouTube-FF0000?style=flat-square&logo=YouTube&logoColor=white)](https://youtu.be/v-mCKvA6tYQ)
