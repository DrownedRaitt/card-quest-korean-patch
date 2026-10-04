# Card Quest 한국어 패치

Steam 게임 **Card Quest**의 팬 제작 비공식 한국어 번역 패치입니다.

게임 내 메뉴, 카드, 장비, 상태 효과, 스토리 등 주요 텍스트를 한국어로 번역합니다.

> 이 패치는 공식 번역이 아니며, Card Quest 개발사와는 관련이 없는 비공식 팬 패치입니다.

---

## 다운로드

최신 버전은 이 저장소의 **Releases** 페이지에서 다운로드할 수 있습니다.

---

## 지원 환경

현재 다음 환경에서 설치 및 실행을 확인했습니다.

- **운영체제:** Windows
- **플랫폼:** Steam
- **Card Quest Steam Build:** `20329684`
- **BepInEx:** `5.4.23.5 Windows x64` 포함

BepInEx와 한글 폰트가 패치에 포함되어 있으므로 **별도로 설치할 필요가 없습니다.**

게임 업데이트 이후에는 패치가 정상적으로 작동하지 않을 수 있습니다.

---

# 설치 방법

1. Releases에서 최신 한국어 패치 ZIP 파일을 다운로드합니다.
2. Steam 라이브러리에서 **Card Quest**를 우클릭합니다.
3. **관리 → 로컬 파일 탐색**을 눌러 Card Quest 설치 폴더를 엽니다.
4. 게임이 실행 중이라면 종료합니다.
5. 다운로드한 ZIP 파일의 **내용물이 Card Quest 설치 폴더 바로 아래에 위치하도록 압축을 해제합니다.**
6. Steam에서 Card Quest를 실행합니다.

> [!IMPORTANT]
> **`CardQuestKorean-...` 같은 새 하위 폴더를 만들어 그 안에 압축을 풀면 안 됩니다.**
>
> ZIP 안의 `winhttp.dll`, `doorstop_config.ini`, `BepInEx` 폴더 등이  
> **Card Quest 설치 폴더 바로 아래에 위치해야 합니다.**

### 올바른 설치 예시

```text
Card Quest/
├─ Card Quest.exe
├─ winhttp.dll
├─ doorstop_config.ini
└─ BepInEx/
   ├─ core/
   │  └─ ...
   └─ plugins/
      └─ CardQuestKoreanPoC/
         ├─ CardQuestKoreanPoC.dll
         ├─ translation-base-runtime-batch1-10-v1.tsv
         └─ fonts/
            ├─ SUIT-Regular.ttf
            ├─ SUIT-Bold.ttf
            └─ OFL.txt
