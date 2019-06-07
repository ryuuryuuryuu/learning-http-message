# HTTPでやりとりする仕組み

<!-- Markdown記法のヒント

コード記法（1行の中に埋めたい場合）

`code`

コードブロック記法（複数行）

```
print('a')
print('b')
```

-->

## 実習でやったこと (Y)

*   デベロッパーツールの利用
*   マークダウンの記入練習をした。

## 自分で調べたこと

*   先生の見ていた「URLとは何か」のサイトを検索して読んだ。
[URLとはなにか](https://developer.mozilla.org/ja/docs/Learn/Common_questions/What_is_a_URL)
*   マークダウンのコマンドについて調べた。
[Markdown記法 サンプル集](https://qiita.com/tbpgr/items/989c6badefff69377da7)
*   TLSとSSLについて
*   Mac ページ更新　コマンド
*   HTTPメッセージについて
[研鑽の日々]（https://ken3ypa.hatenablog.com/entry/2019/01/10/205908）
[HTTP入門](http://www.tohoho-web.com/ex/http.htm)

## HTTPメッセージ (kd.txt) のうち、最も重要だと思う部分を貼り付けてください

```
GET / HTTP/1.0
HTTP/1.0 200 OK
Server: Apache
Date: Fri, 07 Jun 2019 02:16:10 GMT
Content-Type: text/html; charset=UTF-8
```

## それはなぜですか？
```
リクエスト行。メソッド、パス名、バージョンについて。
ステータス行。バージョン、ステータスコード（200はリクエストが受理されてることを確認できる。）、ステータスコードについてのテキスト。
レスポンスを返した時間。のちに確認することがあると思うから。
プログラミング言語。キャラセットの指定。
```
## わかったこと・気づいたこと
'わからないことはすぐにググった方がいいことに気づきました。'
'マークダウンの描きやすさに感動しました。'
'URLからもいろんなことを読み取れるんだなと思いました。'
