# Osero
C++でのソースコード．

表示されている横・縦の座標値をもとに，置きたい位置の値を入力することで，ゲームを進めていきます．
（注：数値以外を入力するとバグが発生します）

main.cppの9行目，10行目で対戦相手を変更することができます．
--クラス名--
・PLAYER：人間
・NORMAL_OMPUTER：石を置ける位置に置くCOM
・GREEDY_COMPUTER：一番多く石を多くとれる位置に置くCOM
・PREDICT_COMPUTER：数手先を読んで一番多く石をとれる位置に置く(非推奨：時間がかかる)
・AI_COMPUTER：強化学習によって学習し，最善手を取ってくるCOM（ある程度強い）
