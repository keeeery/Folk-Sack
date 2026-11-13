# Folk Sack (공개용 사본)

포트폴리오 첨부용으로 공개한 저장소입니다.
학원 저장소(KooHoo-Dev/3rd-TeamProject-KH)의 커밋 이력을 브랜치·태그와 함께 그대로 옮기고,
**외부 에셋만 모든 커밋에서 제외**했습니다. 커밋 메시지·작성자·날짜는 원본과 같고, 커밋 해시는 다릅니다.
원본의 Pull Request 기록은 옮겨지지 않았습니다.

서버는 별도 저장소(KooHoo-Dev/3rd-TeamProject-KH-Server)에 있습니다.

## 제외한 것

라이선스상 재배포할 수 없거나 출처가 팀이 아닌 파일입니다.

| 경로 | 내용 |
|---|---|
| `Assets/99. External Assets/AllIn1SpriteShader/` | 스프라이트 셰이더 에셋 |
| `Assets/Resources/Character/` 안의 스프라이트 시트 | 캐릭터 스프라이트 (`1 Woodcutter`, `2 GraveRobber`, `3 SteamMan`, `4 Effects`, `charSprite.png`). 애니메이션·컨트롤러 파일은 남김 |
| `Assets/Resources/UI/` 중 19개 | 외부 UI 시트 (Buttons, Craft, Equipment, Inventory, Main_menu 등) |
| `Assets/Plugins/Demigiant/` | DOTween |

## 열어 볼 때

- Unity `6000.3.15f1`
- 위 에셋이 빠져 있어 **그대로는 실행되지 않습니다.** DOTween·AllIn1SpriteShader를 쓰는 스크립트는 컴파일 오류가 나고, 캐릭터·일부 UI 스프라이트 참조는 비어 있습니다.
- 코드는 `Assets/02. Scripts/`, `Assets/03. UI/Scripts/`, `Assets/04. Environment/Scripts/`에 있습니다.

## 포함된 폰트

Noto Sans KR·Galmuri(SIL Open Font License 1.1), m5x7(Daniel Linssen)을 사용합니다.
