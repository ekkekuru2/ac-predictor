---
title: UserScript
---

## UserScript
UserScript 版の ac-predictor をインストールすることで、AtCoder ページ上にて推定パフォーマンス/レート変化等を確認できるようになります。
  
#### インストール
##### 1. UserScript を実行できる環境を用意する

ac-predictor では、TamperMonkey を推奨動作環境としています。自分のブラウザに合ったものを<a href=https://www.tampermonkey.net>公式サイト</a>からダウンロードしてください。
  
##### 2. インストールする
<a href=https://greasyfork.org/ja/scripts/369954-ac-predictor></a> よりインストールをして下さい。

#### 使い方
##### コンテストページでの確認
スクリプトをインストールすると、画面右側に黒い半透明のタブが表示されます。これをクリックすると表示されるサイドメニューにて、コンテストページ上より予測を確認することができます。


<b>順位</b>、<b>perf</b>、<b>rate</b> の入力欄に目標の数値を入力すると、それを達成する<b>順位</b>と達成したときの <b>perf</b>、 <b>rate</b> がそれぞれ表示されます。 <b>現在の順位</b>ボタンをクリックすることで、順位表取得時の自分の順位を入力できます。<b>更新</b>ボタンを押すことで、順位表情報を最新のものに更新できます。

##### 順位表での確認

順位表ページでは、順位表に表示されている人のパフォーマンスとレート遷移を確認できます。
