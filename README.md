# 文鳥パフェ育成 ストアリダイレクト
## AppStore
- https://apps.apple.com/app/id1461042810

## GooglePlay
- https://play.google.com/store/apps/details?id=com.kamakurablog.suzuran.suzuran2018buntyo.dist

## URL
- http://MOCHIZUKI-Jun.github.io/AppRedirectBuntyo

## 短縮URL
- https://bit.ly/35L4aCV

## Memo
- twitterではonelinkのサービスのリンクがスパム扱いされたので、githubを利用したリダイレクトを使用
- URL短縮サービスはGoogleのサービスが提供停止になったので、ひとまず以下を利用。こちらはtwitterで今の所(2019.10.20現在)スパム扱いされていない
  - https://bitly.com

## Fork
- yasuakiohamaさん
- https://github.com/yasuakiohama/redirect
- ご提供ありがとうございます。

## 使い方 (Fork元のREADMEより引用し一部編集)

- `index.html` の各OS分岐のURLを適宜修正

```
cd yourRepository/
git checkout --orphan master
git add index.html
git commit -a -m "First pages commit"
git push origin master

```
- リポジトリの `Settings `から `GitHub Pages` でProject Pageを有効化
- ここにアクセスするとOS別にリダイレクトして他のURLに移動できる
  - http://yourself-account.github.io/yourRepository