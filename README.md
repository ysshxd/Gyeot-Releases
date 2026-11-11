# 곁 · Gyeot Releases

곁의 Windows 설치 파일과 서명된 업데이트 정보를 제공하는 배포 전용 저장소입니다.

## Windows x64 · Tauri 0.5.2

[설치 파일 다운로드](https://github.com/ysshxd/Gyeot-Releases/releases/download/v0.5.2/Gyeot-Setup-0.5.2-x64.exe) · [최신 릴리스](https://github.com/ysshxd/Gyeot-Releases/releases/latest)

수동 설치에는 exe 파일 하나만 필요합니다. 모델 파일과 Ollama는 포함되지 않습니다. WebView2가 없는 PC에서는 설치 중 인터넷 연결이 필요합니다.

0.5.2는 성능 화면의 ‘사용 중인 앱’ 카드 하단 빛 효과를 제거해 카드들의 톤을 맞췄습니다. 이전 상주 부하 개선도 포함합니다. 자세한 변경과 검증 범위는 릴리스 안내를 확인하세요.

기존 Tauri 0.5.0은 서명된 자동 업데이트를 받을 수 있습니다. Electron 0.4.x 설치판의 자동 전환과 데이터 자동 이전은 제공하지 않습니다.

## 배포 파일

- `Gyeot-Setup-버전-x64.exe`: Windows x64 전체 설치 파일
- `latest-tauri.yml`, `proof-tauri-버전.json`: 서명된 업데이트 정보
- `SHA256SUMS.txt`: 배포 파일 체크섬

앱은 업데이트 서명과 설치 파일 해시·크기·앱 식별자를 검증합니다. Windows Authenticode 서명과는 별개이며 SmartScreen 경고가 표시될 수 있습니다.

향후 곁 홈페이지도 이 저장소의 공개 설치 파일을 연결합니다.
