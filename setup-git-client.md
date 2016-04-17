### git クライアントセットアップ
1. 前提条件
  ~~~~
  UbuntuにJavaが入っていない場合、起動できないのでJavaの導入がまだな人は同時にインストールするようにしてください。
  ~~~~
  - [JDKインストール](setup-JDK.md)
1. リポジトリを更新します。  
  ```
  $ sudo add-apt-repository ppa:eugenesan/ppa
  ```
1. パッケージ全体を update します。  
  ```
  $ sudo apt-get update -y
  ```

1. SmartGit をインストールします。  
  ```
  $ sudo apt-get install smartgit -y
  ```

### 引用
- [SmartGitのインストールと使い方](http://ry0.github.io/blog/2015/06/06/smart-git/)
