---
# the default layout is 'page'
icon: fas fa-info-circle
order: 4
published: false
---

## 이지호 (Jiho Lee)

컴퓨터 비전과 3D 데이터 처리, AI 응용 분야에서 End-to-End 시스템을 설계하고 구현합니다.

---

## 경력

### ㈜평행공간 (2025.08 - 현재)

**연구원** · P-Engine — 포인트 클라우드 기반 3D 메시 자동 생성 플랫폼

#### 3D 지오메트리 엔진
- 포인트 클라우드를 텍스처가 적용된 고품질 3D 메시(GLB)로 자동 변환하는 C++ 엔진 개발
- 청크 기반 스트리밍 아키텍처로 수억 개 포인트를 메모리 효율적으로 처리
- 노말 정렬, UV 매핑, 텍스처 베이킹, 바닥/벽/객체 자동 분류 기능 구현

#### AI 3D 세그멘테이션
- 3D 메시를 멀티뷰 렌더링 후 2D 세그멘테이션하고 3D로 역투영하는 파이프라인 개발
- 24방향 자동 렌더링 및 투표 기반 3D 라벨링으로 정확도 확보

#### 웹 SaaS 서비스
- 크레딧 기반 과금 및 결제 시스템이 포함된 SaaS 웹 서비스 설계 및 구현
- 클라우드 서버리스 환경에서 Import → Reconstruction → Export 비동기 처리 파이프라인 구축

#### 데스크톱 도구 및 Revit 플러그인
- 다양한 포맷(PLY/E57/LAS/LAZ) 입력을 지원하는 데스크톱 처리 도구 개발 및 단일 EXE 배포
- Autodesk Revit 2021~2026 6개 버전 호환 플러그인 개발

---

### ㈜엠시스랩 (2019.12 - 2024.01)

**연구원** · AI ADAS 및 스마트팩토리 비전검사 장비 개발

#### 터미널단자 핀 삽입 검출 시스템
- 딥러닝 기반 객체 검출을 활용한 실시간 검사 시스템 구축
- PLC 연동 지연시간 1ms 미만 달성, VPN 기반 원격 개발 환경 구축

#### AI 블랙박스
- 실시간 사고 감지 및 서버 전송 시스템 개발
- 모델 최적화로 실시간 처리 성능 확보, 객체 검출과 차선 검출 동시 처리

#### LDM Visualizer
- 실시간 데이터를 3D로 시각화하는 웹 기반 뷰어 개발
- 위성지도와 3D 객체의 통합 시각화

#### GPU 서버 팜
- 8~10대 GPU 서버 구성 및 운영
- 관제 대시보드 구현, 장애 복구 및 유지보수

---

## 학력

### 충북대학교 산업인공지능학과 (석사, 2021.03 - 2023.02)
- 학점: 4.13 / 4.5
- 논문: 오토인코더를 이용한 용융 적층 모델링 3D 프린터의 출력 이상 감지 [[Link](https://chungbuk.dcollection.net/common/orgView/200000771904)]

### 충북대학교 전자공학과 (학사, 2016.03 - 2020.02)
- 학점: 3.83 / 4.5

---

## 기술 스택

#### Advanced

<img height="20" src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python"> <img height="20" src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript"> <img height="20" src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript"> <img height="20" src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker"> <img height="20" src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch"> <img height="20" src="https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white" alt="OpenCV"> <img height="20" src="https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="Jetson"> <img height="20" src="https://img.shields.io/badge/Machine_Vision_Camera-333333?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZmlsbD0id2hpdGUiPjxnIGlkPSJTVkdSZXBvX2ljb25DYXJyaWVyIj4gPHBhdGggZD0iTTE4LjE1LDQuOTRBMi4wOSwyLjA5LDAsMCwwLDE3LDUuMmwtOC42NSw1YTIsMiwwLDAsMC0uNzMsMi43NGwxLjUsMi41OWEyLDIsMCwwLDAsMi43My43NGwxLjgtMWEyLjQ5LDIuNDksMCwwLDAsMS4xNiwxVjE4YTIsMiwwLDAsMCwyLDJIMjJWMThIMTYuODFWMTYuMjdBMi40OSwyLjQ5LDAsMCwwLDE4LDEyLjczbDIuNTMtMS40NmEyLDIsMCwwLDAsLjc0LTIuNzRsLTEuNS0yLjU5YTIsMiwwLDAsMC0xLjU5LTFNNi4yMiwxMy4xNywyLDEzLjg3bC43NSwxLjMsMiwzLjQ2Ljc1LDEuMywyLjcyLTMuM1oiPjwvcGF0aD4gPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIj48L3JlY3Q+IDwvZz48L3N2Zz4=&logoColor=white" alt="Machine Vision Camera">

#### Intermediate

<img height="20" src="https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++"> <img height="20" src="https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAwQTEyIDEyIDAgMDAwIDEyYTEyIDEyIDAgMDAxMiAxMiAxMiAxMiAwIDAwMTItMTJBMTIgMTIgMCAwMDEyIDB6bS0xLjE1IDE3LjA3bC0uOTItLjkyTDcuNDcgMTJsMi40Ni00LjE1LjkyLS45MiAxLjg4IDEuMUwxMC44IDEybDEuOTMgMy45N3ptNi4xMi0zLjQ3aC0xLjV2MS41aC0xdi0xLjVoLTEuNXYtMWgxLjV2LTEuNWgxdjEuNWgxLjV6bTItMS41aC0xLjV2MS41aC0xdi0xLjVIMTR2LTFoMS45N3YtMS41aDF2MS41aDEuNXoiLz48L3N2Zz4K&logoColor=white&logoWidth=14" alt="C#"> <img height="20" src="https://img.shields.io/badge/AWS-232F3E?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xOC43NSAxMS4zNWE0LjMyIDQuMzIgMCAwMC0zLjkzLTQuMDMgNi4wMiA2LjAyIDAgMDAtMTEuMyAyLjA2QTQuNDggNC40OCAwIDAwNSAxOGgxMy41YTMuNzUgMy43NSAwIDAwLjI1LTYuNjV6Ii8+PC9zdmc+Cg==&logoColor=white&logoWidth=14" alt="AWS"> <img height="20" src="https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white" alt="GCP"> <img height="20" src="https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white" alt="Firebase"> <img height="20" src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white" alt="Next.js"> <img height="20" src="https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black" alt="React"> <img height="20" src="https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white" alt="Three.js"> <img height="20" src="https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white" alt="TensorFlow"> <img height="20" src="https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white" alt="TensorRT"> <img height="20" src="https://img.shields.io/badge/Open3D-1C1412?style=flat-square&logo=open3d&logoColor=white" alt="Open3D">

#### Beginner

<img height="20" src="https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white" alt="ROS2"> <img height="20" src="https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white" alt="Qt"> <img height="20" src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP">
