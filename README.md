# WindowMirror 다운로드

macOS와 Windows에서 앱 화면을 다른 모니터에 표시하는 미러링 프로그램입니다. 이 저장소에는 배포 파일과 안내만 제공합니다.

## 다운로드

[최신 버전과 설치 안내](https://github.com/gomting/WindowMirror-Downloads/releases/latest)

릴리스의 **Assets**에서 운영체제에 맞는 파일을 선택하세요.

- **WindowMirror-macOS-…-arm64.zip**: Apple Silicon Mac, macOS 14 이상
- **WindowMirror-Windows-…-x64.zip**: Windows x64, 별도 .NET 설치 불필요

압축을 풀고 실행 중인 WindowMirror를 종료한 뒤 앱을 교체하세요. 기존 사용자 설정 파일은 유지됩니다. macOS 캡처에는 화면 기록 권한이 필요합니다. 현재 테스트 배포이며 macOS 개발자 배포 서명·공증과 Windows 코드서명이 없어 운영체제에서 실행을 확인하거나 차단할 수 있습니다.

## 앱 안에서 업데이트 받기

1.4.0부터 **업데이트 → 업데이트 확인·다운로드…**를 지원합니다. 자동 다운로드는 기본으로 켜져 있으며 미러링 중에는 대기합니다. 다운로드 완료 후 **받은 업데이트 파일 열기…**를 선택해 파일을 찾을 수 있습니다. 앱 교체와 재시작은 수동으로 진행합니다.

1.3.7 이하 버전은 1.4.0 이상을 한 번 직접 설치해야 합니다.

## 절전 캡처

macOS는 기본 절전 캡처로 최대 약 1080p·24fps를 사용합니다. 영역과 표시 크기는 유지되며 세부 선명도가 필요하면 해당 옵션을 끌 수 있습니다. Windows는 DWM/GPU 출력을 유지하며 절전 FPS 제한은 호환성 모드에 적용됩니다.

실제 Photoshop 작업과 Windows GPU 환경에 따라 동작·성능이 달라질 수 있습니다.
