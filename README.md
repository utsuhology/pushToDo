# pushToDo
ToDoリストを作成して通知領域に表示するスマホアプリ

## アプリ概要
- push通知で、外にいる際に行う超小規模のToDoを管理する
- 外にいるときのToDoをどう管理するか、というお話
  - 家にいるときなら両手が開いてるからじっくりPC・スマホでTrelloとかを見ればいい
  - シーン例：
    - おつかいで買うものをメモ
    - 電池買おうと思ってたのに忘れちゃった
    - はがきを出し忘れた
    - 図書館に本を返し忘れた
- 通知領域はスマホに表示される情報の中で最もフットワークが軽い
  - すぐ確認できて、すぐ戻せる
  - 通知領域って何もなくてもなんとなく開いちゃうから、そこにToDoがあると意識しやすいとおもう
- 利用イメージ
  - https://twitter.com/Utsuhology/status/1093495356057313280

## 実装
- Cordova
  - 通知の実装は https://github.com/katzer/cordova-plugin-local-notifications を利用

## 利用について
- apk
  - プロジェクト直下のandroid-debug.apkをインストールするとアプリのお試しができます
  - なんかキャッシュファイルが解決できなくて「尿検査の容器とって」という僕が実際に使っていた片鱗が残ってしまっていますが気にしないでください（え？）
- ビルド
  - 環境によってはビルドできなかったりするかもしれませんが、よろしければどうぞ
