# Tips
##### mysqlでROWNUM を取得するクエリ
```
ローカル変数 @i を使って問い合わせ結果に1番から始まる連番を振る。変数の初期化は FROM 句の中で定義する。
SELECT
  @i:=@i+1 AS ROWNUM
, <col>
FROM
  (SELECT @i:=0) AS INDEX_NUM
, <table>;
```
