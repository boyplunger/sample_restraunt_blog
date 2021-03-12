# 簡易ブログアプリ
オススメのご飯屋さんのメニューを紹介する簡易ブログアプリです。

### 実装されてる機能の一覧

- deviceを使ったユーザー管理とログイン・ログアウト機能
- ブログ機能
- コメント機能
- お気に入り機能
- 検索機能
- 画像アップロード機能
- フォロー機能
- カテゴリー(タグ)機能
- 多言語化対応
- ページネーション
- Rspecを使ったテスト
- CircleCIによる自動テスト

### ローカルで動かす
GitHubからpullしてきたらプロジェクトフォルダに移動して、`./qs init --webpack`してください。

```
$ git clone https://github.com/belion-freee/sample_restraunt_blog.git <Project name>
$ cd <Project name>
$ ./qs init --webpack
```

`http://localhost:3000`にアクセスするとアプリが利用可能です。

以降の開発では `./qs server` でアプリを起動してください。

seedで初期アカウントを登録してるので、すぐに動作確認できます。
```
# You can use those accounts

name: "hoge"
email: "hoge@sample.com"
password: "Password"

name: "foo"
email: "foo@sample.com"
password: "Password"
```

ログイン・ログアウト機能
![douga1](https://user-images.githubusercontent.com/69951545/110927918-96d0c080-8369-11eb-87a7-6b71a7a27ae3.gif)

検索機能
https://user-images.githubusercontent.com/69951545/110958218-d3171780-838f-11eb-8d99-b7aa38d219d2.mov

