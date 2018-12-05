
## 20181205LT

---

PC・スマホ両方から○○がしたい

---

Webアプリ

Note:

が結局最良では?
と、昔から思ってた

---

爆速でWebサービスを作って公開する

---

```
`#Webサービス開発RTA`
```

Note:

ちょっと前にTwitterやQiitaなどでもバズってた

---

`「#いいねvsRT」画像メーカー`

![hoge](img/web-rta.png) <!-- .element width="60%" -->

Note:

Aだったらいいね、BだったらRTみたいなツイートがよくある。
画像を簡単に用意できるサービス。
新幹線に乗っている間に作ったらしい。

---

- GitHub Pages <!-- .element: class="fragment highlight-red grow" -->
- javascript
- bootstrap4
- canvas

---

サーバーの設定を極力考えない

---

![node](img/nodejs.png)

Note:

Nodejs×React・Vueを画像にしたい

---

- インストールして`npm start`でサーバー立てられる。
- ポートもコードで指定できる
  - 環境に依存しない


---

# React Or Vue

![next](img/next.png) <!-- .element width="300px" -->

![nuxt](img/nuxt.png) <!-- .element width="300px" -->

Note:

NEXT.js:react NUXT:vueをラップして使いやすくしてる

---

サンプルが豊富

![github-sample](img/github-sample.png) <!-- .element width="60%" -->

Note:

nextやnuxt
GitHubにSampleコードがたくさん

---

Heroku

(へろく)<!-- .element: class="fragment" -->

---

# 勧める理由 1/4

- 言語毎のチュートリアルが親切
- やってみた系の記事もよく見かける

---

![heroku-tutorial](img/heroku-tutorial.png)

---

nodeは勿論、他の言語も

画像

---

# 勧める理由 2/4

GitHubへPushしたら自動Deploy

Note:

しかも、チュートリアルに組み込まれてる

---

# 勧める理由 3/4

PluginでDBを簡単用意

Note:

結構大きいと思ってる
アドオンで例えばMongoDBが使える。
クレカ登録する必要はあるけど、無料で使える。
ClearDB MySQLとか

---

![heroku-addon](img/heroku-addon.png)

---

# 勧める理由 4/4

- 基本無料
  - 無料で5アプリ(※)

Note:

1月110時間しか使えないけど、30分間動作がなければ自動スリープしてくれる

---

詳しくは[Web](https://jp.heroku.com/)で!

