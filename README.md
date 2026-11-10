# 곁 · Gyeot Releases

곁의 Windows 설치 파일과 서명된 업데이트 정보를 제공하는 배포 전용 저장소입니다. 앱 소스와 분리되어 있습니다.

## Windows x64 · Tauri 0.5.0 시험판

[설치 파일 다운로드](https://github.com/ysshxd/Gyeot-Releases/releases/download/v0.5.0/Gyeot-Setup-0.5.0-x64.exe) · [최신 릴리스](https://github.com/ysshxd/Gyeot-Releases/releases/latest)

Tauri/Rust 기반 설치판입니다. 수동 설치에는 exe 파일 하나만 필요합니다. 모델 파일과 Ollama는 포함되지 않습니다. WebView2가 없는 PC에서는 설치 중 인터넷 연결이 필요합니다.

기존 Electron 앱을 자동 전환하지 않습니다. 기존 곁이 설치되어 있다면 종료·제거 후 새 설치 파일을 실행하세요. 구형 대화·설정·로그인을 자동 이전하지 않습니다. Tauri 설치 이후에는 다음 Tauri 버전의 서명 업데이트를 받을 수 있습니다.

CPU 최적화와 실제 계정·음악·마이크·다른 PC 검증을 이어가는 시험판입니다. 세 로컬 모델의 품질은 별도 검증 중입니다.

## 배포 파일

- `Gyeot-Setup-버전-x64.exe`: Windows x64 전체 설치 파일
- `latest-tauri.yml`, `proof-tauri-버전.json`: Tauri 전용 서명 업데이트 정보
- `SHA256SUMS.txt`: 배포 파일 체크섬

앱은 배포 서명과 설치 파일 해시·크기·앱 식별자를 검증합니다. Windows Authenticode 서명과는 별개이며 SmartScreen 경고가 표시될 수 있습니다. 기존0.4.x 릴리스는 과거 Electron 배포 기록으로 남겨두며 Tauri 자동 전환 경로로 사용하지 않습니다.

향후 곁 홈페이지도 이 저장소의 공개 설치 파일을 연결합니다.