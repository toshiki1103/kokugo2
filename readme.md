# ①課題名 
小学校３年生の読解力向上アプリ

## ②課題内容（どんな作品か） 
OPENAI のAPIコードを接続して、
小学生が楽しんで読解力を向上できるサービス

## ③アプリのデプロイURL デプロイしている場合はURLを記入（任意） 

## ④アプリのログイン用IDまたはPassword（ある場合） 
なし

## ⑤工夫した点・こだわった点  
そもそもAPIを繋ぐところから
出発

## ⑥難しかった点・次回トライしたいこと（又は機能）　フリー項目（感想、シェアしたいこと等なんでも）

【フォームなどに入力された値を取得する時】
授業で習っていた$("#id").val()はjQueryの書き方でありjQueryのライブラリを読み込ませないとだめ
標準javascriptはdocument.getElementByid("#id").valueで記述、若しくは
CSSセレクタのdocument.querySelector("#id").valueという書き方の方が柔軟性が高い（idだけじゃなくクラス、タグ、複合セレクタ選べる）

【Javascriptでデータを読み込む方法】
①Fetch API⇨モダンな標準API。Promiseベース。
②$.ajax⇨jQueryのメソッド。コールバック関数ベースで柔軟な設定ができる
③axis⇨人気のライブラリ。Promiseベースで、自動的にJSON変換、request/responseインターセプターなど便利機能が多い