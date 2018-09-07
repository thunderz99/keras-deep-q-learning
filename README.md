# AIにゲームを遊んでもらった

## 背景

roseについて、みんなの絵文字レスポンスによって回答の精度を上げる要望を頂いている。

強化学習は上記を対応できそう。現在はその中の一つの手法（Deep Q-learning）を勉強中。

入門編は、CartPoleと言うゲームをAIが学習して遊ぶ。

参考コードをDLして色々弄ってみた。

![animation](./assets/animation.gif)

デモ

### どんなゲーム

<http://fluxml.ai/experiments/cartPole/>

### AIの学習の様子

```
$ python3 dqn.py
```

## 実現の仕方



## 今後の発展

* いろんなフォームデータから、結果を推測・分類するタスクに活用できそう
  * 与信判断？ プロジェクト健康度判断？ 
* Word2VecでテキストのVectorを強化
* CNN/RNNで精度向上？

### Usage

```
$ python3 dqn.py
```


## 参考

[1] <http://fluxml.ai/experiments/cartPole/>

[2] <https://medium.freecodecamp.org/an-introduction-to-reinforcement-learning-4339519de419>

[3] <https://keon.io/deep-q-learning/>









![animation](./assets/animation.gif)

