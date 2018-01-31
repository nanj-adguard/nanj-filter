# お知らせ(1/31)
なんJフィルターはなんJ改修フィルターに名称が変更されました。なお、wikiの書き換えの手間や既に辞書の予測変換にURLを登録した人のことなどを考慮して、URL上の名称変更はしていません。
# なんJ改修フィルターとは
なんJ改修フィルターは、AdGuardを日本語ウェブサイトで使う際の不都合と280blockerをAdGuardで使う際の不都合を解消するために<a href="http://wikiwiki.jp/nanj-adguard/">外部のwiki</a>で開発した簡易的なフィルターです。  
280blockerをメインで使うことを前提に不具合等を解消するためのルールだけをリストにしており、広告をブロックするためのフィルターではないので、単独で使用することはできません。
# フィルター作成所
[http://wikiwiki.jp/nanj-adguard/フィルター作成所](http://wikiwiki.jp/nanj-adguard/?%A5%D5%A5%A3%A5%EB%A5%BF%A1%BC%BA%EE%C0%AE%BD%EA)
# フィルター本体
[https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt](https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt)
# 使い方
280さんのフィルターをインポートした後で、「インポート」をタップして**「既存のルールを上書きする」のチェックを外して**、テキストボックスに[https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt](https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt)をコピペしてください。  
元々は誰でも編集できるwikiで作られたフィルターなので、
1. 不正な改変がされていないか各自チェックしてからインポートすること
2. 動作がおかしくなったらユーザーフィルターを削除して元に戻すこと
3. 何らかのトラブルがあっても自己責任であること
以上を心掛けて使用してください。
# コンセプト
AdGuard社のフィルターは日本語ウェブサイト・アプリへの対応が不十分です。一方、280さんのフィルターは原則としてiOSの280blockerでの利用を前提にしており、AdGuard for Androidでの使用に特化したルールは盛り込まれていません。そこで、AdGuardで280さんのフィルターを使用することを前提として、このような不都合を解決するための追加フィルターを作成します。
# 対象ルール
1. AdGuardのフィルター（DNSブロックを含む）を日本語ウェブサイト・アプリで使用した場合に発生する問題を解決するためのルール
- 日本語ウェブサイト・アプリでの不具合を解消するルール
2. 280さんのフィルターをAdGuardで使用した場合に発生する問題を解決するためのルール
- 280さんが対象外としているAndroid専用の広告やAndroidアプリの広告に対応するルール
- AdGuardの不具合によって正常に動作しないルールを改善するルール
- AdGuard独自記法によってさらにブロック性能を高めるルール
基本的にどのような設定（DNSブロック、HTTPSブロックなどのオンオフ）でも問題が起きないルールをまとめます。
# なんJ改修フィルターのtxt化について
なんJ改修フィルターはwiki内で有志たちが作成・公開したものであり、誰でも追加・編集できますが、txt化については現在個人で行っています。  
ですからwikiで公開されているものとtxt化されたものでは更新速度が変わってしまうと思われます。  
最新のルールを使いたい方はwikiのルールを直接コピペする方法をとって、更新速度にこだわりのない方だけがこのtxtを利用してください。  
このtxtの管理をしている人は最低でも3日に1回以上はwikiを確認するつもりですから、wikiの更新から1週間以上経っても反映されない場合は死んだと思って誰かが引き継いでください。  
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
