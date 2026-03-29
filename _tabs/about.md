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

![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white) ![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black) ![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white) ![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white) ![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white) ![OpenCV](https://img.shields.io/badge/OpenCV-5C3EE8?style=flat-square&logo=opencv&logoColor=white) ![Jetson](https://img.shields.io/badge/Jetson-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Machine Vision Camera](https://img.shields.io/badge/Machine_Vision_Camera-333333?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB2aWV3Qm94PSIwIDAgMjQgMjQiIHhtbG5zPSJodHRwOi8vd3d3LnczLm9yZy8yMDAwL3N2ZyIgZmlsbD0id2hpdGUiPjxnIGlkPSJTVkdSZXBvX2ljb25DYXJyaWVyIj4gPHBhdGggZD0iTTE4LjE1LDQuOTRBMi4wOSwyLjA5LDAsMCwwLDE3LDUuMmwtOC42NSw1YTIsMiwwLDAsMC0uNzMsMi43NGwxLjUsMi41OWEyLDIsMCwwLDAsMi43My43NGwxLjgtMWEyLjQ5LDIuNDksMCwwLDAsMS4xNiwxVjE4YTIsMiwwLDAsMCwyLDJIMjJWMThIMTYuODFWMTYuMjdBMi40OSwyLjQ5LDAsMCwwLDE4LDEyLjczbDIuNTMtMS40NmEyLDIsMCwwLDAsLjc0LTIuNzRsLTEuNS0yLjU5YTIsMiwwLDAsMC0xLjU5LTFNNi4yMiwxMy4xNywyLDEzLjg3bC43NSwxLjMsMiwzLjQ2Ljc1LDEuMywyLjcyLTMuM1oiPjwvcGF0aD4gPHJlY3Qgd2lkdGg9IjI0IiBoZWlnaHQ9IjI0IiBmaWxsPSJub25lIj48L3JlY3Q+IDwvZz48L3N2Zz4=&logoColor=white&logoWidth=14)

#### Intermediate

![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white) ![C#](https://img.shields.io/badge/C%23-512BD4?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik0xMiAwQTEyIDEyIDAgMDAwIDEyYTEyIDEyIDAgMDAxMiAxMiAxMiAxMiAwIDAwMTItMTJBMTIgMTIgMCAwMDEyIDB6bS0xLjE1IDE3LjA3bC0uOTItLjkyTDcuNDcgMTJsMi40Ni00LjE1LjkyLS45MiAxLjg4IDEuMUwxMC44IDEybDEuOTMgMy45N3ptNi4xMi0zLjQ3aC0xLjV2MS41aC0xdi0xLjVoLTEuNXYtMWgxLjV2LTEuNWgxdjEuNWgxLjV6bTItMS41aC0xLjV2MS41aC0xdi0xLjVIMTR2LTFoMS45N3YtMS41aDF2MS41aDEuNXoiLz48L3N2Zz4K&logoColor=white&logoWidth=14) ![AWS](https://img.shields.io/badge/AWS-%23FF9900?style=flat-square&logo=data:image/svg+xml;base64,PHN2ZyB4bWxucz0iaHR0cDovL3d3dy53My5vcmcvMjAwMC9zdmciIHZpZXdCb3g9IjAgMCAyNCAyNCIgZmlsbD0id2hpdGUiPjxwYXRoIGQ9Ik02Ljc2MyAxMC4wMzZjMCAuMjk2LjAzMi41MzUuMDg4LjcxLjA2NC4xNzYuMTQ0LjM2OC4yNTYuNTc2LjA0LjA2My4wNTYuMTI3LjA1Ni4xODMgMCAuMDgtLjA0OC4xNi0uMTUyLjI0bC0uNTAzLjMzNWEuMzgzLjM4MyAwIDAxLS4yMDguMDcyYy0uMDggMC0uMTYtLjA0LS4yMzktLjExMmEyLjQ3IDIuNDcgMCAwMS0uMjg3LS4zNzUgNi4xOCA2LjE4IDAgMDEtLjI0OC0uNDcxYy0uNjIyLjczNC0xLjQwNSAxLjEwMS0yLjM0NyAxLjEwMS0uNjcgMC0xLjIwNS0uMTkxLTEuNTk2LS41NzQtLjM5MS0uMzg0LS41OS0uODk0LS41OS0xLjUzMyAwLS42NzguMjM5LTEuMjMuNzI2LTEuNjQ0LjQ4Ny0uNDE1IDEuMTMzLS42MjMgMS45NTUtLjYyMy4yNzIgMCAuNTUxLjAyNC44NDYuMDY0LjI5Ni4wNC42LjEwNC45MTguMTc2di0uNTgzYzAtLjYwNy0uMTI3LTEuMDMtLjM3NS0xLjI3Ny0uMjU1LS4yNDgtLjY4Ni0uMzY3LTEuMy0uMzY3LS4yOCAwLS41NjguMDMyLS44NjMuMTA0LS4yOTYuMDcyLS41ODMuMTYtLjg2Mi4yNzJhMi4yODcgMi4yODcgMCAwMS0uMjguMTA0LjQ4OC40ODggMCAwMS0uMTI3LjAyNGMtLjExMiAwLS4xNjgtLjA4LS4xNjgtLjI0N3YtLjM5MWMwLS4xMjguMDE2LS4yMjQuMDU2LS4yOGEuNTk3LjU5NyAwIDAxLjIyNC0uMTY3Yy4yNzktLjE0NC42MTQtLjI2NCAxLjAwNS0uMzZhNC44NCA0Ljg0IDAgMDExLjI0Ni0uMTUyYy45NSAwIDEuNjQ0LjIxNiAyLjA5MS42NDcuNDQuNDMuNjYyIDEuMDg1LjY2MiAxLjk2M3YyLjU4NnptLTMuMjQgMS4yMTRjLjI2MyAwIC41MzQtLjA0OC44MjItLjE0NC4yODctLjA5Ni41NDMtLjI3MS43NTgtLjUxLjEyOC0uMTUyLjIyNC0uMzIuMjcyLS41MTIuMDQ3LS4xOTEuMDgtLjQyMy4wOC0uNjk0di0uMzM1YTYuNjYgNi42NiAwIDAwLS43MzUtLjEzNiA2LjAyIDYuMDIgMCAwMC0uNzUtLjA0OGMtLjUzNSAwLS45MjYuMTA0LTEuMTkuMzItLjI2My4yMTUtLjM5LjUxOC0uMzkuOTE3IDAgLjM3NS4wOTUuNjU1LjI5NS44NDYuMTkxLjIuNDcuMjk2LjgzOC4yOTZ6bTYuNDEuODYyYy0uMTQ0IDAtLjI0LS4wMjQtLjMwNC0uMDgtLjA2NC0uMDQ4LS4xMi0uMTYtLjE2OC0uMzExTDcuNTg2IDUuNTVhMS4zOTggMS4zOTggMCAwMS0uMDcyLS4zMmMwLS4xMjguMDY0LS4yLjE5MS0uMmguNzgzYy4xNTEgMCAuMjU1LjAyNS4zMS4wOC4wNjUuMDQ4LjExMy4xNi4xNi4zMTJsMS4zNDIgNS4yODQgMS4yNDUtNS4yODRjLjA0LS4xNi4wODgtLjI2NC4xNTEtLjMxMmEuNTQ5LjU0OSAwIDAxLjMyLS4wOGguNjM4Yy4xNTIgMCAuMjU2LjAyNS4zMi4wOC4wNjMuMDQ4LjEyLjE2LjE1MS4zMTJsMS4yNjEgNS4zNDggMS4zODEtNS4zNDhjLjA0OC0uMTYuMTA0LS4yNjQuMTYtLjMxMmEuNTIuNTIgMCAwMS4zMTEtLjA4aC43NDNjLjEyNyAwIC4yLjA2NS4yLjIgMCAuMDQtLjAwOS4wOC0uMDE3LjEyOGExLjEzNyAxLjEzNyAwIDAxLS4wNTYuMmwtMS45MjMgNi4xN2MtLjA0OC4xNi0uMTA0LjI2NC0uMTY4LjMxMmEuNTQ5LjU0OSAwIDAxLS4zMi4wOGgtLjY4N2MtLjE1MSAwLS4yNTUtLjAyNC0uMzE5LS4wOC0uMDYzLS4wNTYtLjEyLS4xNi0uMTUtLjMyTDEzLjUxNCA2LjlsLTEuMjM4IDUuMTRjLS4wNC4xNi0uMDg3LjI2NC0uMTUuMzItLjA2NC4wNTYtLjE3Ni4wOC0uMzIuMDh6bTEwLjI1Ni4yMTVjLS40MTUgMC0uODMtLjA0OC0xLjIyOS0uMTQzLS4zOTktLjA5Ni0uNzEtLjItLjkxOC0uMzItLjEyOC0uMDcxLS4yMTYtLjE1MS0uMjQ4LS4yMTVhLjUxLjUxIDAgMDEtLjA0OC0uMjI0di0uNDA3YzAtLjE2Ny4wNjQtLjI0Ny4xODMtLjI0Ny4wNDggMCAuMDk2LjAwOC4xNDQuMDI0cy4xMi4wNjQuMi4xMTJjLjI3MS4xNTIuNTY2LjI3Mi44ODYuMzYuMzIuMDg3LjYzLjEyNy45NS4xMjcuNTAzIDAgLjg5NC0uMDg4IDEuMTY1LS4yNjRhLjg2Ljg2IDAgMDAuNDE1LS43NTguNzc3Ljc3NyAwIDAwLS4yMTUtLjU1OWMtLjE0NC0uMTUxLS40MTUtLjI4Ny0uODA2LS40MTVsLTEuMTU3LS4zNmMtLjU4My0uMTgzLTEuMDE0LS40NTQtMS4yNzctLjgxM2ExLjkwMiAxLjkwMiAwIDAxLS40LTEuMTU4YzAtLjMzNS4wNzMtLjYzLjIxNi0uODg2LjE0NC0uMjU1LjMzNS0uNDc5LjU3NS0uNjU0LjI0LS4xODQuNTEtLjMyLjgzLS40MTVhMy42NiAzLjY2IDAgMDExLjAxMy0uMTM2Yy4xNzUgMCAuMzU5LjAwOC41MzUuMDMyLjE4My4wMjQuMzUuMDU2LjUxOC4wODguMTYuMDQuMzEyLjA4LjQ1NS4xMjcuMTQ0LjA0OC4yNTYuMDk2LjMzNi4xNDRhLjY5LjY5IDAgMDEuMjQuMi40My40MyAwIDAxLjA3MS4yNjN2LjM3NWMwIC4xNjgtLjA2NC4yNTYtLjE4NC4yNTZhLjgzLjgzIDAgMDEtLjMwMy0uMDk2IDMuNjUyIDMuNjUyIDAgMDAtMS41MzItLjMxMWMtLjQ1NSAwLS44MTUuMDcxLTEuMDYyLjIyMy0uMjQ4LjE1Mi0uMzc1LjM4My0uMzc1LjY5NCAwIC4yMjQuMDguNDE2LjI0LjU2Ny4xNTkuMTUyLjQ1NC4zMDQuODc3LjQ0bDEuMTM0LjM1OGMuNTc0LjE4NC45OS40NCAxLjIzNy43NjcuMjQ4LjMyOC4zNzUuNzAzLjM3NSAxLjExOCAwIC4zNDQtLjA3Mi42NTUtLjIwNy45MjZhMi4xNjYgMi4xNjYgMCAwMS0uNTc1LjY5NWMtLjI0Ny4yLS41NDMuMzQzLS44ODYuNDQ3LS4zNi4xMTEtLjc0Mi4xNjctMS4xNS4xNjd6Ii8+PHBhdGggZD0iTTIxLjY5OCAxNi4yMDdjLTIuNjI2IDEuOTQtNi40NDIgMi45Ny05LjcyMiAyLjk3LTQuNTk4IDAtOC43NC0xLjctMTEuODctNC41MjYtLjI0Ny0uMjIzLS4wMjQtLjUyNy4yNzEtLjM1MSAzLjM4NCAxLjk2MyA3LjU1OSAzLjE1MyAxMS44NzcgMy4xNTMgMi45MTQgMCA2LjExNC0uNjA3IDkuMDYtMS44NTIuNDM5LS4yLjgxNC4yODcuMzg0LjYwNnoiLz48cGF0aCBkPSJNMjIuNzkyIDE0Ljk2MWMtLjMzNi0uNDMtMi4yMi0uMjA3LTMuMDc0LS4xMDMtLjI1NS4wMzItLjI5NS0uMTkyLS4wNjMtLjM2IDEuNS0xLjA1MyAzLjk2Ny0uNzUgNC4yNTQtLjM5OS4yODcuMzYtLjA4IDIuODI2LTEuNDg1IDQuMDA3LS4yMTUuMTg0LS40MjMuMDg4LS4zMjctLjE1MS4zMTktLjc5IDEuMDMtMi41Ny42OTUtMi45OTR6Ii8+PC9zdmc+Cg==&logoColor=white&logoWidth=14) ![GCP](https://img.shields.io/badge/GCP-4285F4?style=flat-square&logo=googlecloud&logoColor=white) ![Firebase](https://img.shields.io/badge/Firebase-DD2C00?style=flat-square&logo=firebase&logoColor=white) ![Next.js](https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=next.js&logoColor=white) ![React](https://img.shields.io/badge/React-61DAFB?style=flat-square&logo=react&logoColor=black) ![Three.js](https://img.shields.io/badge/Three.js-000000?style=flat-square&logo=three.js&logoColor=white) ![TensorFlow](https://img.shields.io/badge/TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white) ![TensorRT](https://img.shields.io/badge/TensorRT-76B900?style=flat-square&logo=nvidia&logoColor=white) ![Open3D](https://img.shields.io/badge/Open3D-1890FF?style=flat-square&logo=open3d&logoColor=white)

#### Beginner

![ROS2](https://img.shields.io/badge/ROS2-22314E?style=flat-square&logo=ros&logoColor=white) ![Qt](https://img.shields.io/badge/Qt-41CD52?style=flat-square&logo=qt&logoColor=white) ![PHP](https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white)
