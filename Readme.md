# フィルター作成所
<http://wikiwiki.jp/nanj-adguard/?%A5%D5%A5%A3%A5%EB%A5%BF%A1%BC%BA%EE%C0%AE%BD%EA>
# フィルター本体
<https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt>
# なんJ改修フィルターとは
なんJ改修フィルターは、[なんJ AdGuard部](http://wikiwiki.jp/nanj-adguard/)で開発された簡易的なフィルターです。  
# コンセプト
AdGuard社のフィルターは日本語ウェブサイト・日本語アプリへの対応が不十分です。一方、280さんのフィルターは原則としてiOSの280blockerでの利用を前提にしており、AdGuard for Androidでの使用に特化したルールは盛り込まれていません。そこで、AdGuardで280さんのフィルターを使用することを前提として、このような不都合を解決するための追加フィルターを作成します。  
完成したフィルターはパブリックドメイン（CC0）とし、著作権を放棄して複製・頒布・改変・営利目的利用など誰でも自由に利用できるものとします。  
完成したフィルターを利用したことに起因するいかなる損害に対してもwiki及びtxtファイルの管理人は一切の責任を負いません。
# 対象ルール
- AdGuardのフィルター（DNSブロックを含む）を日本語ウェブサイト・日本語アプリで使用した場合に発生する問題を解決するためのルール 
    - 日本語ウェブサイト・日本語アプリでの不具合を解消するルール
    - 日本語ウェブサイトのアンチ広告ブロックスクリプトに対応するルール
- 280さんのフィルターをAdGuardで使用した場合に発生する問題を解決するためのルール 
    - 280さんが対象外としているAndroid専用の広告やAndroidアプリの広告に対応するルール
    - AdGuardの不具合によって正常に動作しないルールを改善するルール
    - AdGuard独自記法によってさらにブロック性能を高めるルール

基本的にどのような設定（DNSブロック、HTTPSブロックなどのオンオフ）でも問題が起きないルールをまとめます。
# 使い方
1. 280さんのフィルターをインポートした後で、「インポート」をタップして **「既存のルールを上書きする」のチェックを外して** 、テキストボックスに<https://raw.githubusercontent.com/nanj-adguard/nanj-filter/master/nanj-filter.txt>をコピペしてください。  
2. [なんJ AdGuard部フィルター作成所](http://wikiwiki.jp/nanj-adguard/?%A5%D5%A5%A3%A5%EB%A5%BF%A1%BC%BA%EE%C0%AE%BD%EA)にアクセスして、「最新チェック」からインポート（または更新）ができたかを確認してください。  

なお、なんJ AdGuard部はこのフィルターをパブリックドメイン（CC0）とし、著作権を放棄しています。複製・頒布・改変・営利目的利用なども自由に行うことができます。
# 使用上の注意
元々は誰でも編集できるwikiで作られたルールなので、
- 不正な改変がされていないか各自チェックしてからインポートすること
- 動作がおかしくなったらユーザーフィルターを削除して元に戻すこと
- 何らかのトラブルがあっても自己責任であること

を心掛けて使用してください。
# なんJ改修フィルターのtxtファイル化について
なんJ改修フィルターはwiki内で有志たちが作成・公開したものであり、誰でも追加・編集できますが、txtファイル化については現在個人で行っています。  
ですからwikiで公開されているルールがtxtファイルに反映されるまでにはタイム・ラグが生じてしまうと思われます。  
最新のルールを使いたい方はwikiのルールを直接コピペする方法をとって、更新速度にこだわりのない方だけがこのtxtファイルを利用してください。  
このtxtファイルを管理している人は最低でも3日に1回以上はwikiを確認するつもりですから、wikiの更新から1週間以上経っても反映されない場合は死んだと思って誰かが引き継いでください。

<p xmlns:dct="http://purl.org/dc/terms/" xmlns:vcard="http://www.w3.org/2001/vcard-rdf/3.0#">
  <a rel="license"
     href="http://creativecommons.org/publicdomain/zero/1.0/">
    <img src="http://i.creativecommons.org/p/zero/1.0/88x31.png" style="border-style: none;" alt="CC0" />
  </a>
  <br />
  To the extent possible under law,
  <a rel="dct:publisher"
     href="http://wikiwiki.jp/nanj-adguard/">http://wikiwiki.jp/nanj-adguard/</a>
  has waived all copyright and related or neighboring rights to
  <span property="dct:title">nanj-filter.txt</span>.
This work is published from：
<span property="vcard:Country" datatype="dct:ISO3166"
      content="JP" about="http://wikiwiki.jp/nanj-adguard/">
Japan</span>.
</p>
