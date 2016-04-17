### git クライアントセットアップ
#### 前提条件
~~~~
UbuntuにJavaが入っていない場合、起動できないのでJavaの導入がまだな人は同時にインストールするようにしてください。
~~~~
- [JDKインストール](setup-JDK.md)

#### SmartGitのインストール
1. リポジトリを更新します。  
  ```
  $ sudo add-apt-repository ppa:eugenesan/ppa
  ```
1. パッケージ全体を update します。  
  ```
  $ sudo apt-get -y update
  ```

1. SmartGit をインストールします。  
  ```
  $ sudo apt-get -y install smartgit
  ```

### 引用
- [SmartGitのインストールと使い方](http://ry0.github.io/blog/2015/06/06/smart-git/)
