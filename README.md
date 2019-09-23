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

