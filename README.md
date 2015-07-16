# simple-webapi-console
Simple web console to use ajax HTTP request

WebAPIの開発時、ブラウザでGET/POSTリクエストを簡単に試すことができます。

1. APIを選択

2. URL, POSTデータを編集

3. 実行

URL/inputパラメータ/HTTP methodのサンプルは、APIリストに追記していくことで簡単に呼び出すことができます。
<pre>/json/apilist.json</pre>

inputデータの扱いについて
* **GET**かつdataType:**text**のとき、URLパラメータとして扱います。
* **POST**かつdataType:**text**のとき、POST formdataとして扱います。textareaにはjsonで記述してください。
* dataType:**json**のとき、jsonをリクエストに含めます。

[サンプルページ](http://kentayamamoto.github.io/pages/apitest/index.html)
