<!-- ELUCENIA technical documentation · harvey-bradshaw · ja · no clinical/professional/rights approval -->

# Harvey-Bradshaw指数

[条件・出典・許諾](https://elucenia.org/ja/tools/harvey-bradshaw)

## 使い方

ポータルでツールを使用するか、ローカルHTTPサーバー経由でindex.htmlを開いてください。言語を選択し、項目を入力して計算してください。

## 入力項目と単位

### 全身状態（前日）

`bem`

- `0` — 非常に良い
- `1` — 通常より少し悪い
- `2` — 悪い
- `3` — 非常に悪い
- `4` — 極めて悪い

### 腹痛（前日）

`dor`

- `0` — なし
- `1` — 軽度
- `2` — 中等度
- `3` — 強い

### 液状便または非常に軟らかい便（前日）

`evac`

1日あたり · 範囲: 0–40

### 腹部腫瘤

`massa`

- `0` — なし
- `1` — 不確か
- `2` — 確定
- `3` — 明確で痛みを伴う

### 関節痛

`artralgia`

### ぶどう膜炎

`uveite`

### 結節性紅斑

`eritema`

### アフタ性潰瘍

`aftas`

### 壊疽性膿皮症

`pioderma`

### 裂肛

`fissura`

### 新たな瘻孔

`fistula`

### 膿瘍

`abscesso`

## 方法の版

HBI/Harvey–Bradshaw 1980：5領域、液状便回数は上限なし；CDAIではない

## 記載された計算式

全身状態（0–4）+腹痛（0–3）+前日の液状便回数+腹部腫瘤（0–3）+合併症ごと1点。

## 限界・対象集団

Harvey–Bradshawは、前日の液状便の回数、腹部腫瘤と合併症の評価を含め、クローン病の臨床活動性を表します。クローン病の診断や、炎症・他の症状原因の評価に代わるものではありません。CDAIとの関係は良好ですが完全ではありません。Best2006は224回の受診を分析し予測の限界を記録したため、HBIを正確なCDAIへ変換することはできません。引用した研究の反応・寛解の結果は、その試験の対象集団と期間に関するものです。

## 参考文献

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## 技術テストの再現

このリポジトリのルートディレクトリでnode test.cjsを実行すると、記録された合成ケースを再実行できます。元の入力、期待結果、許容誤差は保持されています。技術テストは臨床的検証を意味しません。

```sh
node test.cjs
```

tool.jsonには出典、版、確認範囲が記録されています。examples.jsonには合成入力と期待結果が保持され、results.jsonには実際に得られた結果が記録されています。

[記録・参考文献](../tool.json) · [JavaScriptコード](../calculator.js) · [参照ケース](../examples.json) · [results.json](../results.json)

## 確認状況と使用条件

独立した臨床レビューは実施されていません。

このインターフェースは独自に作成した翻訳であり、公式版や認証済みの版ではありません。独立した臨床レビュー、専門家による言語レビュー、評価尺度等の権利許諾の確認は実施されていません。

式または分類の結果です。解釈、対応、適用可能性は専門家による評価と選択した出典に依存します。

## ライセンスと帰属表示

Apache-2.0はELUCENIAのコードにのみ適用されます。評価尺度等、出版物、翻訳、データの権利は、それぞれの権利者に帰属します。LICENSEとNOTICEを保持してください。

ELUCENIA · Felipe Guedes · Copyright © 2026
