# logic_puzzle

**レンダリング用の関数**
 - Run時のレンダリングはFn1のみ
 - moveRocketに引数を渡し呼び出す
 - レンダリングした要素について、引数に応じて実行するかどうかを制御

**1回の操作**
 - 操作が実行されるときの条件（共通で設定可能）
 - xかyを1マス増減（移動）
 - rotateを1増減（右か左に90度方向転換）
 - タイルの色を塗りかえる
 - F1,F2,F3 いずれか指定されたもののレンダリングを0番目から行う

**moveRocket**
 - 引数に応じて操作を変える。
 - yはy軸の増減分
 - xはx軸の増減分
 - rotateは方向転換の増減分

（+1で90度右, -1で90度左）

タイル
・星なし
（0:赤色）
（1:緑色）
（2:青色）
・星あり
（3:赤色）
（4:緑色）
（5:青色）