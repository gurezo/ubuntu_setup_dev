### android studio setup
- サイトからのダウロード  
  [Android Studio と SDK Tools のダウンロード | Android Developers](http://developer.android.com/intl/ja/sdk/index.html)
- [android-studio-ide-143.2739321-linux.zip](https://dl.google.com/dl/android/studio/ide-zips/2.0.0.20/android-studio-ide-143.2739321-linux.zip) 2016.04.25 22:11時点
- 任意の場所に解凍する。  
  例：~/android-studio
- 任意の場所へ移動する。  
 ```
  $ cd android-studio/bin$
  ```
- android-studioを起動する。  
  ```
  $ ~/android-studio/bin$ ./studio.sh
  ```

### 起動してもSDKが正常にインストール出来ない時
- 依存性の問題の可能性があるので、下記手順を行う。
  ```
  $ sudo apt-get install -y lib32stdc++6
  ```

### 引用
- [Ubuntu にAndroid Studio をインストールする](http://qiita.com/TsutomuNakamura/items/ef4aeec32cdaaf9105cc)
