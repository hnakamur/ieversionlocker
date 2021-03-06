ieversionlocker
===============

インターネットエクスプローラのメジャーバージョンを固定するためのコマンドラインツールです。
このコマンドは「管理者：コマンドプロンプト」で実行してください。

## 使い方

1. インターネットエクスプローラで https://github.com/hnakamur/ieversionlocker/raw/master/dist/windows_32bit/ieversionlocker.exe をダウンロードし「ダウンロード」フォルダに保存します。
2. 以下の手順で「管理者：コマンドプロンプト」を開きます。
    * Windows VistaまたはWindows 7の場合：
        1. WINDOWSキーを押します。
        2. 「すべてのプログラム」メニューをクリックします。
        3. 「アクセサリ」フォルダをクリックします。
        4. 「コマンド プロンプト」メニューの上で右クリックしてポップアップメニューを開きます。
        5. 「管理者として実行」メニューをクリックします。
    * Windows 8または8.1の場合
        1. デスクトップウィンドウでWINDOWSキーを押しながらXキーを押します。
        2. Aキーを押して「コマンド プロンプト (管理者)」メニューを選択します。
3. 「管理者：コマンドプロンプト」が開いたら、以下のコマンドを実行してインターネットエクスプローラのバージョンをロックします。

```
cd %USERPROFILE%\Downloads
ieversionlocker.exe -l
```

インターネットエクスプローラのメジャーバージョンのロックを解除するには以下のコマンドを実行します。

```
cd %USERPROFILE%\Downloads
ieversionlocker.exe -u
```

## ライセンス

MIT
