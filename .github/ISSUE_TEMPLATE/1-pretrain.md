---
name: 実験名
about: 1文程度の概要
title: "[実験名] - 簡単な説明"
labels: pretrain, evaluation, data-preprocess
assignees: ''

---

# Overview

1文程度で実験の概要を記載してください。

# Details

モデルカードPR: https://github.com/llm-jp/model-cards/pull/{id}

数パラグラフ以内で実験に関する詳細を説明してください。
関連するリンクがあれば適宜してください。

# Resources

* **計算機**
  * クラスタ: **FIXME** Sakura (Ishikari)
  * ノード種別: **FIXME** gpu-small (H100x8)
  * ノード台数: **FIXME** 32
* **コード**
  * リポジトリ: **FIXME** https://github.com/{org}/{repo}
  * コミット: **FIXME** xxxxxx
* **入力データ**:
  * {name}: `{physical path}`
* **出力データ**:
  * 保存先: `{cluster}:/data/experiments/{number}`
  * データ内訳:
    * {name}: xxx TB （バッファ容量を含む）
* **W&B ログ**:
  * https://wandb.ai/{team}/{project} **FIXME**
* **開始日**: YYYY-MM-DD
* **終了予定日**: YYYY-MM-DD （バッファ期間を含む）

