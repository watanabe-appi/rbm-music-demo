# RBM 作曲デモサイト

## 公開サイト

[https://watanabe-appi.github.io/rbm-music-demo/](https://watanabe-appi.github.io/rbm-music-demo/)

## デプロイ

`main`ブランチに`push`するとビルドが走ってGitHub Pagesで公開される。

## ローカルでのテスト

リポジトリで

```sh
hugo --minify
```

を実行すると`public\index.html`が作成されるので、それを確認する。もしくは

```sh
hugo server 
```

を実行してブラウザで[http://localhost:1313/](http://localhost:1313/)を閲覧する。

