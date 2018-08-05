# 問題制作の演習

# 進め方
## はじめてのとき
* [GitHub](https://github.com/)のアカウントを作成してください
* [Travis CI](https://travis-ci.org/) のアカウントを作成してください
* GitHubのアカウントを[こちらのフォーム](https://goo.gl/forms/anAdoxqPKVt8sJGZ2)から教えてください。
## 毎回の進め方
* このリポジトリをforkしてください
* Travis CI を設定して、自動ビルドが通るようにしてください
   * Travis CI のGitHubアカウントでの登録とforkしたリポジトリをTravisCI側で許可する
   * 参考サイト：[Travis CI入門 Travis CIとGitHubでCIを実現する方法(Change the World!)](http://changesworlds.com/2014/09/introduction-to-travis-ci-and-github-001/)
* forkしたリポジトリの README.md ファイルの「t-kougei-game-comp」の部分を自分のGitHubアカウント名に差し替えてください(2箇所)
* 問題を解いて、テストを通るようにしてください。
* fork 元の master ブランチにプルリクエストを投げてください

# テスト結果

[![Build Status](https://travis-ci.org/t-kougei-game-comp/create.svg?branch=master)](https://travis-ci.org/t-kougei-game-comp/create)

# 今回の問題

あなたが問題を作る番です。

今まで行ってきた課題と同様な形式で、面白い課題を作成してください。

input?.txt ファイルを標準入力として読み込んで、標準出力の結果を output?.txt ファイルと一致するか比較するテストをします。
テストの回数を増やす場合は、「travis.yml」に追記してください。

main.c ファイルだけを書き換えるようにしてください。

## 入力される値
入力のフォーマットを与えてください。
~~~
a
b
c
d
e
~~~
それぞれの入力の説明をしてください。

## 期待する出力

プログラムを動作させた後の出力を記述してください。

最後は改行し、余計な文字、空行を含んではいけません。

## 条件
すべてのテストケースで満たされる条件を記述してください。

各条件について、成り立つ場合と成り立たない場合の両方のテストケースがあることが望ましいです。

## 入力例1
~~~
1
~~~
入力したデータの意味が説明されているとなおよいです。

## 出力例1
~~~
1
~~~

## 入力例2
~~~
2
~~~

## 出力例2
~~~
2
~~~
