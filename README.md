# 올림포스의 서고 — 3D 모델 에셋

장흥중학교 교과 액션 RPG **「올림포스의 서고」** 에서 쓰는 3D 모델입니다.
게임 본체(HTML)가 이 저장소에서 모델을 내려받아 씁니다.

## 파일

| 파일 | 쓰이는 곳 |
|---|---|
| `temple.glb` | 마을 신전 건물 |
| `village_kit.glb` | 마을 소품 30종 |
| `boss1.glb` ~ `boss10.glb` | 관문별 보스 |

보스는 그 관문에 들어갈 때 하나씩만 내려받습니다.

## 저작자 표기

| 모델 | 만든이 | 라이선스 |
|---|---|---|
| Elder Moonseer (`boss1`) | [ItsKrish7](https://sketchfab.com/ItsKrish7) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Low Poly Roman Temple (WIP) (`temple`) | [lexferreira89](https://sketchfab.com/lexferreira89) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Medieval Town Base (`village_kit`) | [Kenney](https://kenney.nl/assets/medieval-town-base) | CC0 1.0 |
| Wise Man Rigged 3D Model (`npc_wise`) | [CG-Moon](https://sketchfab.com/CG-Moon) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| The Noble Craftsman (`npc_craft`) | [olmopotums](https://sketchfab.com/olmopotums) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Scholar cat (`npc_scribe`) | [Muru](https://sketchfab.com/muru) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Herbalist (`npc_herb`) | [Coffeek](https://sketchfab.com/coffe0wolf) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Mushroom Merchant Animated (`npc_trade`) | [Crazicide](https://sketchfab.com/Crazicide) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Idle animation Golem (`mob_golem`) | [Di Co](https://sketchfab.com/dimitricoquet) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Low Poly wolf (`mob_wolf`) | [manoeldarochadeoliveira](https://sketchfab.com/manoeldarochadeoliveira) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| 02_centaur_archer (Warcraft III Reforged) (`mob_centaur`) | [spikye09](https://sketchfab.com/spikye09) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Toad Warrior (`mob_toad`) | [SmugglersStudio](https://sketchfab.com/SmugglersStudio) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| PSX HARPY (`mob_harpy`) | [Seifert](https://sketchfab.com/Peter_Seifert) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| Hydra protofactor (`mob_hydra`) | [.](https://sketchfab.com/Hdhdhejwnwnjdjd) | [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) |
| `boss2` ~ `boss10` | 각 파일에 제작자 정보가 들어 있습니다 | 대부분 CC BY 4.0 |

모든 모델은 학습용으로 **폴리곤과 텍스처를 줄여** 사용했습니다 (CC BY 의 변경 고지).
게임 안 `메뉴 → 제작 정보` 화면에서도 같은 내용을 볼 수 있습니다.

## 사용 방법

게임 HTML 안의 `ASSET_BASES` 가 이 저장소를 가리킵니다.

```js
const ASSET_BASES=[
  'https://cdn.jsdelivr.net/gh/fistluck-lgtm/olympos-assets@main/',
  'https://raw.githubusercontent.com/fistluck-lgtm/olympos-assets/main/',
  'assets/'
];
```

앞에서부터 차례로 시도하므로, 학교망에서 한 곳이 막혀도 다음 주소로 넘어갑니다.
