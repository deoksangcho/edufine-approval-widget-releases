# 행정실 결재 위젯 다운로드

나이스 미결·협조함, 에듀파인 결재, 교데통 승인 대기, e교육금고 전송대상 건수를 보여 주는 Windows 위젯입니다. Chrome 또는 Edge 확장 프로그램과 연결해 현재 로그인된 업무 사이트에서 조회합니다.

이 저장소는 설치 파일과 사용 안내를 배포하는 공간입니다.

## 다운로드

- [최신 버전 다운로드](https://github.com/deoksangcho/edufine-approval-widget-releases/releases/latest)
- [v0.8.7 Windows 설치 ZIP](https://github.com/deoksangcho/edufine-approval-widget-releases/releases/download/v0.8.7/edufine-approval-widget-v0.8.7.zip)

릴리스의 Assets에서 **edufine-approval-widget-v0.8.7.zip**을 선택합니다. `Source code (zip)`에는 설치 프로그램이 없습니다.

## 설치

1. ZIP을 모두 압축 해제하고 `Setup.exe`를 실행합니다.
2. 안내창에서 업무용 Chrome 또는 Edge를 선택합니다.
3. 안내에 따라 확장 관리 화면에서 **개발자 모드 → 압축해제된 확장 프로그램 로드**를 선택합니다.
4. 안내창에서 복사한 설치 폴더를 불러옵니다.
5. 업무포털에 로그인합니다. 연결되면 위젯에 건수가 표시됩니다.

기존 사용자는 설치 후 확장 관리 화면에서 위젯의 새로고침 버튼을 한 번 누릅니다. 상세 안내는 ZIP 안의 `사용방법.md`에 있습니다. 관리되는 학교 PC의 확장 설치 제한은 해당 기관의 정책을 따릅니다.

## 이전에 바이러스 감지로 다운로드가 차단된 경우

2026-09-15 Microsoft Defender 보안 인텔리전스를 **1.459.211.0**으로 업데이트한 뒤 v0.8.7 원본 ZIP을 재검사하여 탐지 0건을 확인했습니다. 파일의 내용은 기존 노션 배포본과 같습니다.

**Windows 보안 → 바이러스 및 위협 방지 → 바이러스 및 위협 방지 업데이트(보호 업데이트) → 업데이트 확인** 후 다시 다운로드해 주세요.

실행 파일은 코드 서명되지 않아 게시자나 SmartScreen 경고가 별도로 나올 수 있습니다. 백신 탐지가 계속되면 릴리스 버전, 탐지명, 보안 인텔리전스 버전을 알려 주세요. 검사 결과는 검증한 환경의 결과이며 모든 PC에서 동일함을 보장하는 것은 아닙니다.

## 파일 동일성 확인

v0.8.7 ZIP SHA-256:

```text
0B6062B3D71ECFEB3D262C1B5816A6F56218CE0DA84CE3CF940294C379BD9A3B
```

다운로드 파일의 값은 PowerShell에서 확인할 수 있습니다.

```powershell
Get-FileHash -LiteralPath '.\edufine-approval-widget-v0.8.7.zip' -Algorithm SHA256
```

해시값이 같으면 배포 원본과 동일한 파일입니다. 개인정보가 포함된 화면이나 업무자료 대신 파일 버전과 오류 문구로 문의해 주세요.
