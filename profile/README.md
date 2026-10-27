<p align="center">
  <img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/banner.svg" alt="Autonomous Data Platform — 자율주행 데이터의 검색부터 학습·검증까지" width="100%">
</p>

<p align="center">
  <a href="https://data.intellectus.software/"><img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/portal-link.svg" alt="포털 바로가기" width="192" height="50"></a>
  <a href="#구성요소별-저장소"><img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/repositories-link.svg" alt="저장소 둘러보기" width="206" height="50"></a>
</p>

# Autonomous Data Platform

**실측·합성·공개 데이터를 연결하는 오픈소스 플랫폼**

여러 곳에 흩어진 자율주행 데이터의 메타데이터와 의미 정보를 연결해 필요한 장면을 찾고, 확인하고, 활용할 데이터셋으로 구성합니다. 지식그래프의 객체·환경·관계 조건과 벡터 검색의 의미적 유사도를 결합해 AI 학습과 자율주행 검증에 필요한 데이터 탐색을 지원합니다.

An open-source platform for discovering, exploring, and preparing autonomous-driving data for AI training and validation.

<img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/capabilities.svg" alt="데이터 통합, 의미 기반 검색, 계층형 탐색, 활용과 공유" width="100%">

## 필요한 데이터를 찾고 활용하는 흐름

실측 센서 데이터, 시뮬레이션 기반 합성 데이터, 공개 데이터셋의 구조와 의미를 연결합니다. 검색 결과는 Dataset에서 Clip·Scene으로 범위를 좁혀 확인하고 시각화·패키징·공유로 이어집니다.

<img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/data-flow.svg" alt="실측·합성·공개 데이터에서 메타데이터 관리, KG·벡터 검색, Dataset·Clip·Scene 탐색을 거쳐 시각화·패키징·공유로 이어지는 구성 개요" width="100%">

“야간 교차로에서 보행자와 차량이 등장하는 장면”처럼 필요한 상황을 탐색하는 흐름을 지향합니다. 실제 질의 방식, 지원 기능과 데이터 제공 범위는 각 서비스와 저장소의 안내를 확인해 주세요.

## 데이터 활용 목적에 맞춰

<img src="https://raw.githubusercontent.com/AutonomousDataPlatform/.github/main/profile/assets/use-cases.svg" alt="AI 학습 데이터 탐색, 자율주행 검증, 데이터 재활용" width="100%">

| 활용 목적 | 사용 흐름 |
| --- | --- |
| AI 학습 데이터 탐색 | 필요한 객체와 상황을 기준으로 데이터 후보군 구성 |
| 자율주행 검증 | 특정 환경·시나리오에 해당하는 클립과 장면 탐색 |
| 데이터 재활용 | 검색하고 확인한 데이터를 활용 목적에 맞게 재구성 |

## 구성요소별 저장소

설치 방법과 공개 구현 범위는 각 저장소의 README와 릴리스 문서를 확인해 주세요.

| 저장소 | 역할 |
| --- | --- |
| [MetaPipeline](https://github.com/AutonomousDataPlatform/MetaPipeline) | 메타데이터 처리 파이프라인 |
| [local-knowledge-graph](https://github.com/AutonomousDataPlatform/local-knowledge-graph) | 로컬 지식그래프 |
| [information-retrieval](https://github.com/AutonomousDataPlatform/information-retrieval) | 정보 탐색 |
| [auto-labeling-api](https://github.com/AutonomousDataPlatform/auto-labeling-api) | 자동 라벨링 API |
| [Graph-search](https://github.com/AutonomousDataPlatform/Graph-search) | 그래프 검색 |
| [fabric-data-pipeline-zenoh](https://github.com/AutonomousDataPlatform/fabric-data-pipeline-zenoh) | 데이터 파이프라인 연계 |
| [AutonomousDrivingMetaData](https://github.com/AutonomousDataPlatform/AutonomousDrivingMetaData) | 자율주행 메타데이터 |

## 시작하기

[BigData Portal](https://data.intellectus.software/)에서 데이터와 활용 흐름을 살펴보고, 사용하려는 구성요소의 저장소에서 실행 환경과 설정을 확인하세요. 각 저장소의 최소 예제로 입출력을 확인한 뒤 필요한 데이터와 모델을 준비합니다. 구성요소별 공개 기능과 연계 범위는 버전에 따라 다를 수 있습니다.

## 함께 개선하기

오류 제보와 개선 제안은 관련 저장소의 Issues를 이용해 주세요. 코드와 문서의 변경은 Pull Request로 제안할 수 있습니다. 사용 버전, 실행 환경과 재현 절차를 함께 남겨 주세요.

## 라이선스와 데이터 이용

소프트웨어의 이용 조건은 각 저장소의 LICENSE 및 제3자 고지를 따릅니다. 데이터셋·모델 가중치·이미지 등에는 각각의 이용 조건이 적용됩니다.

<sub>본 플랫폼은 과학기술정보통신부·정보통신기획평가원의 자율주행 빅데이터 과제(RS-2023-00235293) 지원으로 개발되었습니다.</sub>
