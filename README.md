# IMBK_langgraph
랭그래프를 활용한 운동 계획 제안 모델

## 기간:

2026.05.13

## 기술 스택:

<img width="491" height="107" alt="image" src="https://github.com/user-attachments/assets/d0307e10-a9d4-4270-8342-e91d9b2c6109" />

<img width="359" height="29" alt="image" src="https://github.com/user-attachments/assets/628d2fa9-46d1-4674-b3d7-8920af4e0995" />

Ollama, PromptTemplate(LangChain), TypedDict, StateGraph(LangGraph), exaone3.5:2.4b을 사용했습니다.

## 멀티 에이전트

<img width="1057" height="280" alt="image" src="https://github.com/user-attachments/assets/1b068b18-7cb9-4f72-b2c4-19767164e9cb" />

- 추출 에이전트: 핵심 증상만 추출하여 데이터만 남기는 정제 역할을 수행

<img width="795" height="271" alt="image" src="https://github.com/user-attachments/assets/ee4f0325-410b-41ce-a059-1f9f10762f80" />

- 후보 에이전트: 해결책이 될 운동 리스트를 매칭하여 도출하는 역할을 수행

<img width="872" height="493" alt="image" src="https://github.com/user-attachments/assets/ed8a1cc4-424b-4b24-aded-6f81f7641456" />

- 답변 에이전트: 사용자가 읽기 편한 개조식 형태의 답변으로 도출하는 역할을 수행

## 그래프 구조

<img width="115" height="432" alt="image" src="https://github.com/user-attachments/assets/1814b326-017b-4968-b353-3197c9879346" />

## 결과

<img width="1700" height="628" alt="image" src="https://github.com/user-attachments/assets/0a7732ef-f881-44fe-8c8f-a47127d5462d" />
