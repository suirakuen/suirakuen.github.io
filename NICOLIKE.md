# NICOLIKE
## 注意
このプログラムはニコニコ動画、株式会社ドワンゴとは一切関係ありません  
問題があれば消します
## コマンド
"/"キーを押すか、ギアマークのボタンを押すとコマンドウィンドウが開きます  
通常の文章を入手するとコメントをして表示されます。  
"/"から始まるコマンドを入力することで様々な操作や特殊なコメントを実行することができます。  
##　コマンド一覧
### /start
動画の再生を開始・再開します。
### /stop
動画を一時停止します。
### /restart
動画をはじめから再生します。
### /clear
現在表示されているコメントを全て削除します。
### /on
コメントを非表示にします。
### /off
コメントを表示します。
### /repeat (STRING)
(STRING)がonでリピート再生を有効化、offで無効化します。
### /color (STRING-1) (STRING-2~)
(STRING-1)で色を指定して(STRING-2~)のコメントを生成します。  
使用できる色は以下の通りです。
- white `#FFFFFF`
- red `#FF0000`
- pink `#FF8080`
- orange `#FFC000`
- yellow `#FFFF00`
- green `#00FF00`
- cyan `#00FFFF`
- blue `#0000FF`
- purple `#C000FF`
- black `#000000`
- scratch `#4C97FF`
- turbowarp `#FF4C4C`
- cat `#FFAB19`
- nobamen `#A2FFA2`
また、カラーコードでも指定が可能です。
### /custom (STRING-1) (STRING-2) (STRING-3~)
生成されるコメントの種類を増やせます。  
(STRING-1)がnormalで流れるコメント、stopで固定コメントを指定します。  
(STRING-2)がaddで(STRING-3)の内容を追加します。resetでデフォルトに戻します。
### /ue (STRING-1) (STRING-2~)
(STRING-2~)のコメントを上側固定コメントとして生成します。  
(STRING-1)で色を指定できます。(省略可)
### /naka (STRING-1) (STRING-2~)
(STRING-2~)のコメントを通常コメントとして生成します。  
(STRING-1)で色を指定できます。(省略可)
### /shita (STRING-1) (STRING-2~)
(STRING-2~)のコメントを下側固定コメントとして生成します。  
(STRING-1)で色を指定できます。(省略可)
### /special (STRING-1) (STRING-2~)
特殊な効果を持ったコメント(STRING-2~)を生成します。  
以下は効果の全てです。  
- normal 通常コメント。効果なし
- rainbow コメントがゲーミング仕様になります。
### /size (STRING-1) (STRING-2~)
サイズを指定してコメントを生成できます。  
以下は使用できるサイズです。
- small
- medium
- big
### /niconico [(STRING1~)] : [(STRING-2~)]
一度に複数の効果を指定してコメントを生成します。  
**コマンドとコメントの間は必ず":"(コロン)で区切る必要があります。**  
(STRING-1~)群に使用できるコマンドは以下の通りです。  
- ue
- naka
- shita
- small
- medium
- big
- normal
- special
- カラー関数 例: `red`
- カラーコード 例: `#FF0000`
### /command [(STRING1~)] : [(STRING-2~)]
"/niconico"と同じ効果を持ちます。
### / [(STRING1~)] : [(STRING-2~)]
"/niconico"と同じ効果を持ちます。
### /file (STRING)
ファイルの読み込み待機画面を呼び出します。  
(STRING)に入力できる内容は以下の通りです。
- video 動画ファイルを読み込みます。
### //
直前に入力されたコマンドを実行します。  
構文エラーなどで実行に失敗したコマンドも対象になります  
通常のコメントは対象外です。