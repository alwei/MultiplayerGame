Unreal Engine 4 マルチプレイヤーサンプル
=======================================================
対応Ver UE 4.21.0


解説
------
UE4を使って実装するマルチプレイヤーゲームのサンプルです。
ローカルPC上、もしくはLANを使ったネットワーク上で動作します。
サーバーのセッション作成、クライアントのマッチング、更にセッションの破棄を行うところまで一通り実装しています。
ブループリントのみでネットワークを使ったサンプルとして、かなり必要最低限の実装となっています。

基本的な使用方法
------------------
『Maps』フォルダーに『LoginMap』と『ExampleBattleMap』が格納されており、初期設定では『LoginMap』を読み込みます。
『Play』ボタン横から『MultiPlayer Options』の『Number of Players』を2人以上に設定してから、開始します。
まずホストとなるサーバー『Host to start』を選択し、レベル上にログインします。
その後はクライアント側で『Client to start』を選択し、以降は何人でもサーバー上のレベルへログイン可能です。

ゲームはWASDによる移動とマウスによるエイミングとシュート操作、更に左Shiftキーでクラウチング操作が可能です。
ライフゲージが存在するので、それが全てなくなるとそのプレイヤーの敗北となります。
ライフゲージがなくなるとセッションを出るか再度リスポーンするかを選ぶことができます。
ホストとなるサーバーがセッションを出ると全員が強制的に退出されるので注意してください。

※4.21でも動作するように修正を行いました。

プロジェクト全体について
-------------------------
基本的にテンプレート系の素材して使っておりませんが、プレイヤーキャラクターとなるGrayちゃんに関しては以下の規約に従って利用してください。
http://rarihoma.xvs.jp/products/graychan/

ぜひネットワークマルチプレイヤーゲームを学ぶ上での参考にしてください。

連絡先
------------------
Twitter : @aizen76

mail : altaizen76@gmail.com
