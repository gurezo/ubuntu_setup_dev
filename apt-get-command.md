### apt-get コマンド 一覧
- 最新のアップデートを確認します。  
  ```
  $ sudo apt-get -y update
  ```
- 確認した最新のアップデートを適用します。  
  ```
  $ sudo apt-get -y upgrade
  ```
- dist-upgradeでディストリビューションを最新のものに適用します。  
  ```
  $ sudo apt-get -y dist-upgrade
  ```
- 依存関係解決後に使わなくなったパッケージを削除します。   
  ```
  $ sudo apt-get -y autoremove
  ```
- 作業時のaptキャッシュを削除します。  
  ```
  $ sudo apt-get -y autoclean
  ```
  - キャッシュ(/var/cache/apt/archives)が肥大化することを防ぎます。
- apt-get コマンド確認  
  ```
  $ man apt-get
  ```

### 引用
- [Ubuntuをアップデートする(コマンド編)【LinuxOSの取り扱い説明】](http://do-you-linux.com/blog/2013/11/19/post-838/)
