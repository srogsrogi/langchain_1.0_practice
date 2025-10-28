# Langchain 1.0 실습

## 개요

- 전에 0버전 써봤을 때는 너무 고수준화돼있어서 중간 과정도 잘 모르겠고 답답했는데

- 1.0은 많이 나아졌다고 해서 공식 문서 기반으로 배워보기로 함

  https://docs.langchain.com/oss/python/langchain/quickstart

- 문법 많이 바뀌었으니 0버전 문법들 섞어 쓰지 않도록 주의



## 환경 세팅

- Conda 가상환경 사용
- `requirements.txt` 또는 `environment.yml`로 환경 재현

### 환경 변수

- `dotenv` 사용, `.env` 파일로 관리
- 필요한 환경 변수 목록
  - OPENAI_API_KEY
  - EXCHANGE_RATE_HOST_API_KEY

## 학습 내용

- Langchain pipeline 설계 기초

  - agent 구축

  - RAG, 함수 실행 등 multi tool 설계

- 공식 문서 튜토리얼 코드를 기반으로 순차적 학습
  - 공식 문서는 날씨 조회 기능을 기반으로 작성되어 있으나
  - 직접 고민하고 설계해보기 위해 환율 검색 및 변환 등을 수행하는 agentic LLM 설계