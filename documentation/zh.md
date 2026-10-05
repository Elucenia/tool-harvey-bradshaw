<!-- ELUCENIA technical documentation · harvey-bradshaw · zh · no clinical/professional/rights approval -->

# Harvey-Bradshaw 指数

[条件、来源与许可](https://elucenia.org/zh/tools/harvey-bradshaw)

## 使用方法

在门户中使用工具，或通过本地 HTTP 服务器打开 index.html。选择语言，填写各字段，然后计算。

## 输入与单位

### 总体健康感（前一天）

`bem`

- `0` — 非常好
- `1` — 略差于正常
- `2` — 差
- `3` — 很差
- `4` — 极差

### 腹痛（前一天）

`dor`

- `0` — 无
- `1` — 轻度
- `2` — 中度
- `3` — 重度

### 水样或很稀的排便（前一天）

`evac`

每天 · 范围: 0–40

### 腹部包块

`massa`

- `0` — 无
- `1` — 不确定
- `2` — 确定
- `3` — 明确且有压痛

### 关节痛

`artralgia`

### 葡萄膜炎

`uveite`

### 结节性红斑

`eritema`

### 阿弗他溃疡

`aftas`

### 坏疽性脓皮病

`pioderma`

### 肛裂

`fissura`

### 新发瘘管

`fistula`

### 脓肿

`abscesso`

## 方法版本

HBI/Harvey–Bradshaw 1980：5领域，稀便开放计数；非CDAI

## 已记录的公式

总体感受（0–4）+腹痛（0–3）+前一天稀便次数+腹部包块（0–3）+每项并发症1分。

## 限制与适用人群

Harvey–Bradshaw描述克罗恩病的临床活动，包括前一天的稀便次数以及腹部包块和并发症评估。它不能诊断克罗恩病，也不能替代炎症或其他症状原因的评估。它与CDAI的关系良好但并不完全：Best2006分析了224次就诊并记录预测局限，因此HBI不能换算为精确的CDAI。所引研究的反应和缓解结果属于各自试验人群和观察时段。

## 参考文献

- [Harvey RF, Bradshaw JM. A simple index of Crohn's-disease activity. Lancet, 1980.](https://doi.org/10.1016/S0140-6736(80)92767-1)

- [Best WR. Predicting the Crohn's disease activity index from the Harvey-Bradshaw Index. Inflamm Bowel Dis, 2006.](https://doi.org/10.1097/01.MIB.0000215091.77492.2a)

- [Vermeire S et al. Correlation between the Crohn's disease activity and Harvey-Bradshaw indices in assessing Crohn's disease severity. Clin Gastroenterol Hepatol, 2010.](https://doi.org/10.1016/j.cgh.2010.01.001)

## 复现技术测试

在此仓库的根目录中运行 node test.cjs，以重复已记录的合成案例。原始输入、预期结果和容差保持不变。技术测试不构成临床验证。

```sh
node test.cjs
```

tool.json 包含来源、版本和审查范围。examples.json 保留合成输入与预期结果；results.json 记录实际得到的结果。

[记录与参考文献](../tool.json) · [JavaScript代码](../calculator.js) · [参考案例](../examples.json) · [results.json](../results.json)

## 审查与使用条件

尚未开展独立临床审查。

此界面为自主编写的翻译，并非官方或认证版本。尚未完成独立临床审查、专业语言审查或工具权利授权。

公式或分类结果。解释、处理及适用性须结合专业评估和所选来源。

## 许可与署名

Apache-2.0 仅适用于 ELUCENIA 代码。工具、出版物、翻译和数据的权利仍归各自权利人所有。请保留 LICENSE 和 NOTICE。

ELUCENIA · Felipe Guedes · Copyright © 2026
