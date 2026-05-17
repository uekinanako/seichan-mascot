# セイちゃんマスコット配布サイト

GitHub Pagesで公開するための静的サイトです。

## ローカル確認

`index.html` をブラウザで開くと確認できます。

## GitHubで公開する手順

1. GitHubで `uekinanako/seichan-mascot` という公開リポジトリを作成します。
2. このフォルダ内のファイルをすべてアップロードします。
3. GitHubのリポジトリ画面で `Releases` を開きます。
4. `Create a new release` を押します。
5. Tagに `v1.0.2`、Release titleに `セイちゃんマスコット 1.0.2` と入力します。
6. `seichan-mascot-setup-1.0.2.exe` をRelease assetsにアップロードします。
7. Releaseを公開します。
8. `index.html` のダウンロードリンクを、GitHub ReleasesのURLに差し替えます。
   例: `https://github.com/uekinanako/seichan-mascot/releases/latest/download/seichan-mascot-setup-1.0.2.exe`
9. リポジトリの `Settings` → `Pages` を開きます。
10. `Build and deployment` の `Source` で `Deploy from a branch` を選びます。
11. Branchを `main`、Folderを `/root` にして保存します。

公開URLは通常、以下になります。

```txt
https://uekinanako.github.io/seichan-mascot/
```

## 説明文案

セイちゃんマスコットは、Windowsのデスクトップにちょこんと登場する無料マスコットアプリです。
作業中の画面のすみに置いて、いつものPC時間を少し楽しくできます。

## 注意書き案

このアプリは個人制作のため、インストール時にWindowsの警告が表示される場合があります。
配布元を確認したうえでインストールしてください。
