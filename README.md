作業 / 休憩 BGM タイマー
備忘録

━━━━━━━━━━━━━━━━
■ 概要
━━━━━━━━━━━━━━━━

作業用のポモドーロタイマー。

2種類のバージョンを用意。

PC版
YouTube動画をBGMとして再生

iPhone版
ローカルの mp3 / mp4 を再生

━━━━━━━━━━━━━━━━
■ ファイル構成
━━━━━━━━━━━━━━━━

index.html
トップページ（メニュー）

youtube.html
PC用タイマー（YouTube版）

local.html
iPhone用タイマー（ローカル再生）

icon.png
ホーム画面アイコン

━━━━━━━━━━━━━━━━
■ URL
━━━━━━━━━━━━━━━━

トップページ
https://username.github.io/repo/

PC版（YouTube）
https://username.github.io/repo/youtube.html

iPhone版（ローカル）
https://username.github.io/repo/local.html

━━━━━━━━━━━━━━━━
■ iPhoneで使う方法
━━━━━━━━━━━━━━━━

1 Safariで local.html を開く

2 共有ボタン

3 「ホーム画面に追加」

ホーム画面からアプリのように起動できる。

━━━━━━━━━━━━━━━━
■ GitHub Pages 設定
━━━━━━━━━━━━━━━━

Settings
↓
Pages

Source
Deploy from branch

Branch
main

━━━━━━━━━━━━━━━━
■ 動作仕様
━━━━━━━━━━━━━━━━

作業 → 休憩
休憩BGMは毎回ループ開始位置から再生

休憩 → 作業
作業BGMは前回の再生位置から再開

━━━━━━━━━━━━━━━━
■ メモ
━━━━━━━━━━━━━━━━

iPhoneはYouTubeの自動再生制限があるため
ローカル版を使用。

PCではYouTube版が安定。

━━━━━━━━━━━━━━━━
■ 将来の改善案
━━━━━━━━━━━━━━━━

・作業終了音
・作業ログ
・プレイリスト対応
