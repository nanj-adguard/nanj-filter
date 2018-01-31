<!DOCTYPE html>
<html lang="ja">
<head>
<meta http-equiv="Content-Type" content="text/html; charset=utf-8">
</head>
<body>
<p>お知らせ(1/31)：なんJフィルターはなんJ改修フィルターに名称が変更されました。<br>
なお、wikiの書き換えの手間や既に辞書の予測変換にURLを登録した人のことなどを考慮して、URL上の名称変更はしていません。</p>
<p>なんJ改修フィルターは、AdGuardを日本語ウェブサイトで使う際の不都合と280blockerをAdGuardで使う際の不都合を解消するために<a href="http://wikiwiki.jp/nanj-adguard/">外部のwiki</a>で開発した簡易的なフィルターです。<br>
280blockerをメインで使うことを前提に不具合等を解消するためのルールだけをリストにしており、広告をブロックするためのフィルターではないので、単独で使用することはできません。</p>
<p>◇フィルター作成所<br>
<a href="http://wikiwiki.jp/nanj-adguard/?%A5%D5%A5%A3%A5%EB%A5%BF%A1%BC%BA%EE%C0%AE%BD%EA">http://wikiwiki.jp/nanj-adguard/フィルター作成所</a></p>
<p>◇フィルター本体<br>
<a href="https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt">https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt</a></p>
<p>◇使い方<br>
<a href="https://280blocker.net/files/280blocker_adblock.txt">280さんのフィルター</a>をインポートした後で、「インポート」をタップして「既存のルールを上書きする」のチェックを外して、テキストボックスに<a href="https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt">https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt</a>をコピペしてください。<br>
一応管理人がチェックするつもりですが、元々は誰でも編集できるwikiで作られているフィルターなので<br>
1.不正な改変がされていないか各自チェックしてからコピペすること<br>
2.動作がおかしくなったらユーザーフィルターを削除して元に戻すこと<br>
3.何らかのトラブルがあっても自己責任であること<br>
を心掛けて使用してください。</p>
<p>◇コンセプト<br>
AdGuard社のフィルターは日本語ウェブサイト・アプリへの対応が不十分です。一方、280さんのフィルターは原則としてiOSの280blockerでの利用を前提にしており、AdGuard for Androidでの使用に特化したルールは盛り込まれていません。そこで、AdGuardで280さんのフィルターを使用することを前提として、このような不都合を解決するための追加フィルターを作成します。</p>
<p>◇対象ルール<br>
1.AdGuardのフィルター（DNSブロックを含む）を日本語ウェブサイト・アプリで使用した場合に発生する問題を解決するためのルール<br>
　i.日本語ウェブサイト・アプリでの不具合を解消するルール<br>
2.280さんのフィルターをAdGuardで使用した場合に発生する問題を解決するためのルール<br>
　i.280さんが対象外としているAndroid専用の広告やAndroidアプリの広告に対応するルール<br>
　ii.AdGuardの不具合によって正常に動作しないルールを改善するルール<br>
　iii.AdGuard独自記法によってさらにブロック性能を高めるルール<br>
基本的にどのような設定（DNSブロック、HTTPSブロックなどのオンオフ）でも問題が起きないルールをまとめます。</p>
<p>◇なんJ改修フィルターのtxt化について<br>
なんJ改修フィルターはwiki内で有志たちが作成・公開したものであり、誰でも追加・編集できますが、txt化については現在個人で行っています。<br>
ですからwikiで公開されているものとtxt化されたものでは更新速度が変わってしまうと思われます。<br>
最新のルールを使いたい方はwikiのルールを直接コピペする方法をとって、更新速度にこだわりのない方だけがこのtxtを利用してください。<br>
このtxtの管理をしている人は最低でも3日に1回以上はwikiを確認するつもりですから、wikiの更新から1週間以上経っても反映されない場合は死んだと思って誰かが引き継いでください。</p>
<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="https://github.com/nanj-adguard/nanj-filter/">https://github.com/nanj-adguard/nanj-filter/</a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">nanj-filter.txt</span>.
This work is published from:
<span property="vcard:Country" datatype="dct:ISO3166"
      content="JP" about="https://github.com/nanj-adguard/nanj-filter/">
  日本</span>.
</p>
</body>
</html>
