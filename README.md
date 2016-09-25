# sandbox-ogp

OGP について、試すリポジトリ。

OGP については、次を参照。

http://ogp.me/

## refs

参考にした情報

### ウェブ管理者 - シェア機能 - ドキュメンテーション - 開発者向けFacebook

https://developers.facebook.com/docs/sharing/webmasters#markup

### デバッガー - 開発者向けFacebook

https://developers.facebook.com/tools/debug/

### SEO嫌いにお送りするSEO策。これでもうSEOについてしばらく考えなくて良いぜ！！

http://qiita.com/taiyop/items/050c6749fb693dae8f82


## note

1. using-opg.html に対して、デバッガーを使用した結果
![debugger1](./ogp-debugger-warning-before.png)
2. `ogp:title`、`ogp:url` をそれぞれ改善して、再度、デバッガーを使用した結果
![debugger2](./ogp-debugger-warning-after.png)
3. og のそれぞれのプロパティも意図した通り認識されている。
![debugger3](./open-graph-properties.png)
4. Facebook でのシェアプレビュー。綺麗に表示されている模様。
![debugger4](./facebook-share-preview.png)

