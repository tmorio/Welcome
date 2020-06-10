# Welcome to GitHub!

## GitHub is 何
バージョン管理システムのGitを使用したコードホスティングシステム。  
簡単に言えば、Gitのファイル管理機能をサーバー上でもやってくれるサービスみたいなものです。  
間違えないで欲しいのですが、**あくまでもGitHubはレポジトリと言う名のフォルダを管理する場所であり、開発する場所ではありません。**

## Git is 何
ソースコードなどの変更履歴を追跡する分散型バージョン管理システム。  
[Git - Wikipedia](https://ja.wikipedia.org/wiki/Git)
  
  
簡単に言えば、ソースコードの変更履歴を記録できるシステムです。  
例えばAさんがここを追加した、Bさんがこの部分を削除したと言うのを可視化してくれるものです。  
これにより、完成したソースコードをいちいちコピーする必要がなくなります。

## 学内でGit/GitHubを使う方法
学内LANだとGitHubにデータを送信するポートが塞がれている、そもそもGitが入っていないなどの問題があります。  
本来ならばコマンドを入力して、操作を行いたいところですが、ベースをこちらで用意しておくので今回はGitHubのWeb上から操作していきます。  
  
※ Git Portable版をインストールする、学内LANの規制を回避するなどの手段はありますが、今回は割愛します。  

## "Web上で"編集してマージするまでの流れ
基本的には以下の流れで行います。(個人的にはコマンドでやったほうが色々楽だけど規制回避ゴニョゴニョ...)  
<br />
[1. レポジトリをCloneまたはForkする。](https://github.com/ElectronicsDesign/Welcome/blob/master/manual/1.md)  
[2. 作業用Branchを作成する。](https://github.com/ElectronicsDesign/Welcome/blob/master/manual/2.md)    
[3. 編集して、Commitする。](https://github.com/ElectronicsDesign/Welcome/blob/master/manual/3.md)  
[4. Pull request(合体要求)を投げる。](https://github.com/ElectronicsDesign/Welcome/blob/master/manual/4.md)  
[5. マージ(合体)する。](https://github.com/ElectronicsDesign/Welcome/blob/master/manual/5.md)  
<br />
という事で今回は、一通りこれらの作業をやってみましょう。  
<br />
各手順をクリックすると説明に入ります。
<br />
## この文書の著作権について
内容について、一応確認はしておりますが、確実な保証はできないため、著作権は放棄します。  
何方でも自由にご利用下さい。  
また、不適切な点がございましたら、IssueやPull requestを投げてくれると助かります。  
<br />
Written by Morikapu.
