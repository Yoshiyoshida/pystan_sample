# #pystan_sample
- このプロジェクトはpipenvで管理している
## このリポジトリの目的
- FJCTの課題である時系列データ予測の練習
- 本リポジトリはpystanを使う

## 参考
- Udemy講座【PythonとStanで学ぶ】仕組みが分かるベイズ統計学入門

## ゴール
1. 任意のデータに対して、pystanを用いてデータの予測をすることができる
  - 簡単なモデルの設定
  - モデルのチューニング
2. 予測に伴う手順を説明することができる

## 目的達成へのKPI
- そもそもの計算内容の理解
  - ベイズ更新
  - ベイズの定理
  - モンテカルロの理解
- 　pystanの扱い方を学習
  - 単回帰
  - 重回帰
  - ロジスティック回帰
  - 状態空間モデル
- 任意のデータへの適用
- できればブログにまとめる
# #フォルダ概要
## pystan_udemy
- Udemyを参考にしたフォルダ
## pystan_local_case
- 拾ってきたデータにpystanを適用
## Bayesian
- ベイズの定理の学習
- ベイズ更新を実装
  - 尤度関数が「ベルヌーイ分布」の時
- MAP推定
## MonteCarlo
- モンテカルロステップの学習
  - π/4を使って確率的にπを算出
- 棄却サンプリング
