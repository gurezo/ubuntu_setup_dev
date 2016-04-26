### ubuntu OS Check Memo
- アーキテクチャ（OSが32bit, 64bitどちらなのか）を調べるコマンド
  - arch  
  ```
  $ arch
  ```
  ~~~~
  # 以下のように表示されます
  # 64bitの場合
  X86_64
  # 32bitの場合
  i686
  ~~~~
  - uname  
  ```
  $ uname -a 
  ```
  ~~~~
  # 以下のように表示されます
  Linux コンピューター名 4.2.0-35-generic #40-Ubuntu SMP Tue Mar 15 22:15:45 UTC 2016 x86_64 x86_64 x86_64 GNU/Linux
  ~~~~
- バージョン確認方法  
  ```
  $ cat /etc/lsb-release
  ```
- バージョンアップコマンド（長期安定版）  
  ```
  $ sudo do-release-upgrade
  ```
- バージョンアップコマンド（最新版）  
  ```
  $ sudo do-release-upgrade -d
  ```

### 引用
- [Ubuntuのバージョン確認とアーキテクチャ確認コマンド](http://mawatari.jp/archives/check-ubuntu-version)
