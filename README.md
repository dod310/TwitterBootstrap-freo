# TwtterBootstrap-freo

[Twitter Bootstrap](http://twitter.github.com/bootstrap/)を[freo](http://freo.jp)に適用させたhtmlテンプレートです。
※ **2012年の2月に作成してほぼ変更していません。**

## ライセンス
freoとTwitter Bootstrapのライセンスに順じます。

### freoのライセンス
> 配布しているプログラムは、個人・法人を問わず、自由に利用・複製・改変・再配布することができます。
> 各フッター部分に表示している著作権表記は、削除したければ削除可能です。
> プログラム内の著作権表示とライセンスの文章は削除できません。
> 再配布の際に対価を要求することもできますが、再配布物にはGPLを適用しなければなりません。
> <http://freo.jp/about/license.html>

### Twitter Bootstrapライセンス
> Apache License
> Version 2.0, January 2004
> http://www.apache.org/licenses/
> <https://github.com/twitter/bootstrap/blob/master/LICENSE>

## ファイルのアップロード

ダウンロード後、templatesフォルダ、cssフォルダ、jsフォルダとimgフォルダを適用させるfreoのそれぞれのフォルダへアップロード、上書きして下さい。

## 表紙の変更方法
freoデフォルトのhtmlテンプレートとは異なり、このテンプレートでは、

<code>templates/index.html</code>が、サイトの表紙のhtmlテンプレート
<code>templates/default.html</code>が、ブログ記事一覧表示部分のhtmlテンプレート
となっております。

上記2つのhtmlテンプレートを<code>internals/default/default.html</code>内で条件分岐して表示させていますので、

表紙が必要無い場合は、<code>internals/default/default.html</code>2行目の<code>index.html</code>を<code>default.html</code>に書き換えて下さい。

## サンプル

* [サンプルページ](http://metal-mad.com/demo/g010/index.html)

またこのテンプレートについて<http://metal-mad.com/view/24>でも記してあります。

## 連絡先

* [Website](http://metal-mad.com)
* [Twitter](https://twitter.com/metalmadcom)