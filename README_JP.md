# PhoneFriend With SmartSpeaker Architecture

## 概要
AIキャラクター (以下character)と、AIアシスタント(以下assistant)を分離しつつ、同一の会話空間に置くことで、キャラクター性を阻害せず、アシスタントの実用性を実現する仕組みです。

`PhoneFriend With SmartSpeaker`の命名の由来は、「電話越しの友人」(AIキャラクター)と、「スマートスピーカー」(AIアシスタント)を二人で使う、という光景を意味します。

## 従来手法の問題点



## 動作の例

### 通常ケース1
```
USER: こんばんは
CHARACTER: こんにちは！今日も元気かな？

USER: 電気をつけて
CHARACTER: 了解！ @assistant 電気をつけて
ASSISTANT: 居間の電気を点灯しました。
CHARACTER: 電気付けたよ！

USER: あ、やっぱいいや。 @assistant 電気消して
ASSISTANT: 居間の電気を消灯しました。
CHARACTER: あれ、消しちゃうんだ？
```

### 通常ケース2
```
USER: こんばんは
CHARACTER: こんにちは！今日も元気かな？

USER: 電気をつけて
CHARACTER: 了解！ @assistant 電気をつけて
ASSISTANT: 居間の電気を点灯しました。
CHARACTER: 電気付けたよ！

USER: あ、やっぱいいや。 @assistant 電気消して
ASSISTANT: 居間の電気を消灯しました。
CHARACTER: あれ、消しちゃうんだ？
```




### character単体のよくある例


### assistant単体





