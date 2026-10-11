# 제작에 쓴 에셋

게임에 들어간 외부 에셋과 라이선스. 새 에셋을 넣기 전에 라이선스를 직접 확인하고 여기에 먼저 적는다.

## 그림

**Ninja Adventure - Asset Pack** (2026-03-29 갱신판)
- 만든 사람: Pixel-boy, AAA
- 출처: https://pixel-boy.itch.io/ninja-adventure-asset-pack
- 라이선스: CC0 1.0 Universal. 상업적 사용 가능, 출처 표기 의무 없음
- 확인: 팩 안의 `LICENSE.txt`, `README.md`와 itch.io 페이지 (2026-10-10)
- 쓰는 방식: 원본 색을 그대로 쓰지 않고 `scripts/assets.py`로 하르벤 48 팔레트에 맞게 다시 입혔다. 결과물은 `assets/sprites/`
- 쓰는 파일: 캐릭터(NinjaMageOrange, GreenPig), 몬스터(Slime), 동물(DogBlack), 타일셋(TilesetFloor, TilesetNature), 효과(Thunder, Claw, Spark, Leaf, RockGray, Smoke, SmokeCircular, SpriteSheetRock), UI(ThemeMap, Theme Wood, Receptacle Sphere, LifeBarMini, Emote, Skill Icon, 키보드와 마우스 그림), 아이템(Coin2, GoldCoin, LifePot, WaterPot)

## 글꼴

**갈무리 Galmuri** 2.40.3 (Galmuri11, Galmuri11 Bold, Galmuri9)
- 만든 사람: 이민서 (quiple)
- 출처: https://github.com/quiple/galmuri
- 라이선스: SIL Open Font License 1.1. 전문은 `assets/fonts/LICENSE-Galmuri.txt`
- 확인: npm `galmuri@2.40.3` 배포본의 `dist/LICENSE.txt` (2026-10-10)
- 쓰는 방식: woff2를 바꾸지 않고 빌드할 때 data URI로 넣는다
