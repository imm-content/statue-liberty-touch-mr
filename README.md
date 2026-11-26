# 내 책상 위의 자유의 여신상 | 손가락 조작 MR

실행 주소: https://imm-content.github.io/statue-liberty-touch-mr/

## 파일 구성
- index.html: 직접 배치 방식
- statue_of_liberty_1.glb: 기존 파일 유지
- README.md: 사용 안내

## 실행 방법
1. WebXR immersive-ar 및 DOM Overlay를 지원하는 Android Chrome에서 실행합니다.
2. AR 시작을 누르고 카메라 권한을 허용합니다.
3. 화면 중앙의 +를 원하는 위치에 맞춥니다.
4. 배치 버튼을 누르면 카메라 앞 0.8m 지점에 모형 중심을 배치합니다.
5. 한 손가락으로 회전, 두 손가락으로 이동·확대·축소합니다.
6. 재배치를 누르면 모형이 숨겨지고 새 위치에서 배치할 수 있습니다.

## 변경 및 제한 사항
- hit-test 및 녹색 원 대기를 제거했습니다. +는 단순 조준 표시입니다.
- GLB 로딩 및 유효한 XR 카메라 자세가 확보되면 배치 버튼이 활성화됩니다.
- 실제 표면 높이는 측정하지 않습니다. 모형이 떠 있거나 표면에 파묻힐 수 있으며 두 손가락 이동으로 조정할 수 있습니다.
- 배치 후 XR 기준 공간 좌표를 유지합니다. 추적 품질에 따라 위치가 달라질 수 있습니다.
- DOM Overlay가 없는 환경은 직접 배치 AR을 지원하지 않습니다. 일반 3D 미리보기를 사용합니다.
- JavaScript 문법 검사 완료. 실제 스마트폰 동작 및 배치 시간은 미검증입니다.

## 3D 모델 출처
[statue_of_liberty (1) — tech.service.allwe](https://sketchfab.com/3d-models/statue-of-liberty-1-b3105217169b4ebbabeefb1d97e3696c) · [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/)
