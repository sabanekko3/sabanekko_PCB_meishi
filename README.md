# 2024年全ロボ用名刺

## 自己紹介  

一応名刺なのでまずは自己紹介から…。
豊田高専でロボコンをしておりますさばねっこと申します。  

2021/2022は豊田高専Aチームの回路班長としてロボコンに参加し、モタドラとか電源とかパワー系の回路をいろいろやってました。  

![2022高専ロボコン](images/200d13e1edeb7aeb4621d10bd0a8bd60774321cb2683db3dc9d3486487461e88.png)  
↑2022高専ロボコンの時のやつ。  

また2023の学生ロボコンにも豊田高専RoboSharpとして参加させていただきました。  

普段は趣味の電子工作をネットに垂れ流す遊びをしているので良かったら見ていってください。自作モーターとかテスラコイルとか~~コイルガン~~(検閲済み)とかいろいろやってます。  

[Twitter(X)](https://twitter.com/sabanekko1)  
[blog](https://sabanekko2.hatenablog.com/)  

もし何かあれば気軽にDMくださいね！  

## 基板概要  

この名刺は簡単に言えば †僕が考えた最強のユニバーサル基板† となっております。  
主な特徴として、

- USB type-Cポート  
- シリアル変換IC搭載
- USB-PDトリガー搭載
- 3.3V600mAのスイッチングレギュレータ搭載
- GND用ベタプレーン
- ターミナルブロックがそのまま挿せる穴径
  
があります。便利ですねー。  

## 作り方  

基本的には下に示した部品リストの部品を乗せて頂ければよいのですが、PDトリガーICのCH224Kに関してはIC裏面にGNDパッドがあるため頑張らないといけません。  

はんだ付けの流れの例を示します。  

まず、ソルダーペーストと爪楊枝を用意します。  

![picture 0](images/7b7158c65a71f530a62f639ab4d54b4f3b25a5d2580cffbbd6db8dafe72ffbca.png)  

爪楊枝でいい感じの量のペーストを取って基板に塗ります。  
量はそれほど多く無くてかまいません。また、ICの足は後からはんだごてではんだ付けすればいいだけなので塗っても塗らなくても大丈夫です。  

いつか塗り方の例の写真追加します…。  

ペーストを塗ったらICを乗せて…

![picture 1](images/e4c577a995b3a33eaf632f2934e80683fdf3ca91f98127bd589d58cf79fc77a4.png)  

ヒートガン等で炙ります。  
ガス式のはんだごて等があると便利なのでおすすめ。  

![picture 2](images/b9fcb449eb21bc8b3b69acbd80e6964fca3effcbdf530aebc6f53f64922d2339.png)  

しばらく炙ればこんな感じではんだ付け完了です。  

![picture 3](images/a0d867894e4d19fac31ef124994bead8bb02409c622e59683ff3a62f8320887a.png)  

仕上げに普通のはんだごてで余分なはんだを取り除いて、浮いている足があればはんだ付けしましょう。  

## 使い方  
