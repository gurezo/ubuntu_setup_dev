### adb setup
- android-tools-adbをインストールする  
  ‘‘‘
  $ sudo apt-get install -y android-tools-adb
  ‘‘‘

### adb_usb.ini 編集する
```
$ vi ~/.android/adb_usb.ini
```
- 下記の内容を追記する
  ~~~~
  # 例：Fx0, Open Web Board  
  # 他のデバイスも同様に記述する事
  # 1 USB VENDOR ID PER LINE.
  0x2207
  # 2 USB VENDOR ID PER LINE.
  0x1004
  ~~~~

### ルールを設定する
  ```
  $ sudo vi /etc/udev/rules.d/51-android.rules
  ```

- 下記の内容を追記する
~~~~
# 例：Fx0, Open Web Board  
# 他のデバイスも同様に記述する事
SUBSYSTEM=="usb", ATTR{idVendor}=="2207", MODE="0666", GROUP="plugdev"
SUBSYSTEM=="usb", ATTR{idVendor}=="1004", MODE="0666", GROUP="plugdev"
~~~~

### 設定を反映をする。
```
$ sudo udevadm control --reload
```

### 引用
- [ADBをインストールして使用する](http://is.gd/niM4h1)
- [参考メモ](https://public.etherpad-mozilla.org/p/chirimen-touch-20160109)
