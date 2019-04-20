## 「ターミナル」の日本語パスが文字化け対策
### [「ターミナル」の日本語パスが文字化けする](http://ytooyama.hatenadiary.jp/entry/2016/06/30/000237)
1. .profile edit
    ```
    $ vi ~/.profile
    ```
1. .profile write
    ```
    export LANG=ja_JP.UTF-8   
    export LESSCHARSET=utf-8
    ```
1. 設定反映
    ```
    $ source ~/.profile
    ```
