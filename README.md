TKGMap
====

徳島の交通状況 Google Maps API 版
====

Google が提供している交通状況データーに、徳島県が公開している道路の通行規制情報を Google Maps 上でマッシュアップしたものです。

オープンデータが流行していますが、オープンデータの作り方やその公開されたデータを実際に使う方法を解説したものはあまり存在しません。
オープンデータを使う際の参考になれば幸いです。

公開サイト http://tk.ecitizen.jp/

TKGMapは、コンソールアプリケーションです。ソースを利用する場合は、Visual Studio 2013 Express for Windows Desktop を利用してください。サーバー用のソフトウェアについては Webフォルダーにまとめてあります。

基本的には7年前に作ったソフトなので、XMLをDOMで処理をしています。最近であれば、XML の処理もLINQ To XML を使えばもう少し楽に処理ができるし、サーバ用のデータもJsonにしていると思います。
