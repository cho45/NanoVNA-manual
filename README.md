About this repository
=====================

This repository includes unofficial NanoVNA user guide written in Japanese.

If you want to read in English, you can Google Translate or Microsoft Translator as following:

 * https://translate.google.co.jp/translate?sl=ja&tl=en&u=https%3A%2F%2Fcho45.github.io%2FNanoVNA-manual%2F
 * https://www.translatetheweb.com/?from=ja&to=en&a=https://cho45.github.io/NanoVNA-manual/

このレポジトリについて
======================


Github Pages で処理されることを想定しており、jekyll で HTML に変換されます。

## localhost でプレビューする場合

### 必要なもの

 * ruby
 * bundler

bundle コマンドがない場合 bundler をインストールします

```
gem install bundler
```

localhost:4000 でサーバーを起動

```
bundle exec jekyll serve
```

http://localhost:4000/NanoVNA-manual/ で見れるようになります。

