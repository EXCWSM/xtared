# xtared
pseudo tar ball editor for [xyzzy text editor](https://ja.wikipedia.org/wiki/Xyzzy).

# 使い方
書庫を[xdired](https://github.com/EXCWSM/xdired)のように操作することができます。設定例のようにすると、xdired上で対応書庫を訪問した際にxtaredを表示します。

## 設定例

    (require "xtared")
    (setq *xdired-find-tar-function* 'xtared::xtared)
    (setq *xdired-find-tar-other-window-function* 'xtared::xtared-other-window)

## 既定の操作

| キー | 内容 |
| ---- | ---- |
| C    | 解凍 |
| d    | 削除フラグ |
| D    | カーソル行の項目を削除 |
| g    | 再読み込み |
| m    | マーク |
| o    | 他のウィンドウで訪問 |
| q    | バッファを閉じる |
| s    | ソート変更 |
| t    | マークの反転 |
| u    | マーク解除 |
| U    | すべてのマークを解除 |
| v    | 読み取り専用で訪問 |
| x    | 削除実行 |
| Z    | すべて解凍 |
| ESC = | マーク済項目の数と合計ファイルサイズ |
| * .  | 拡張子指定でマーク |
| * /  | ディレクトリをマーク |
| * *  | 実行ファイルをマーク |
| * c  | マークを変更 |
| % m  | 正規表現でマーク |
| C-h | マークを解除してカーソルを上へ |

