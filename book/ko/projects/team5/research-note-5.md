# 5차 프로젝트 연구일지

## 기본 정보

- **팀명**: AICS
- **프로젝트명**: AI Courtroom Simulator (AI 법정 시뮬레이터)
- **주차**: 5차

## 팀 구성원 활동 요약

| 이름    | 역할   | 주요 활동                | 다음 주 계획             |
| ------- | ------ | ------------------------ | ------------------------ |
|  홍성관 | 팀장, NLP모델 및 시스템 설계 | • 프로젝트 요구사항 분석 <br> • 법정 시뮬레이션 시나리오 초안 작성 <br> • 팀원 교육 | • 데이터셋 수집 및 병합 <br> • 백엔드 및 프론트엔드 코드 수정 |
|  박진우 | 웹 개발자 | • 백엔드 구조 설계 <br> • 데이터셋 초기 세팅 | • 모델 학습에 필요한 데이터 준비 및 병합 |
|  김현서 | UI 디자이너 | • 사용자 인터페이스 초안 작성 <br> | • RAG 및 Streamlit 코드 분석 |
|  김형규 | 데이터 엔지니어 | • 법률 및 판례 수집 <br> • 법률 용어 사전 구성 <br> | • 데이터셋 json파일로 생성 <br> • 모델 학습에 필요한 데이터 준비 |
|  부윤철 | 데이터 엔지니어 | • 법률 및 판례 수집 <br> • 법률 용어 사전 구성 <br> | • 모델 학습에 필요한 데이터 준비 |


## 주간 목표 달성도

| 목표    | 상태               | 비고        |
| ------- | ------------------ | ----------- |
| 주제 선정 및 제안서 작성(AI 법정 시뮬레이터) | 완료 | 제안서 최종 승인 |
| 시뮬레이션 주제 선정 | 완료 | 해킹 및 개인정보 유출, 불법적인 데이터 수집, 사이버 명예훼손|
| RAG 관련 학습 | 진행중 | RAG를 시스템에 적용하는 방법 구체화 예정 |
| Langchain 관련 학습 | 진행중 | Langchain을 시스템에 적용하는 방법 구체화 예정 |
| 법률 데이터셋 조사 | 진행중 | • 3개의 주제에 관련된 법률과 판례 조사 <br> • 데이터 조사가 완료된 인원들의 데이터 병합 |
| 시뮬레이션 코드 분석 | 진행중 | • RAG 및 Streamlit 코드 분석 (김현서)
| 데이터셋 병합(3개 주제) | 진행중 | • 현재 2개 주제 병합 <br> • json파일 형식으로 수정

## 주요 성과 및 결과물

1. RAG와 Langchain을 사용한 프로젝트를 통해 학습 (Open AI api를 사용하여 RAG를 통한 논문 내용 Q&A 시스템 구축)
2. 세 명의 데이터 병합본

## 기술적 도전 및 해결 방안

1. **도전 1**: json 파일 형식에 대한 지식 부족(데이터셋)
   - 해결 방안: json 파일에 관한 관련 자료를 통해 학습
2. **도전 2**: UI에 관한 내용 이해 및 학습 부족
   - 해결 방안: streamlit을 사용한 UI 구현 코드 분석

## 학습 내용

   1. RAG 시스템을 사용한 코드 분석 및 학습
      - 주요 내용: RAG 시스템이 어떻게 구동되고 사용되는지 학습
      - 적용 방안: 논문 내용 Q&A 시스템을 통해 적용 방안 실습

   2. Open AI API 사용법 숙지
      - 주요 내용: Open AI API를 사용하여 사용자의 질문에 대한 키워드 추출 및 검색 결과 도출 방법 학습
      - 적용 방안: 추출된 키워드를 기반으로 외부 검색 엔진이나 내부 데이터베이스와 연동하여 적절한 검색 결과를 도출

## 다음 주 계획

1. 법률 및 판례 데이터 종합본 json파일로 변환
2. 벡엔드 및 프론트엔드 코드 수정

## 기타 특이사항

- 데이터 부족으로 인해 데이터 수집 과정 연장 
- RAG 및 Streamlit 코드 분석 요청

## 팀 미팅 요약

- **일시**: 2024년 9월 19일
- **참석자**: 홍성관, 박진우, 김현서, 김형규
- **주요 논의 사항**:
  1. 데이터셋 양식 변경(json)
- **결정 사항**:
  1. 데이터 양 확대
  2. 백엔드 코드수정

---

작성일: 2024-09-26
작성자: 홍성관