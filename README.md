# NASA-95

CAE 전·후처리 프로그램(유한요소 해석용 Pre/Post 프로세서)의 **배포 저장소**입니다. 설치 파일과 변경 기록을 여기서 받습니다. 소스 코드는 이 저장소에 없습니다.

## 내려받기

[Releases](https://github.com/kwonbyeongchun/Nasa-95-Release/releases) 에서 최신 버전을 받습니다.

| 파일 | 용도 |
|---|---|
| `NASA-95-<버전>-setup.exe` | 설치 파일. 시작 메뉴·바탕화면 바로 가기와 `.nasa95` 파일 연결을 만든다 |
| `NASA-95-<버전>-win64.zip` | 포터블. 풀어서 `NASA-95.cmd` 로 실행 |

- Windows 10/11 x64. Python·Qt 는 배포본에 들어 있어 따로 설치할 것이 없습니다.
- 3D 화면은 Vulkan 을 씁니다. 그래픽 드라이버가 Vulkan 1.1 이상을 지원해야 합니다.

## 솔버

해석 솔버는 배포본에 들어 있지 않습니다. 따로 설치한 뒤 프로그램 설정(또는 환경 변수)에서 실행 파일 경로를 지정합니다.

| 솔버 | 환경 변수 | 비고 |
|---|---|---|
| CalculiX `ccx` | `NASA95_CCX` | 2.22 기준 |
| OpenSees | `NASA95_OPENSEES` | 3.8.0 으로 확인 |
| MyStran | `NASA95_MYSTRAN` | |

## 변경 기록

[CHANGELOG.md](CHANGELOG.md)

## 문의·버그 신고

이 저장소의 [Issues](https://github.com/kwonbyeongchun/Nasa-95-Release/issues) 에 남겨 주세요. 버전, 재현 절차, 가능하면 프로젝트 파일(`.nasa95`)을 함께 적어 주시면 빠르게 확인할 수 있습니다.
