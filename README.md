

# 学習中に参考になったサイトや情報のメモ


- githubはbranchをpushしても草が生えないのか？
gitの設定Default branchを切り替えれば草が生えた
その代わりmain/branch切り替えで草も切り替わる

GitHub Pagesを設定すればできそう
調べる必要あり


- gitbranch切り替え
git switch branch名

- ワークツリーからステージへ記録
git add ファイル名
全ての変更内容をステージへ
git add .

- ステージからローカルリポリトジへ
git commit -m "commit名"

- gitの最初に行うこと、初期化
git init

- git branchの一覧
git branch
github含めた全ての一覧
git branch -a

- pumeの停止
[ec2-user@ip-xx-xx-xx-xx アプリケーション名]$ sudo kill $(cat tmp/pids/puma.pid)

- slick 画像スライドショー
https://qiita.com/Yusuke_Hoirta/items/309bac88a4f75b58128b

- slick 読み込み後画像が縦並びとなってしまう
https://qiita.com/Rairu_blog/items/e6382a64ba4457545069
Jsファイルに「turbolinks:load」を追加した
turbolinks:load イベントは、新しいページが表示された後に再実行されるJavaScriptコードを提供します。

- slick画面サイズによる調節がうまくいかない
画面サイズが大きくなると次のスライドが映り込んでいる
variableWidth: true,のコメントアウト
画像それぞれにサイズを持たせる時使用

- git commitメッセージ修正
git commit --amend -m ""

