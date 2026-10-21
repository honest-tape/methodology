# Honest Tape：測試方法

**用十幾年數據、扣真實成本，測你喺 YouTube 見到嘅交易策略，結果點都照講。**

呢個 repo 係 Honest Tape（YouTube 頻道「技術性擊倒」）嘅公開方法同預先登記紀錄。每集片嘅判決都根據呢度嘅規則。

| 檔案 | 內容 |
| --- | --- |
| [`methodology.md`](methodology.md) | 測試方法：七個陷阱、三個判決、我哋做唔到嘅嘢 |
| [`retest/process.md`](retest/process.md) | 重測系列流程：人手關卡、數據時期、成本、評估、判決門檻 |
| [`retest/plan_template.md`](retest/plan_template.md) | 每集預先登記模板 |
| [`retest/series_ledger.md`](retest/series_ledger.md) | 系列帳簿：每個測過嘅策略、變體數、累計試驗數；KO 嘅都唔刪 |
| [`assets/`](assets/) | 方法片「100 單」模擬嘅圖同數字 |

## 點樣證明「先寫、後跑」
每集嘅測試計劃（規則、變體、合格標準、預測）都會喺跑結果**之前** commit 入呢個 repo。
GitHub 上面嘅 commit 時間就係紀錄；之後只可以補上結果同「修 bug 紀錄」，唔可以改規則。

## 三個判決
| 判決 | 意思 |
| --- | --- |
| **KO** | 冇 edge：贏唔到隨機入場，或者只係「試得多」嘅運氣 |
| **判數輸** | 有 edge，但扣真實成本之後冇錢賺 |
| **企得住** | 扣成本後連 holdout 都過埋 |

## 免責
所有內容係教育用途，唔構成投資建議。只測試公開講過嘅規則，唔評論任何人。

文字內容以 [CC BY 4.0](https://creativecommons.org/licenses/by/4.0/) 授權：可以轉載、改編，註明出處「Honest Tape」即可。
