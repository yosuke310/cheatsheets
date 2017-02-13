# セッション
コマンド|説明
---|---
tmux|新規セッション開始
tmux new -s <セッション名>|名前をつけて新規セッション開始
tmux ls|セッションの一覧表示
tmux lsc|接続クライアントの一覧表示
tmux a|セッションを再開 ※-t <対象セッション名>でセッション名の指定も可能
tmux kill-session|セッションを終了 ※-t <対象セッション名>でセッション名の指定も可能
tmux kill-server|tmux全体を終了
tmux [command [flags]]|その他コマンドを実行

# キー操作
prefix-key入力後の操作

コマンド|説明
---|---
?|キーバインド一覧
:|コマンドプロンプト<br/>show-options -g や show-window-options -g 入力で設定一覧を表示<br/>-gはグローバル指定(デフォルト)の意、個別に設定された値は-g無しで確認する
