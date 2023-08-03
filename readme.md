# Gitの学習  

## Gitの基本的な用語  

**リポジトリ**→シンプルに保存先のこと  
 - リモートリポジトリ：サーバ上のリポジトリ  
 - ローカルリポジトリ：自分のPC上にあるリポジトリ  

**コミット**  
 - ローカルリポジトリへのアップロードを行うこと  

**プッシュ（push）**  
 - ローカルリポジトリの内容をリモートリポジトリに反映させる
  （わかりやすく言うと、アップロード）

**クローン（clone）**  
 - リモートリポジトリの内容をコピーして、ローカルリポジトリを作成する  

**プル（pull）**  
 - リモートリポジトリからローカルリポジトリの内容を更新する  

**ブランチ**  
 - 1つのリソースに対いて、複数人で作業できるようにできる仕組み  
   分岐させたブランチは、合流させることができる。  
  vscodeのブランチ操作  
  →https://qiita.com/glitter_holic/items/b76fda092ec2f56afae8  

**フェッチ（fetch）**  
 - pullの更新しないバージョン（リモートリポジトリのコミット履歴を取得する）  
  fetch→リモートリポジトリとローカルリポジトリに差分発見→pull  
  のような使い方をするのかな。。。  
  https://prograshi.com/general/git/how-to-use-git-fetch/  

**チェックアウト（checkout）**  
 - ブランチを切り替えたいときに行う  
