# 3D_Random_Walk
Pythonの勉強に3次元ランダムウォーク作ってみた <p>

大学の課題で3次元ランダムウォークのシミュレーションを作ってみました。<br>
初体験の3次元プロット、更にはそれを使って作るシミュレーションに苦戦しましたが、どうにか思い通りのものを作れました…<p>

僕のようにax.plot3Dメソッドの返り値とax.scatterメソッドの返り値の違い、animation.ArtistAnimationの引数型の特殊さに振り回されて時間を無駄にする人が減ることを願って、このコードを公開しておきます。<p>

## やったこと概要
1. とりあえず普通に作る。
  - 3次元ランダムウォークの移動履歴を表す配列を作る関数を作成<br>
  - その配列を引数に3Dアニメーションを作る関数を作成<br>
  
2. 点の数増やしてみる。
  - 複数個の点のランダムウォークのの移動履歴を表す配列を作る関数を作成<br>
  - その配列を引数に3Dアニメーションを作る関数を作成<br>
  
3. 統計してみる。
  - a個の点がn回動いた時の移動履歴をまとめた配列を作る関数を作成<br>
  - 各時刻での全ての点の原点からの距離の平均を要素とする1次元配列を作る関数を作成<br>
  - 線グラフでプロット。
