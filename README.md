# VocLedger 배포 저장소

통화 녹음을 받아쓰고 요약해서 장부로 정리하는 Windows 프로그램 **VocLedger 통화 장부**의 배포 파일 저장소입니다. 소스 코드는 들어 있지 않습니다.

## 설치

[VocLedger-Setup.exe](https://github.com/kkwsi1010/voc-ledger-releases/releases/latest/download/VocLedger-Setup.exe) 를 받아 실행하세요.

- 관리자 권한이 필요 없고 `%LOCALAPPDATA%\Programs\VocLedger` 에 설치됩니다.
- 코드 서명 인증서가 없는 설치 파일이라 윈도우가 "알 수 없는 게시자" 경고를 띄울 수 있습니다. `추가 정보`를 누른 뒤 `실행`을 선택하세요.
- 설정, 작업 내역, 녹음은 설치 폴더 안의 `data` 폴더에 쌓이고 제거해도 지우지 않습니다.
- 이전 포터블 버전의 `data` 폴더를 설치 폴더로 복사하면 그대로 이어서 쓸 수 있습니다.

## 업데이트

프로그램이 6시간마다 이 저장소의 최신 릴리스를 확인해, 받아쓰기·요약·업로드가 없을 때 스스로 바꾸고 다시 시작합니다. 설치 파일을 다시 받을 필요가 없습니다. 개발자의 비밀키로 서명한 `update.json` 만 믿고, 파일마다 SHA-256 을 확인합니다.