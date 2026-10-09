# Card Quest 한국어 패치 v1.0.0

Card Quest의 메뉴, 카드, 장비, 상태 효과, 훈련 대사, 스토리 등 주요 텍스트를 한국어로 번역하는 **비공식 팬 패치**입니다. 개발사·배급사의 공식 번역이 아닙니다.

## 지원 환경

- Windows x64 / Steam, App ID **493080**
- 확인된 게임 버전 **1.03j**, Steam Build **20329684**
- 한국어 패치 **v1.0.0**, 번역 **3,518개**
- BepInEx **5.4.23.5 Windows x64**, SUIT Regular/Bold 포함

## 주요 특징과 검증 범위

카드·장비·전투 상태와 다양한 메뉴·호버·스토리 UI에 한국어를 적용합니다. 번역 문맥과 용어를 점검하고 반복 선택 시 영어 전환·카드 미리보기 깜박임 등을 개선했습니다. 한글 폰트는 게임에서 사용하며 별도 Windows 폰트 설치는 필요하지 않습니다.

## 다운로드·설치

공개 후 [Releases](https://github.com/DrownedRaitt/card-quest-korean-patch/releases)에서 `CardQuest-Korean-Patch-v1.0.0.zip`을 받습니다. `SHA256SUMS.txt`로 내려받은 파일의 체크섬을 확인할 수 있습니다.

1. 게임을 종료합니다.
2. Steam 라이브러리 → Card Quest 우클릭 → **관리 → 로컬 파일 탐색**.
3. ZIP 안의 모든 파일·폴더를 **`Card Quest.exe` 옆에 바로** 풉니다. 같은 이름의 하위폴더를 만들어서 그 안에 풀면 안됩니다.
4. Steam에서 게임을 실행하고 한국어 메뉴·글자 표시를 확인합니다.

`winhttp.dll`, `doorstop_config.ini`, `BepInEx/`가 게임 폴더 바로 안에 있어야 합니다. 상세 구조와 제거 방법은 배포 ZIP의 `INSTALL_KO.md`에 있습니다.

## 구버전 한글패치 사용자

방법 1. 한글패치만 업데이트

게임을 재설치하지 않고 한글패치만 교체하는 방법입니다.
게임을 완전히 종료합니다.
Steam에서 Card Quest를 우클릭하고 관리 → 로컬 파일 탐색을 선택합니다.
BepInEx/plugins/ 폴더 안의 기존 CardQuestKoreanPoC 폴더를 삭제합니다.
새 한글패치 ZIP 안의 BepInEx/plugins/CardQuestKoreanPoC 폴더를 같은 위치에 복사합니다.
게임을 실행합니다.
기존 RC2 사용자는 BepInEx를 다시 설치할 필요가 없습니다.

방법 2. 게임을 완전히 재설치

폴더를 직접 교체하는 과정이 어렵다면 게임을 새로 설치해도 됩니다.
Steam에서 Card Quest를 제거합니다.
기존 Card Quest 설치 폴더가 남아 있다면 해당 폴더도 삭제합니다.
Steam에서 Card Quest를 다시 설치합니다.
최신 한글패치 ZIP의 모든 내용을 Card Quest.exe가 있는 폴더에 압축 해제합니다.
게임을 실행합니다.

※ 게임을 삭제해도 설치 폴더 외부에 저장된 세이브는 일반적으로 유지됩니다. 다만 안전을 위해 재설치 전 세이브를 백업하는 것을 권장합니다.

## 제거

한국어 패치만 제거하려면 게임 종료 후 `BepInEx/plugins/CardQuestKoreanPoC/`만 삭제합니다. 전체 제거는 이 통합판만 설치했음을 확인한 경우에만 `INSTALL_KO.md`의 목록을 따릅니다. 순정 게임·세이브·게임 설정은 삭제하거나 초기화하지 않습니다.

## 알려진 제한 사항·제보

확인된 게임 버전 외 환경이나 다른 모드 조합은 정상 동작을 보장하지 않습니다. 게임 업데이트 후 패치가 작동하지 않을 수 있으며 일부 번역·UI가 미흡할 수 있습니다.

[Issues](https://github.com/DrownedRaitt/card-quest-korean-patch/issues)에 패치/게임 버전, 화면·표시 문구, 재현 방법, 가능하면 스크린샷을 남겨 주세요. 로그를 공개할 때는 사용자명·개인 경로를 가리고 세이브·계정 정보는 첨부하지 마세요.

## 구성 요소·라이선스

BepInEx 및 관련 라이브러리(MIT), Unity Doorstop(LGPL 2.1), SUIT(OFL 1.1)를 포함합니다. 출처·저작권·라이선스 원문은 ZIP의 `THIRD_PARTY_NOTICES.md`, `CardQuestKorean-Licenses/`, 폰트 폴더의 `OFL.txt`에서 확인할 수 있습니다. 한국어 패치 자체에 별도 공개 소스 라이선스를 지정하지 않았으며 제3자 라이선스 권리는 그대로 유지됩니다.

Doorstop 대응 소스 `UnityDoorstop-v4.5.0-source.zip`을 같은 릴리스에서 제공합니다. 설치에는 필요하지 않지만 재배포 시 대응 소스에 대한 동등한 접근을 유지해야 합니다. Doorstop의 수정·교체·디버깅 권리를 제한하지 않습니다. 게임 원본 파일은 포함하지 않습니다.
