<!--
@masaquid
debug url: https://poo-it-masaquid.c9users.io
-->
# じゃんけんゲーム @masaquid

## 概要

友人がRubyの勉強を始め、最初の課題としてじゃんけんゲームを作る事になった
自分でプログラムを作ってみた上で、他人のソースを見ると勉強しやすいと思うので
暇すぎて忙しい僕も作ってみることにした

- 言語はRuby
- 入出力の形式は問わない (標準入出力でも何でも良い)
- というかRuby使用する以外はなんでも良いので適当に

### 基本仕様

- [ ] ボタンを押下でゲームスタート
- [ ] 手持ちのコインから3枚減らす
- [ ] 自分の出せる手を表示・選択
- [ ] 相手の手を表示（可能であれば少し時間をあけた後に）
- [ ] 勝利の場合、5枚～10枚の抽選された（ランダム）枚数獲得
- [ ] 敗北の場合、コイン獲得無し
- [ ] 規定枚数（100枚）とかに達した時点でゲーム終了
- [ ] 特別なメッセージを流す（おめでとうワレ）

### ぼくの課題
class化するのは、最初はわかりにくいと思うので避けてあげる
mozuleとかも避ける
gemは使わない
簡単にテストしたら if より case の方が早いみたいなので適宜使う