### ショートカットの作り方

#### desktop ファイルの作成(Android Studio の場合)

```
[Desktop Entry]
Encoding=UTF-8
Version=1.0
Type=Application
Name=Android Studio
Icon=(Android Studioの絶対パス)/bin/androidstudio.ico
Path=(Android Studioの絶対パス)/bin
Exec=(Android Studioの絶対パス)/bin/studio.sh
```

#### ファイルの設定を変更

ファイル > 設定 > 動作 > 実行可能なテキストファイル の 「クリックしたら実行する」を設定

#### 作成した desktop ファイルの設定を変更

desktop ファイルを右クリック > プロパティ > アクセス権 > 実行:の「プログラムとして実行可能」を設定

#### ランチャーに追加

desktop ファイルをランチャーへドラック＆ドロップ

### 引用

* [うめの記録帳: Android Studio を Ubuntu のランチャーから起動できるように設定する](http://blog.ysakaguchi.net/2014/07/android-studio.html)