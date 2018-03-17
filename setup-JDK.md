### JDK setup
1. python を追加します。  
  ```
  $ sudo apt-get install python-software-properties
  ```
1. リポジトリを更新します。  
  ```
  $ sudo add-apt-repository ppa:webupd8team/java
  ```
1. パッケージ全体を update します。  
  ```
  $ sudo apt-get -y update
  ```
1. JDK6の場合  
  ```
  $ sudo apt-get -y install oracle-java6-installer
  ```
1. JDK7の場合  
  ```
  $ sudo apt-get -y install oracle-java7-installer
  ```
1. JDK8の場合  
  ```
  $ sudo apt-get -y install oracle-java8-installer
  ```
1. 上記が正常にできない場合
  ```
  $ sudo apt-get install openjdk-9 
  $ sudo apt-get install openjdk-9-jdk-headless
  $ sudo dpkg --configure -a
  $ sudo dpkg -i --force-overwrite '/var/cache/apt/archives/openjdk-9-jdk_9~b181-0ubuntu1_amd64.deb'
  $ java -version
  openjdk version "9-internal"
  OpenJDK Runtime Environment (build 9-internal+0-2016-04-14-195246.buildd.src)
  OpenJDK 64-Bit Server VM (build 9-internal+0-2016-04-14-195246.buildd.src, mixed mode)
  ```

### 引用
- [qiita UbuntuにOracle JDK8をインストール](http://qiita.com/niusounds/items/1f32dcd6fa1f57ade98a)
- [もうJava9にadd-apt-repositoryは要らない](https://qiita.com/yamatok/items/ed90768419f151df1e68)