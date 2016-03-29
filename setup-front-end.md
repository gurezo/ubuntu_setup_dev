### ruby setup
1. rbenv, ruby-buildをインストールします。  
```sh
$ brew install rbenv ruby-build
```
1. rbenvの設定を.profileに書く  
```sh
$ echo 'eval "$(rbenv init -)"' >> ~/.profile
$ source ~/.profile
```
1. rubyをインストールします。  
```sh
$ rbenv install 1.9.3-p448
```
1. rubyのバージョンの切り替え  
```sh
$ rbenv global 1.9.3-p448
```
1. rubyのバージョンを確認  
- 下記のように表示されれば、正常に切り替え終了です。
```sh
$ ruby -v
ruby 1.9.3p448 (2013-06-27 revision 41675) [x86_64-darwin14.5.0]
```
1. bundler のインストールします。  
```sh
$ rbenv exec gem install bundler
```

----

### sass setup
1. sass をインストールします。  
```sh
$ gem install sass -v 3.4.10
```
----

### compass setup
1. compass をインストールします。  
```sh
$ gem install compass -v 1.0.3
```

----

### Node.js
1. nodebrew をインストールします。  
```sh
$ curl -L git.io/nodebrew | perl - setup
```
1. 環境設定ファイルにnodebrew のパスを通す  
```sh
$ echo "export PATH=$HOME/.nodebrew/current/bin:$PATH" >> ~/.profile
$ source ~/.profile
```
1. nodebrewの確認  
```sh
$ nodebrew --version
```
1. nodebrew から Node.jsをインストールします。  
```sh
$ nodebrew install-binary 0.10.21
```
1. Node.jsの使用するバージョンを指定する  
```sh
$ nodebrew use 0.10.21
```

----

### Grunt の準備
1. npmを最新の状態にします。  
```sh
$ npm update
```
2.	Grunt-cliをインストールします。   
```sh
$ npm install -g grunt-cli
```  
