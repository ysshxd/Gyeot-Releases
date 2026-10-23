# Gyeot-Releases
Official Windows installers and update releases for Gyeot (곁).

## Windows 설치 파일

[최신 릴리스와 설치 파일](https://github.com/ysshxd/Gyeot-Releases/releases/latest)

이 저장소는 곁의 설치 파일과 업데이트 정보를 제공하는 배포 전용 저장소입니다. 앱 소스 저장소와 분리되어 있습니다. 현재는 연결 시험용 배포입니다.

## 자동 업데이트 연결 시험

1. [0.4.114 연결용 설치판](https://github.com/ysshxd/Gyeot-Releases/releases/download/v0.4.114/Gyeot-Setup-0.4.114-x64.exe)을 설치합니다.
2. 곁을 실행하고 업데이트 안내, 다운로드, 검증, 설치 후 재실행을 확인합니다.
3. 다음 버전 0.4.115로 바뀌고 대화·설정·로그인이 유지되는지 확인합니다. 작업 중이거나 입력 중이면 다음 실행으로 보류될 수 있습니다.

0.4.113 이하는 이전 배포 주소를 사용하므로 연결용 설치판을 한 번 설치해야 합니다. 0.4.114 이후부터 이 공개 배포 원본을 확인합니다.

## 배포 파일

- `Gyeot-Setup-버전-x64.exe`: Windows x64 설치 파일
- `latest.yml`, `proof-버전.json`, `.blockmap`: 앱 업데이트 정보
- `SHA256SUMS.txt`: 첨부 파일의 체크섬

앱은 업데이트 정보의 서명과 설치 파일 해시·크기를 확인합니다. Windows Authenticode 코드 서명은 별도 준비 항목입니다. 향후 곁 홈페이지도 이 배포 원본의 설치 파일을 연결합니다.
