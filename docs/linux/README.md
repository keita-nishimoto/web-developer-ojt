# Linuxの基礎知識

## Linuxの概要

OSの一種です。

OSとはオペレーティングシステムの略で、コンピュータを操作する為の基本的な機能を提供します。

Linux以外だと [Microsoft Windows](https://ja.wikipedia.org/wiki/Microsoft_Windows) や [macOS](https://ja.wikipedia.org/wiki/MacOS) 等があります。

1991年に当時フィンランドの大学生だった「リーナス・トーバルズ」氏によりUNIXを参考に開発・公開されました。

UNIXに関しては [こちらの記事](https://eng-entrance.com/unix_linux) が詳しいので見てみて下さい。

UNIXベースで一番身近なOSだと [macOS](https://ja.wikipedia.org/wiki/MacOS) があります。

## Linuxの特徴

以下のような特徴があります。

- オープンソース（誰でも無料で使えるしソースコードの改変も自由）
- 軽量なので比較的古いPCでも動く
- GUI（Character User Interface）が中心の操作

## Linuxの利用用途

オープンソースという特性上、世界中の様々な箇所で使われています。

一番身近な例だとスマートフォンに搭載されている、AndroidはGoogleが開発したLinuxベースのOSです。

## Linuxを学ぶ目的

WebエンジニアにとってもWebサービスを提供する為のWebサーバやデータを永続化する為のデータベースサーバを作成する際にLinuxを利用するのが一般的です。

よってWebエンジニアにとってはLinuxは必須スキルとなります。

## カーネル

OSの中核となる部分でハードウェアと直接やり取りするもっとも中心的な機能を受け持ちます。

カーネル以外の部分をユーザランドと呼び、ファイルシステム、ファイル操作コマンド、シェルなどの基本的なソフトウェア郡を指します。

## Linuxディストリビューション

ごく一般の利用者が利用する際にはカーネルをダウンロードしただけでは、コンピュータを利用出来る状態に持っていくのは難しいでしょう。

そこでカーネルに様々なオープンソースソフトウェアを組み合わせて、インストーラーと一緒に配布しています。

これをLinuxディストリビューションと呼びます。

### Linuxディストリビューションの種類

[Linuxディストリビューション](https://ja.wikipedia.org/wiki/Linux%E3%83%87%E3%82%A3%E3%82%B9%E3%83%88%E3%83%AA%E3%83%93%E3%83%A5%E3%83%BC%E3%82%B7%E3%83%A7%E3%83%B3)
にはたくさんの種類があります。

主にDebian系、 Red Hat系、 Slackware系があります。

※ Slackware系は玄人向けで現状はあまり利用されていない。

それぞれが目的にあったカスタマイズがされており、その中から用途にあった物を選ぶのが良いでしょう。

例えば普通の個人PCとして利用するなら、Debian系の[Ubuntu](https://www.ubuntulinux.jp/) 、

サーバ用途として利用するならRedHat系の[CentOS](https://www.centos.org/) 等を選択します。

本カリキュラムではRedHat系の [Amazon Linux](https://aws.amazon.com/jp/amazon-linux-ami/) を利用して学習を進めます。

理由はAmazon LinuxはAWS上で利用が推奨されているディストリビューションなので学習を進める上で効率が良いと判断した為です。

使い方も [CentOS](https://www.centos.org/) によく似ています。

## Linuxの学習方法

まずは使って見るのが一番です。

[ojt-linux-vagrant](https://github.com/keitakn/ojt-linux-vagrant) というリポジトリを用意しました。

こちらは使って学習のほうを進めていきましょう。

使い方はリポジトリのREADMEに記載しておきます。

また体系的に学習をする為には [Linux標準教科書](http://www.lpi.or.jp/linuxtext/text.shtml) を読むのが良いでしょう。

無料でダウンロードが可能です。

最近公開された [Linuxの基礎用語を完全理解するためにエンジニアが作成した「10のミニプロジェクト」](https://gigazine.net/news/20210220-getting-better-linux-10-project/) もオススメです。
