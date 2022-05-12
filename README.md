# xtared
pseudo tar ball editor for xyzzy text editor.

# 使い方
先にxdiredをrequireしてから次のようにすると、xdired上での訪問操作時にxtaredを使うことができます。

    (setq *xdired-find-tar-function* 'xtared::xtared)
    (setq *xdired-find-tar-other-window-function* 'xtared::xtared-other-window)

