１　コマンドプロンプトにてrm　なる関数が使えない
	→直接削除でindexフャイルをバックアップに移す
２　app/views/layouts/application.htmlファイル内
	<title></title>直下にコメントを書くことができない。
	#ダメ→#が反映されてしまう。
	=begin =endだめそのまま表示されてしまう。
	元のソースコードの避難場所として以下に記述しておく
  <%= stylesheet_link_tag    "application", :media => "all" %>
  <%= javascript_include_tag "application" %>
３　app/models/.post
　　attr_accessible :content, :name, :titleこの一行いるのか？？
　　→rails3.2以降は必要らしい。。。
４　ブログ内でも日本語で入力するとエラーが表示される　トホホ
　　バック（windouwsの）を行うと一応日本語の一行は得られているが
　　同様に編集などを行うとエラーとなる。


