### ショートカットの作り方

#### desktop ファイルの作成(Android Studio の場合)
- AndroidStudio.desktop
    ```
    [Desktop Entry]
    Encoding=UTF-8
    Version=1.0
    Type=Application
    Name=Android Studio
    Icon=/home/gurezo/android-studio/bin/studio.png
    Path=/home/gurezo/android-studio/bin
    Exec=/home/gurezo/android-studio/bin/studio.sh
    ```
- desktop file copy
    ```
    $ cp ~/android-studio/AndroidStudio.desktop ~/.local/share/applications/
    $ cp ~/DeveloperEdition/DeveloperEdition.desktop ~/.local/share/applications/
    $ cp ~/Nightly/Nightly.desktop ~/.local/share/applications/
    ```

#### desktop ファイルの作成(Firefox Nightly の場合)
- Nightly.desktop
    ```
    [Desktop Entry]
    Encoding=UTF-8
    Version=1.0
    Terminal=false
    Type=Application
    Name=Firefox Nightly
    Icon=/home/gurezo/Nightly/browser/chrome/icons/default/default128.png
    Path=/home/gurezo/Nightly/
    Exec=/home/gurezo/Nightly/firefox
    ```

#### desktop ファイルの作成(Firefox Developer Edtion の場合)
- DeveloperEdition.desktop
    ```
    [Desktop Entry]
    Encoding=UTF-8
    Version=1.0
    Terminal=false
    Type=Application
    Name=Firefox Developer Edtion
    Icon=/home/gurezo/DeveloperEdition/browser/chrome/icons/default/default128.png
    Path=/home/gurezo/DeveloperEdition/
    Exec=/home/gurezo/DeveloperEdition/firefox
    ```


### 引用
- [Ubuntuでショートカット（デスクトップエントリ）を作る](http://91stardust-atelier.hatenablog.com/entry/2016/11/17/015854)

---- 

#### ファイルの設定を変更

ファイル > 設定 > 動作 > 実行可能なテキストファイル の 「クリックしたら実行する」を設定

#### 作成した desktop ファイルの設定を変更

desktop ファイルを右クリック > プロパティ > アクセス権 > 実行:の「プログラムとして実行可能」を設定

#### ランチャーに追加

desktop ファイルをランチャーへドラック＆ドロップ

### 引用

- [うめの記録帳: Android Studio を Ubuntu のランチャーから起動できるように設定する](http://blog.ysakaguchi.net/2014/07/android-studio.html)
