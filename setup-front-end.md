## front end dev setup

### ruby setup

1. rbenv, ruby-build をインストールします。

```
$ sudo apt-get -y install rbenv ruby-build
```

1. rbenv の設定を.profile に書く

```
$ echo 'eval "$(rbenv init -)"' >> ~/.profile
```

1. 設定を反映させる

```
$ source ~/.profile
```

1. ruby をインストールします。

```
$ rbenv install 2.4.1
```

1. ruby のバージョンの切り替え

```
$ rbenv global 2.4.1
```

1. ruby のバージョンを確認

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

- [rbenv のよく使うコマンドまとめ - TASK NOTES](http://www.task-notes.com/entry/20141204/1417662000)

---

### Node.js

- ubuntu をアップデート、アップグレード(省略可)します。

  ```sh
  $ sudo apt-get -y update
  $ sudo apt-get -y upgrade
  ```

- node v20.x を取得します。

  ```sh
  $ curl -sL https://deb.nodesource.com/setup_20.x | sudo -E bash -
  ```

- node.js をインストールします。

  ```sh
  $ sudo apt-get install nodejs -y
  ```

- ubuntu の不要パッケージを削除(省略可)、クリーニング(省略可)します。

  ```sh
  $ sudo apt-get -y autoremove
  $ sudo apt-get -y autoclean
  ```

- インストール後の確認をします。

  ```sh
  $ npm -v
  10.5.0
  $ node -v
  v20.12.1
  $
  ```

### 引用

- [Ubuntu 20.04 に Node.js をインストールする方法](https://www.digitalocean.com/community/tutorials/how-to-install-node-js-on-ubuntu-20-04-ja)
