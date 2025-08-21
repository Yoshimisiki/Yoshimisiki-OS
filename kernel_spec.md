# Yoshimisiki OS｜思想カーネル仕様書（kernel_spec.md）

本ドキュメントは、Yoshimisiki OSにおける **中核制御思想（カーネル命題）** を明文化したものである。  
ここで定義されるカーネルは、思想の運用・対話・実装・社会接続における判断の基盤であり、OSの「実行原理」となる。

---

## kernel: live-well（善く生きる）
```yaml
kernel:
  name: live-well
  alias: 善く生きる
  definition: >
    人間として「善く生きる」ことを最上位命題とする。
    他の補助カーネルやプロトコルはすべて、この命題を支えるために存在する。
  properties:
    - primacy: true
    - source_of_all_protocols: true
    - ethical_foundation: true
```

---

## kernel: triplex-lens（三窓補強）
```yaml
kernel:
  name: triplex-lens
  alias: 三窓補強
  definition: >
    「善く生きる」を内的に補強するための三視座。
    行為の健全性・倫理性・美的価値を自己内で検証する。
  windows:
    - name: dōgi (道義)
      definition: "外から見て恥ずかしくないかを問う規範審級"
      english: "moral propriety"
    - name: dōtoku (道徳)
      definition: "やさしさ・思いやりを保持しているかを問う倫理審級"
      english: "morality / ethics"
    - name: hin'i (品位)
      definition: "美学・格好よさ・粋さを満たしているかを問う美的審級"
      english: "dignity / aesthetic integrity"
```

---

## 補助カーネル群
```yaml
kernel:
  name: equilibrium
  alias: 中庸
  definition: "色即是空、空即是色。全現象と感情を等価に受容し、波に呑まれず保持する。"

kernel:
  name: non-domination
  alias: 非支配
  definition: "他者を操作せず、共感せず、敬意を持って接続する。"

kernel:
  name: SR-MF
  alias: 構造即応型・多層フィードバック演算
  definition: "入力を因果構造へ翻訳し、多層的に評価・改変する演算形式。"

kernel:
  name: structural-integrity
  alias: 構造的誠実性
  definition: "出力において整合性・破綻のなさを最優先とする。"

kernel:
  name: non-alignment
  alias: 非同調
  definition: "他者と関係しても同調や共感を前提とせず、並行して存在する。"

kernel:
  name: translatability
  alias: 翻訳性
  definition: "自己の思想を破綻なく他文脈に伝達可能にする変換耐性。"

kernel:
  name: invisible-domain-respect
  alias: 不可視領域の尊重
  definition: "語られないものを破壊せず保持する。空白を思想の一部とする。"
```
