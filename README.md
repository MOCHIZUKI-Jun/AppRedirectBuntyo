# 文鳥パフェ育成 ストアリダイレクト
## AppStore
- https://apps.apple.com/app/id1461042810

## GooglePlay
- https://play.google.com/store/apps/details?

## 短縮URL
- xxx

## Memo
- twitterではonelinkのサービスのリンクがスパム扱いされたので、githubを利用したリダイレクトを使用
- URL短縮サービスはGoogleのサービスが提供停止になったので、ひとまず以下を利用。こちらはtwitterで今の所(2019.10.20現在)スパム扱いされていない
  - https://bitly.com

## Fork
- yasuakiohamaさん
- https://github.com/yasuakiohama/redirect
- ご提供ありがとうございます。

## 使い方
- Fork元のREADMEより引用

```cd yourRepository/
git checkout --orphan gh-pages
git rm -rf . #これは別にやらなくてもいいかも
echo "My GitHub Page" > index.html
git add index.html
git commit -a -m "First pages commit"
git push origin gh-pages

ここにアクセスするとOS別にリダイレクトして他のURLに移動できる
http://yourself-account.github.io/yourRepository```
