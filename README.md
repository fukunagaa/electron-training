# ELECTRON-TRAINING
## 使い方
macOS(darwin)、Windows向けアプリケーションを作成する手順を以下に記載する。
- GITからクローンする。

- ディレクトリ移動
```
$ cd electron-training
```

- 初期化設定
```
$ npm init
```

- electronのインストール
```
$ npm install electron
```

- electron-packagerのインストール
```
$ npm install electron-packager
```

- wineのインストール（省略可、ubuntuでは必要となった）
```
$ sudo apt update
$ sudo apt -y install wine64 winetricks
// 日本語が文字化けする場合、以下も実施
$ winetricks allfonts
```


- 起動が出来るか確認しておく
```
$ npm run start
```

- macOS(darwin)向けアプリケーションを作るときのコマンド
```
$ npm run build-macOS
```

- Windows向けアプリケーションを作るときのコマンド
```
$ npm run build-windows
```

