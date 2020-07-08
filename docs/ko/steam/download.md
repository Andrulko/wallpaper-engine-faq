---
tags:
  - 가동 중지 시간
  - 서버
  - 다운로드
  - 진행률
  - 창작마당
  - 연결
---

# Steam 배경화면 다운로드 문제

**모든 다운로드는 Steam이 진행한다는 점**을 유의하세요. Wallpaper Engine은 Steam의 다운로드 상태만 표시할 뿐이고, 모든 다운로드 문제는 Steam과 관련되어 있으며 Wallpaper Engine과는 직접적인 관계가 없습니다. 이 가이드는 다운로드와 관련된 일반적인 문제를 모두 포함하고 있으며, 많은 경우 초기 문제 원인은 지나치게 열성적인 바이러스 백신 응용 프로그램이나 차단된 네트워크 포트입니다.

Steam 다운로드 관련 문제가 발생하면, 바이러스 백신 응용프로그램이 Steam을 차단하지 않고, 네트워크 라우터의 방화벽을 포함한 모든 방화벽에서 필요한 포트가 모두 열려있는지 확인하세요.

::: tip 스마트폰의 모바일 핫스팟으로 전환하여 배경화면을 다운로드해보면, 네트워크 라우터가 Steam 다운로드를 차단하고 있는지 쉽게 확인할 수 있습니다. :::

## 배경화면 다운로드가 0% 또는 100% (또는 다른 퍼센트)에서 중단
Steam이 다운로드를 완료하지 않고 파일을 식별하지 않습니다. 다운로드가 한동안 중단되면 잠시 기다려 보고, 그래도 여전히 Steam 다운로드가 작동하지 않으면 다음 방법을 시도해 보세요:

* Steam 옵션에서 Steam의 다운로드 캐시를 지웁니다:
  * [Steam 다운로드 캐시 지우기](https://support.steampowered.com/kb_article.php?ref=3134-TIAL-4638)
* 그런 다음 Steam에서 Wallpaper Engine 파일을 식별합니다:
  * [Wallpaper Engine 파일 식별하기](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335)
* 여전히 모든 다운로드가 중단되면: **Steam 끄기** 후 다음 디렉터리의 **콘텐츠를 삭제합니다**:
  * `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`
    * 바이러스 백신 응용 프로그램이 설치되었으면, 이 디렉터리가 제외되었는지 확인합니다
    * **참고:** `C:\Program Files (x86)\Steam`은 기본 Steam 경로이며, 다른 곳에 설치한 경우 위치를 확인하세요.
* Steam을 다시 시작하고, 게임은 시작하지 않습니다. Steam 다운로드 탭에서 진행률을 확인하고 일시정지된 다운로드를 재개합니다.

::: details 위의 단계로 다운로드 문제를 해결하지 못했다면, 여기를 클릭하여 더 많은 가능한 해결책을 확인하세요
* 바이러스 백신 방화벽이 Steam을 차단하지 않았는지 확인합니다. 바이러스 백신 앱 설정에서 Steam 디렉터리 전체를 제외하세요.
* 다운로드하지 못한 배경화면을 구독 취소하고, Steam을 재시작한 뒤 다시 구독합니다.
* Steam 설정에서 다른 콘텐츠 서버를 선택합니다. 옵션은 Steam 설정의 "다운로드" 탭에서 찾을 수 있습니다.
* 시간, 대역폭, 앱 내 존재를 바탕으로 **Steam 설정**에서 Steam 다운로드를 제한하지 않았는지 확인합니다.
* Steam에서 '다운로드' 탭을 엽니다. (라이브러리 -> 다운로드) 일시정지된 다운로드를 찾아보고, 발견하면 '계속'을 클릭하세요.
* Steam에서 Wallpaper Engine을 오른쪽 클릭한 다음, 속성을 클릭하고 **배경 다운로드 허용**을 선택합니다.
* Steam에 보류 중인 게임 업데이트가 없는지 확인합니다. 배경화면 다운로드를 일시정지하거나 비활성화할 수 있습니다.
* Steam 서버 문제의 경우 최소 하루를 기다린 후 다시 시도해 봅니다.
* **최후의 방법으로** Wallpaper Engine을 다시 설치해서 손상된 Steam 파일을 모두 제거해 봅니다. (모든 배경화면을 다시 다운로드합니다!) :::

::: tip Steam 서버는 점검을 위해 매주 정해진 시간마다 오프라인 상태가 됩니다:

* 미국 서부: **화요일 오후 4시 (UTC - 7)**
* 중앙 유럽의 같은 시간: **수요일 오전 1시 (UTC + 1)**
* 중국의 같은 시간: **수요일 오전 8시 (UTC + 8)**

대략 해당 시간 즈음에 이 글을 읽고 있다면, 서버가 일시적으로 오프라인일 수도 있습니다. 한두 시간 정도 기다린 뒤 다시 시도하세요. :::

## Steam: "다운로드 파일 누락" 오류

Steam이 일부 파일을 다운로드할 수 없는 경우, 바이러스 백신 응용 프로그램의 Steam 차단 또는 무작위 발생이 원인일 수 있습니다. 보통 다음 방법으로 해결할 수 있습니다:

* Steam을 끕니다.
* 이 디렉터리의 콘텐츠를 삭제합니다: `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`
* 이 디렉터리의 콘텐츠를 삭제합니다: `C:\Program Files (x86)\Steam\steamapps\downloading\431960`
  * **참고:** `C:\Program Files (x86)\Steam`은 기본 Steam 경로이며, 다른 곳에 설치한 경우 위치를 확인하세요.
* Steam을 시작하고 Wallpaper Engine 파일을 식별합니다:
  * [Wallpaper Engine 파일 식별하기](https://support.steampowered.com/kb_article.php?ref=2037-QEUH-3335)

바이러스 백신 앱이 설치되어 있는 경우: 이 디렉터리를 예외로 구성하여 Steam 창작마당 다운로드 차단을 방지합니다: `C:\Program Files (x86)\Steam\steamapps\workshop\downloads`

#### 관련 문서: [Steam이 모든 배경화면을 다시 다운로드합니다](/steam/redownload)