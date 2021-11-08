# Kickstarter-Project

* クラウドファウンディング成功可否を予測するモデルの実装
* URL: https://www.kaggle.com/kemical/kickstarter-projects

Skill UP AI インターンプロジェクト2021

分類モデル・回帰モデルそれぞれの内容

Notebook1の内容
* 目的変数と説明変数の関係を確認するためのグラフを作成する
* 分類の場合は, ロジスティック回帰
* 質的変数が扱えないアルゴリズムを使う場合は, ダミー変数に置き換える
* 識別精度を確認する(混同行列を作成し, Accuracy, Recall, Precisionを求める)


Notebook2の内容
* 汎化誤差をホールドアウト法と交差検証法によってそれぞれ評価する
* 正則化によって, 出力への寄与が小さい影響は無視して、出力への影響が大きい良い特徴だけでモデルを構成
* 正規化、標準化の重要性（正規化・標準化・無相関化・白色化)
* サポートベクターマシン(カーネルトリック)
* グリッドサーチ


Notebook3の内容
* 特徴選択（フィルタ法・ラッパー法・埋め込み法）
* 決定木→(アンサンブル学習)ランダムフォレスト, アダブースト
* ニューラルネットワーク


Notebook4の内容 (随時更新中)
* ランダムサーチ
* ベイズ最適化
* K-means法
* 主成分分析
