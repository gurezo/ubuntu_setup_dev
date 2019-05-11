### ruby setup
1. rbenv, ruby-buildをインストールします。  
  ```
  $ sudo apt-get -y install rbenv ruby-build
  ```
1. rbenvの設定を.profileに書く  
  ```
  $ echo 'eval "$(rbenv init -)"' >> ~/.profile
  ```
1. 設定を反映させる  
  ```
  $ source ~/.profile
  ```
1. rubyをインストールします。  
  ```
  $ rbenv install 2.4.1
  ```
1. rubyのバージョンの切り替え  
  ```
  $ rbenv global 2.4.1
  ```
1. rubyのバージョンを確認  
  ```
  $ ruby -v  
  ```
  
  ```
ruby 2.4.1p111 (2017-03-22 revision 58053) [x86_64-linux]
  ```
  - 上記のように表示されれば、正常に切り替え終了です。
1. bundler のインストールします。  
  ```
  $ rbenv exec gem install bundler
  ```


### rbenv tips
1. バージョン
  ```
  $ rbenv -v
  $ rbenv --version
  ```
1. インストール可能なバージョンの一覧
  ```
  $ rbenv install -l
  ```
1. インストール
  ```
  $ rbenv install 2.1.5
  ```
1. アンインストール
  ```
  $ rbenv uninstall 2.1.5
  ```

### 引用
- [rbenvのよく使うコマンドまとめ - TASK NOTES](http://www.task-notes.com/entry/20141204/1417662000)


----

### Node.js
1. nodebrew をインストールします。  
  ```
  $ curl -L git.io/nodebrew | perl - setup
  ```
1. 環境設定ファイルにnodebrew のパスを通す  
  ```
  $ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.profile
  ```
1. 設定を反映させる  
  ```
  $ source ~/.profile
  ```
1. nodebrewの確認  
  ```
  $ nodebrew --version
  ```
1. nodebrewのインストールlist確認  
  ```
  $ nodebrew ls-remote
  ```
1. nodebrew から Node.jsをインストールします。  
  ```
  $ nodebrew install-binary v10.15.3
  ```
1. Node.jsの使用するバージョンを指定する  
  ```
  $ nodebrew use v10.15.3
  ```

### 引用
- [nodebrewでよく使うコマンド](https://qiita.com/suisuina/items/c5c4e4b9f55a8615a542)
