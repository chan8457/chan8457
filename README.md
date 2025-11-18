# 안녕하세요, 데이터로 문제를 정의하고 실험으로 개선하는 사람 **조성찬**입니다.

[![Portfolio Banner](https://via.placeholder.com/1000x200.png?text=Chan's+Portfolio)](https://chan8457.github.io)

> 이미지를 클릭하면 포트폴리오 페이지로 이동합니다.

---

## About Me

저는 요리사로 커리어를 시작해 호텔·레스토랑 현장에서 운영 효율화, 재고 관리, 원가 절감 업무를 담당했습니다.  
코로나 이후 삶을 다시 설계하게 되었고, 160kg에서 85kg으로 감량하는 과정에서  
문제를 정의하고, 가설을 세우고, 실험으로 검증하는 프로세스를 몸으로 익혔습니다.

이 경험을 기반으로 데이터 분야로 전향했고,  
사이버대학교 빅데이터학과 및 Codeit 데이터 분석 부트캠프에서  
실제 비즈니스 문제를 데이터 기반으로 해결하는 프로젝트들을 수행했습니다.

저는 데이터로 문제를 정의하고, 실험으로 개선하는 분석가로 성장하고 있습니다.

**E-mail**: jscro@naver.com  
**Discord**: chan_97

---

## Tech Stack

Python · SQL · Airflow · BigQuery · Dash · Tableau · scikit-learn  

<p align="left">
  <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white"/>
  <img src="https://img.shields.io/badge/SQL-003B57?style=flat-square&logo=postgresql&logoColor=white"/>
  <img src="https://img.shields.io/badge/Airflow-017CEE?style=flat-square&logo=apache-airflow&logoColor=white"/>
  <img src="https://img.shields.io/badge/BigQuery-4285F4?style=flat-square&logo=googlecloud&logoColor=white"/>
  <img src="https://img.shields.io/badge/Dash-3F4F75?style=flat-square&logo=plotly&logoColor=white"/>
  <img src="https://img.shields.io/badge/Tableau-E97627?style=flat-square&logo=tableau&logoColor=white"/>
  <img src="https://img.shields.io/badge/scikit--learn-F7931E?style=flat-square&logo=scikit-learn&logoColor=white"/>
</p>

---

## GitHub Stats

> GitHub 활동 요약

<p>
  <img 
    src="https://github-readme-stats.vercel.app/api?username=chan8457&repo=chan8457.github.io&show_icons=true&theme=default" 
    height="150"
  />
  <img 
    src="https://github-readme-stats.vercel.app/api/top-langs/?username=chan8457&repo=chan8457.github.io&layout=compact&theme=default" 
    height="150"
  />
</p>

<p>
  <img 
    src="https://streak-stats.demolab.com?user=chan8457&theme=default" 
    height="150"
  />
</p>

<p>
  <img 
    src="https://github-readme-activity-graph.vercel.app/graph?username=chan8457&theme=github-light&custom_title=Contribution%20Graph"
  />
</p>

---

# Projects

## 1) 서울시 따릉이 광고 타겟 분석
서울시 공공자전거의 재정 적자 문제를 해결하기 위해  
요금 인상 대신 **LED 광고 도입 방안**을 제안한 프로젝트입니다.

- 2021~2024년 대여 이력 분석  
- 성별·연령·시간대 패턴 분석  
- ANOVA, T-test 등 통계 기반 효율 검증  
- 광고 적합 대여소 후보 선정

---

## 2) 채용 플랫폼 지원 퍼널 분석
채용 플랫폼의 방문 → 열람 → 작성 → 지원으로 이어지는  
**4단계 전환 퍼널**을 분석했습니다.

- MAU 감소 시점 분석  
- 경력 필터 사용 감소 → 구간 세분화 A/B Test 제안  
- 공고 신뢰도 문제 → RFM 기반 기업 세그먼트 제공  
- 지원 직전 이탈 → 지원 현황 요약 모듈 A/B Test

---

## 3) 머신러닝 기반 공유오피스 결제 예측
입퇴실·체류시간·주말 방문 비율 등을 활용해  
**결제 여부 예측 모델**을 구축했습니다.

- 클러스터링 기반 고객 유형 정의  
- LightGBM 결제 예측 모델  
- 체류시간·입퇴실 시각·주말 방문 비중이 핵심 영향 요인  
- 주말 특화 요금제 전략 제안

---

## 4) 서비스 종료된 SNS 앱 로그 분석
10대 익명 투표 앱의 실제 로그 데이터를 기반으로  
정착 실패 원인과 이탈 예측 모델을 구축한 프로젝트입니다.

- 첫 24시간 행동 패턴 분석  
- 7일 미복귀 조기 이탈 예측  
- DAU 316,872 → 7,429(-97.7%) 하락 원인 분석  
- 중심학생 네트워크 기반 유지 전략  
- Airflow → GCS → BigQuery → BQML 파이프라인 구축  
- Discord 알림 및 대시보드 자동화

---

## 5) LLM 기반 여행지 추천 플랫폼 (진행 중)
여러 여행·맛집 플랫폼(카카오맵, 트리플 등)에서 수집한 데이터를 기반으로,  
사용자의 자연어 요청을 LLM이 해석해 여행지를 추천하는 프로젝트입니다.

예)  
"오늘은 바다 보러 가고 싶고, 너무 붐비지 않았으면 좋겠어"

→ 의도 태깅  
→ 실제 장소 데이터 필터링  
→ 여행지 + 주변 명소 + 식당 + 간단한 코스까지 자동 추천

**목표**  
- 여행 데이터 수집·정제 파이프라인 구축  
- 자연어 → 구조화 데이터 변환 (LLM 기반)  
- 추천 알고리즘 + 설명 생성 모델 구현

(진행 중)

---

## Goals
- 실행 가능한 인사이트를 도출하는 데이터 분석가로 성장  
- 문제 정의와 가설 검증 중심의 분석 역량 강화  
- 협업과 소통을 기반으로 프로덕트 개선에 기여하는 분석가로 발전  
