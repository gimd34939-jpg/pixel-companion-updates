# Pixel Companion

Windows x64용 포치타 데스크톱 알림 앱의 설치 파일과 자동 업데이트 채널입니다.

## 다른 PC에 처음 설치하기

1. [최신 설치 페이지](https://github.com/gimd34939-jpg/pixel-companion-updates/releases/latest)에서 Setup ZIP을 내려받아 압축을 풉니다.
2. 기존 포치타가 실행 중이면 트레이에서 완전히 종료합니다.
3. **Install.cmd**를 실행하고 관리자 확인 창을 직접 허용합니다. 최초 한 번 공개 인증서 한 개를 LocalMachine\TrustedPeople에 등록하고 업데이트 채널을 설치합니다. Root 저장소나 Windows 보안 정책은 변경하지 않습니다.
4. 시작 메뉴 또는 앱 바로가기로 실행합니다. Windows 10 2004 이상 또는 Windows 11과 Microsoft App Installer가 필요합니다.

## 자동 업데이트

[고정 업데이트 파일](https://github.com/gimd34939-jpg/pixel-companion-updates/releases/latest/download/PixelCompanion.appinstaller)을 사용합니다. 설치된 앱을 시작할 때 확인하고, Windows가 약 8시간마다 백그라운드에서 확인합니다. 배포 직후 모든 PC가 즉시 바뀌는 방식은 아니며 실행 중인 앱을 강제 종료하지 않습니다. EXE 직접 실행은 시작 시 확인을 우회할 수 있으므로 시작 메뉴나 앱 바로가기를 사용하세요.

다음 버전도 같은 서명키로 서명해 이 저장소의 새 정식 Release에 게시합니다. `.appinstaller` 파일 이름과 고정 주소는 유지합니다.

공개 인증서 지문: `8CBC60C121F2CC69AAAAF4A5A84527D4CC2C09BC`

Codex Hooks와 Windows 알림 접근 허용은 대상 PC에서 별도로 설정해야 합니다. 실제 다른 PC 업데이트 완료 여부는 대상 PC 등록 후 확인해야 합니다.

[모든 배포 버전](https://github.com/gimd34939-jpg/pixel-companion-updates/releases)에서 설치 파일과 해시 목록을 확인할 수 있습니다. 앱 구현 소스, 사용자 설정, 개발 검사 기록과 서명 개인키는 이 저장소에 게시하지 않습니다. 원작 또는 OpenAI의 공식 제품이 아닌 개인용 독립 프로그램입니다.
