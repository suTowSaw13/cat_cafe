# 猫カフェサイト

- レスポンシブ対応
- リセットCSS
- Google Mapの埋め込み
- OGP導入
- Google Fonts導入
- 「favicon.ico」「apple-touch-icon.png」を設置
- Sass導入
- PostCSSを利用してのベンダープレフィックスの自動付与


# clone後の、Sass、PostCSS対応
プロジェクトのクローン後、`npm install` にて、package.jsonに記述されているパッケージをインストールする。

コマンドプロンプトにて、`npm run watch:sass`を実行。scssファイルに編集を加えるたびに、編集が反映されたcss/.cssファイルが作成。

コマンドプロンプトにて、`npm run postcss`を実行。作成済みのcss/.cssファイルにベンダープレフィックスを自動付与。

# 参考
以下、書籍を参考。

『HTML&CSS Webデザイン 現場レベルのコーディング・スキルが身につく実践入門』

『1冊で身につく　HTML&CSSとWebデザイン入門講座』

『1冊で身につく　HTML&CSSとWebデザイン実践講座』

『Web制作者のためのSassの教科書』
