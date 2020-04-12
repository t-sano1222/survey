# Depth PredictionWithout the Sensors: Leveraging Structure for Unsupervised Learning from Monocular Videos
[Casser+(Google Brain), AAAI2019] 

## どんなもの?
自動運転の発達に伴い活発化している単眼深度推定の研究．
深度マップとEgomotionを推定する．
物体の移動を取り入れることでSOTA．

## 先行研究との比較
MASK-RCNNで画像中の物体を認識．
認識した物体の移動を損失関数に入れることで，自身と同じ速度で動く物体が無限遠となることを防止．

## 技術や手法の肝
既存のdepth&egomotionネットワークにSfM learnerの考えを取り入れている．

## 検証法
KTTIのデータセットでSOTA

## 議論

## 自分の実装

## Link
arxive:https://arxiv.org/abs/1811.06152
github:https://github.com/tensorflow/models/tree/master/research/struct2depth \
project page:https://sites.google.com/view/struct2depth
