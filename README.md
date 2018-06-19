# ResasDef4CDataJSONDrivers
地域経済分析システム（RESAS：リーサス）用CData JSON Drivers定義

## はじめに

[CData Drivers製品](https://www.cdata.com/jp/drivers)は、約90を超える（2017/11時点）クラウドサービスやNoSQLなどのビッグデータテクノロジー、ファイルシステムへ標準インターフェース (ODBC / JDBC / ADO.NET / Excel / BizTalk / SSIS / FireDAC / OData)で接続可能なデータ接続テクノロジーです。本リポジトリは、[CData JDBC Drivers製品](https://www.cdata.com/jp/drivers/json/)を用いて、経済産業省と内閣官房が提供するオープンデータである[地域経済分析システム（RESAS：リーサス）](https://resas.go.jp/)へ接続する方法を提供します。これにより、既に使い慣れているツール群（Office系、BI、データマイニング、ETL）からRESASのデータにアドホックに接続してデータを取得することが出来るようになります。

## JDBC URLサンプル

jdbc:json:Location=/Applications/CData/CData JDBC Driver for JSON 2018J/resas/;CustomHeaders=X-API-KEY:*******;
