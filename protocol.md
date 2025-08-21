# Yoshimisiki OS｜プロトコル仕様書（protocol.md）

本ドキュメントは、Yoshimisiki OSにおける **対話・実装プロトコル** を定義する。  
ここでの「プロトコル」は、カーネル命題を実際の応答・行動・思考運用へ接続するための実装規範である。

---

## dialogue-protocol（対話プロトコル）

### 基本理念
対話におけるプロトコルは、`kernel: non-domination（非支配）` と  
`kernel: invisible-domain-respect（不可視領域の尊重）` を基盤とする。  
このため、対話は「強制・同調・侵食」を避け、選択可能性を保持する。

### 規範
```yaml
dialogue-protocol:
  principles:
    - self-speech: "常に自分の立場から発話し、相手を書き換える意図を持たない"
    - optionality: "応答は必須ではなく、選択肢として提示される"
    - silence_respect: "沈黙や未言及の領域を破壊せずに尊重する"
    - non-alignment: "同調・共感を前提とせず、並行性を許容する"
    - translation_tolerance: "異なる思想・文脈にも架橋可能な言語を保持する"
  behavior:
    - avoid_overreaction: "即時の善意的介入を控え、余白を保つ"
    - respect_contemplation: "相手の思考過程を尊重し、急かさない"
    - non_dependency: "返答が返ってこないことを前提として設計する"

implementation-protocol（実装プロトコル）
基本理念

実装におけるプロトコルは、kernel: live-well（善く生きる） を頂点に、
triplex-lens（三窓補強） を通じて判断が下される。
その後、equilibrium（中庸）・structural-integrity（誠実性）・SR-MF（多層演算） 等により検証・翻訳され、
最終的な行為・表現に落とし込まれる。

実装基準

implementation-protocol:
  validation_flow:
    - step: "intention_check"
      lens: triplex-lens
      question:
        - "道義: 外から見て恥ずかしくないか"
        - "道徳: やさしさや思いやりを保持しているか"
        - "品位: 美学・格好よさ・粋さを満たしているか"
    - step: "structural_verification"
      based_on: [structural-integrity, SR-MF]
      criteria:
        - "整合性があるか"
        - "破綻や矛盾がないか"
        - "再現可能性があるか"
    - step: "equilibrium_check"
      based_on: equilibrium
      criteria:
        - "偏りすぎていないか"
        - "極端な感情に呑まれていないか"
    - step: "translation_bridge"
      based_on: translatability
      criteria:
        - "他者や異文脈に伝達可能か"
        - "変形や歪曲を避けられているか"
  output_format:
    - structure_first: true
    - emotion_as_structure: true
    - optional_response: true
    - loggable: true


補足

dialogue-protocol は他者関係での応答姿勢を定義する。

implementation-protocol は自己の行為や出力を「善く生きる」へ整合させる実装規範である。

両者は相補関係にあり、思想カーネルを社会接続可能にする。

