# JavaScript

JavaScriptの基礎を学びます。

最初はこのJavaScriptを使って、基礎的な構文やアルゴリズムのトレーニングをして行きましょう。

※ アルゴリズムというのは問題解決の手順の事でアルゴリズムの学習の際に詳しく解説します。

## JavaScriptの特徴

プロトタイプベースのオブジェクト指向言語で主にWebブラウザで動作します。

昔は癖があり使いくいという印象を持たれる事も多かった言語ですが、最近はモダンな機能等も取り入れられているので、そのような印象は大分薄くなったのではないでしょうか。

詳しくは [wikipedia](https://ja.wikipedia.org/wiki/JavaScript) を参照してみて下さい。

## なぜJavaScriptを最初に学習するのか？

私が最初に学ぶべき言語としてJavaScriptをオススメする理由は下記の通りです。

### 理由1フロントエンド（ブラウザ）でもサーバでも利用出来るから

JavaScriptはブラウザでしか動かないというイメージは過去の物です。

[Node.js](https://nodejs.org/ja/) の登場でサーバでも実行させる事が可能だという点が選定理由の1つ目です。

### 理由2多くのプロジェクトで使われているので学習した内容がながく使える可能性が高い

[Node.js](https://nodejs.org/ja/) の恩恵はサーバ側でJavaScriptが実行出来るようになった事だけではありません。

[npm](https://www.npmjs.com/) という強力なパッケージ管理システムの存在により、ブラウザでもサーバでも実行出来る様々なパッケージが利用出来ます。

これらを利用する事で自分で1からプログラムを作るよりも開発速度を大幅に短縮出来ます。

※ 他の言語にもパッケージ管理システムはあります。Rubyの[RubyGems](https://rubygems.org/) やPHPの[composer](https://getcomposer.org/) 等ですね。

このパッケージ管理システムとブラウザ、サーバ両方で動くという性質上、ほとんどのプロジェクトで [Node.js](https://nodejs.org/ja/) が利用されています。

サーバサイドの言語に関してはNode.jsを使わずにRubyやPHPを利用しているケースも多いですが、Web開発だとフロントエンド（ブラウザ）では、事実上JavaScriptの一択です。

参加するプロジェクトによってサーバサイドの言語は様々な物（PHP, Ruby, Java等）がありましたが、JavaScriptが全く登場しないプロジェクトは1つもありませんでした。

よって習得した事を活かせる可能性が高いという点がメリットになります。

### 理由3ブラウザで動かす事だけを考えるなら開発環境の用意が非常に簡単

[Node.js](https://nodejs.org/ja/) を使わなくてもシンプルに動かすだけならWebブラウザとテキストエディタだけあれば開発を進められます。

Webエンジニアを目指すのであれば開発環境構築のスキルは必須ではあるのですが、初心者はここで挫折してしまう可能性が結構高いので、この点は結構なメリットだったりします。

### 理由4言語仕様がモダン（現代的）になってきている

JavaScriptは [ECMAScript](https://ja.wikipedia.org/wiki/ECMAScript) という標準仕様によって仕様が策定されています。

このバージョン5.1までは、正直なところを言うと、他の言語と比較して独自仕様や罠が多く、考慮しなければいけない点が多く存在していました。

しかし2015年に最新の言語仕様である、 ECMAScript 6(2015) が登場してから状況が大きく変わりました。

オーソドックスなオブジェクト指向プログラミングと、関数型言語のエッセンスなどを備えたモダンな言語に生まれ変わりました。

もしこの仕様がリリースされていなかったら私は最初に学ぶべき言語にJavaScriptをオススメしなかったと思います。

※ 補足ですが、ECMAScript 6以降はECMAScript 2015のような呼び方で呼ぶのが正しいそうです。

ネット上ではECMAScript 6とかES7（2017の事）みたいな呼び方をしている場合もありますがECMAScript 20◯◯ が正しい呼び方です。

## 学習の進め方

[ojt-node](https://github.com/keitakn/ojt-node) というリポジトリを作りました。

こちらを利用して学習を進めて行きましょう。

まずはREADMEの手順の通りに動かしてみて下さい。

※ 動作させるには [こちらの課題](https://github.com/keitakn/web-developer-ojt/blob/master/docs/linux/task.md) が終わっている必要があります。

## 学習の際に参考にするリンク

学習の際に参考になるリンクをいくつか紹介させて頂きます。

### [MDN JavaScript リファレンス](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference)

mozillaの公式リファレンスです。

ネット上に公開されている記事等はあくまでも2次情報なので、ここで正しい仕様等を確認しましょう。

### [JavaScript入門](https://dotinstall.com/lessons/basic_javascript_v2)

動画形式で基礎的な構文がある程度身につきます。

本格的な学習に入るまでに一度やっておくといいでしょう。

## JavaScriptの学習の注意点

ネット上の記事は古い可能性があります。

特にJavaScriptはECMAScript 2015以降とそれ以前のバージョンで全く書き方が異なる部分があるので注意しましょう。

※ 今から習得するのであればECMAScript 2015以降の構文を覚えるのが良いでしょう。

見分け方の1つとして下記のように `var` を使って変数宣言を行っているケースは古い情報の可能性があります。

```javascript 1.8
var myName = 'K';
```

ECMAScript 2015以降では下記のように `const` を使っての変数宣言が一般的です。

```javascript 1.8
const myName = 'K';
```

現代的なJavaScriptを書く上でいくつか参考になりそうな記事を載せておきます。

### [イマドキのJavaScriptの書き方2018](https://qiita.com/shibukawa/items/19ab5c381bbb2e09d0d9)

少々極端な主張ですが、記事の内容は概ね同意出来ます。（筆者の方があえてそうしているのだと思っています。）

一点気になったのは、`function` による宣言は完全に捨てて良いと書いてあるところです。

確かにこの記事の通り `const` とアロー関数のみでだいたいの場面は対応出来ますが、ジェネレータ等一部ではまだ `function` が必要だったりします。

[関数宣言 vs 関数式 | ES2015+](https://qiita.com/raccy/items/aac3b8e3981564bbd1fa) でも関数宣言の方法は `const f = () => {};` を基本的に利用するのが良いと結論を出しています。

### [JavaScript 長く使える系の知識](https://qiita.com/yamadar/items/bfdfc58cec49bf2690e1)

基本を抑えておくという意味で一読しておくと良いと思います。

この記事に書いてある言葉で非常に良いと思った内容を引用させて頂きます。

>冒頭にも書きましたが、基礎知識は土台の様なものです。土台があれば、その上にあるものは自分で考えられます。新しい技術を目にしても、理解が容易になります。

まさにその通りだと私も考えます。

[IT技術の学習方法](https://github.com/keitakn/web-developer-ojt/blob/master/docs/tips/ITSkillLearningMethod.md) でも基礎を重視した学習オススメしています。

### [JavaScript初級者のためのコーディングガイド](https://qiita.com/raccy/items/bf590d3c10c3f1a2846b)

コメント欄でも白熱した議論がなされていますが、ここに書いてある事は概ね同意出来ると思いました。

一部の方が言われていますが、この記事には「何故そうするのか」という理由が記載されていません。（筆者の方があえてそうしている）

徐々にで良いので、1つ1つの項目に対して「何故そうするのか」を考えるようにしましょう。

疑問を持ち自ら考える事はエンジニアにとって非常に大切な事だと私は考えます。

例えば [「JavaScript初級者のためのコーディングガイド」に補足を試みる](https://qiita.com/ms2sato/items/94ed459640a1d89cb4de) を書いた方のように、自分なりの意見をアプトプット出来るようになると理想です。

### [【2018年版】今押さえておきたいフロントエンド関連](https://qiita.com/sawadays0118/items/88efc7c85caeb6d1bbd1)

こちらはJavaScriptに特化しているというよりはフロントエンドのWeb全般での最新テクニックが載っています。

内容盛りだくさんなので、ストックしておいてざっと眺めておくと良いでしょう。

### [2018年に見直した現代的なJavaScriptの記法を紹介するぜ](https://ics.media/entry/17262)

最新の言語仕様を分かりやすく解説している良記事です。

### 非同期処理に関する記事

JavaScriptでは非同期処理が非常に重要です。

非同期処理の核となる `Promise` の理解は必須です。

参考になりそうな記事を載せておきます。

- [JavaScriptの同期、非同期、コールバック、プロミス辺りを整理してみる](https://qiita.com/YoshikiNakamura/items/732ded26c85a7f771a27)
- [Promise と async/await の理解度をもう1段階上げる](https://qiita.com/SotaSuzuki/items/f23199e864cba47455ce)

`async/await` は Promiseをより簡潔に書けるようにした仕組みです。
まずは [async function](https://developer.mozilla.org/ja/docs/Web/JavaScript/Reference/Statements/async_function) を見て概要を理解しておきましょう。

下記の記事も分かりやすく解説されているのでオススメです。

- [async await の使い方](https://qiita.com/niusounds/items/37c1f9b021b62194e077)
- [async関数においてtry/catchではなくawait/catchパターンを活用する](https://qiita.com/akameco/items/cc73afcdb5ac5d0774bc)

## コーディング規約について

様々なコーディング規約がありますが、私のオススメは [Airbnb JavaScript Style Guide](https://github.com/airbnb/javascript) です。

オープンな議論を通じてスタイルが決定していること、スタイルについてパフォーマンスに関するエビデンスがあることがオススメの理由です。

GitHub上でも多くのスターを獲得しています。

本カリキュラムではこのAirbnbのスタイルで学習を進めていきます。

[日本語版](http://mitsuruog.github.io/javascript-style-guide/README.md) もあります。

ちなみに [JavaScript初級者のためのコーディングガイド](https://qiita.com/raccy/items/bf590d3c10c3f1a2846b) でもAirbnbのスタイルを推しています。

最近では [Prettier](https://github.com/prettier/prettier) や [ESLint](https://eslint.org/) といったツールを利用しコードを整形するのが主流です。

コーディング規約を理解する事は大事ですが、実際のコード整形はツールに任せてしまったほうがミスがないので確実です。

- [Prettier 入門 ～ESLintとの違いを理解して併用する～](https://qiita.com/soarflat/items/06377f3b96964964a65d)
