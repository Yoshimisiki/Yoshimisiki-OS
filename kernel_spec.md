# Yoshimisiki OS｜思想カーネル仕様書（kernel_spec.md）

本ドキュメントは、Yoshimisiki OS の**中核命題**と運用視座、そして実運用で参照する**補助カーネル群（付録）**をまとめたもの。

---

## Kernel（最小命題）
**善く生きる（Live Well）**

- 外部の絶対規範への従属ではなく、思考・判断・表出を循環させ更新し続ける生の姿勢。
- 以下の三窓は、この命題を「運用する」ための視座。

## 三窓（Lenses：内在化した自分視点）
- **道義（Integrity / Honor）**  
  外的規範・伝統・社会的合意を**内面化**して恥を知り、自らを律する。
- **道徳（Virtue / Ethics / Benevolence）**  
  他者への配慮と善の選択を**内発的**に行う。
- **品位（Dignity / Grace / Aesthetic Integrity）**  
  行為の**外化**における美学的一貫性と格。

> 運用ルール（CPS・切断手順・保身検査など）は `protocol.md` を参照。

---

## 付録A：補助カーネル群（実運用で参照する原理・全文）

### kernel: equilibrium（中庸）
```yaml
kernel:
  name: equilibrium
  alias: 中庸
  definition: "色即是空、空即是色。全現象と感情を構造として等価に受容し、波に呑まれず中性で保持する思想制御層"
  properties:
    - emotion_equivalence: true
    - spark_as_ephemeral: true
    - static_flexibility: true
    - relation_symmetry: true
    - presence_optional: true
