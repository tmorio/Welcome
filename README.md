# Welcome to GitHub!
## GitHub is 何
バージョン管理システムのGitを使用したコードホスティングシステム。  
簡単に言えば、Gitの機能をサーバー上でもやってくれるサービスみたいなものです。
## Git is 何
ソースコードなどの変更履歴を追跡する分散型バージョン管理システム。  
(Git-Wikipedia)[https://ja.wikipedia.org/wiki/Git]
  
  
簡単に言えば、ソースコードの変更履歴を記録できるシステムです。  
例えばAさんがここを追加した、Bさんがこの部分を削除したと言うのを可視化してくれるものです。  
これにより、完成したソースコードをいちいちコピーする必要がなくなります。
## 学内でGit/GitHubを使う方法
学内LANだとGitHubにデータを送信するポートが塞がれている、そもそもGitが入っていないなどの問題があります。  
本来ならばコマンドを入力して、操作を行いたいところですが、ベースをこちらで用意しておくので今回はGitHubのWeb上から操作していきます。  
  
※ Git Portable版をインストールする、学内LANの規制を回避するなどの手段はありますが、今回は割愛します。  
## とりあえず編集してコミットしてみよう
とりあえず、このWelcomeレポジトリ(レポジトリとは**ファイルやディレクトリの状態を管理するデーターベースの一つ**という事で今は良いです)
にいくつかのHello Worldプログラムとテキストファイルを用意しました。  
まずは、テキストファイルを編集してみましょう。  
  
では上のファイルリストから「test.txt」を選択してみましょう。  
すると以下のような画面が出ると思います。
![1](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display1.png?raw=true "1")  
この画面はファイルの内容を見ることができます。  
では、早速編集してみましょう。編集するには、右側の鉛筆のマークを選択します。  
![2](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display2.png?raw=true "2")  
すると、ファイルの編集画面が出ます。という事で、何か適当に追記してみて下さい。  
![3](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display3.png?raw=true "3")  
追記できましたか?  
今回は例として「Javaは良いぞ。」と追記しました。※Javaを贔屓にしている訳ではありません。  
![4](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display4.png?raw=true "4") 
では、下にスクロールして「**Commit changes**」の画面を出します。  
![5](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display5.png?raw=true "5") 
この欄の書き方についてですが、そのままでも構いません。ですが、何度も「**Update ファイル名**」という記録ができてしまい、ややこしくなるので、上の欄には「**自分が行なった作業の簡単な説明**」を入れておくと、後から変更履歴を見たときに見やすくなります。下の欄は空欄でも構いませんが、ややこしい作業や新しくコードを挿入したときは簡単に説明を入れておきましょう。  
まとめると**上の欄に「作業内容」、下の欄に「作業内容の説明」を**入れましょう。  
と言う事で、今回は「Javaは良いぞ。」と追記したので、「Javaを推した」としました。また、複雑な操作ではないので説明は書いておりません。  
![6](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display6.png?raw=true "6")  
ただし、先ほど言ったように**ややこしい作業や新しくコードを挿入したとき**は、他の人がすぐに分かるように、説明を書いておきましょう。  
それでは、緑のボタンの「Commit changes」をクリックします。  
ボタンをクリックすると、変更履歴が記録され、ファイル内容表示画面となります。  
![7](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display7s.png?raw=true "7") 
では、変更履歴を見てみましょう。先ほど編集に使用した鉛筆のアイコンの隣にある、「**History**」を選択してみて下さい。  
すると、以下のような画面となります。これがコミット一覧(変更履歴の記録一覧)です。  
![8](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display8.png?raw=true "8") 
先ほど「**Commit changes**」で設定した「作業内容」が出ていますね。では、その作業内容の横にある、ランダムな文字列を選択してみましょう。  
![8s](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display8s.png?raw=true "8s") 
すると以下のような画面が出ます。  
![9](https://github.com/ElectronicsDesign/Welcome/blob/photo-up/display9.png?raw=true "9") 
