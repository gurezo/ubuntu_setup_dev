### ruby setup
1. rbenv, ruby-buildをインストールします。  
  ```
  $ sudo apt-get -y install rbenv ruby-build
  ```
1. rbenvの設定を.profileに書く  
  ```
  $ echo 'eval "$(rbenv init -)"' >> ~/.profile
  ```
  ```
  $ source ~/.profile
  ```
1. rubyをインストールします。  
  ```
  $ rbenv install 1.9.3-p448
  ```
1. rubyのバージョンの切り替え  
  ```
  $ rbenv global 1.9.3-p448
  ```
1. rubyのバージョンを確認  
  ```
  $ ruby -v  
  ```
  
  ```
  ruby 1.9.3p448 (2013-06-27 revision 41675) [x86_64-darwin14.5.0]  
  ```
  - 上記のように表示されれば、正常に切り替え終了です。
1. bundler のインストールします。  
  ```
  $ rbenv exec gem install bundler
  ```

----

### sass setup
1. sass をインストールします。  
  ```
  $ gem install sass -v 3.4.10
  ```



----

### compass setup
1. compass をインストールします。  
  ```
  $ gem install compass -v 1.0.3
  ```

----

### Node.js
1. nodebrew をインストールします。  
  ```
  $ curl -L git.io/nodebrew | perl - setup
  ```
1. 環境設定ファイルにnodebrew のパスを通す  
  ```
  $ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.profile
  $ source ~/.profile
  ```
1. nodebrewの確認  
  ```
  $ nodebrew --version
  ```
1. nodebrew から Node.jsをインストールします。  
  ```
  $ nodebrew install-binary 0.10.21
  ```
1. Node.jsの使用するバージョンを指定する  
  ```
  $ nodebrew use 0.10.21
  ```

----

### Grunt の準備
1. npmを最新の状態にします。  
  ```
  $ npm update
  ```
2.	Grunt-cliをインストールします。   
  ```
  $ npm install -g grunt-cli
  ```  
