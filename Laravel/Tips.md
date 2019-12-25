# Tips
##### 実行されたSQLを確認する
```
.
.

use DB;

.
.

// 確認したいSQLの前にこれを仕込んで
DB::enableQueryLog();

// 確認したいSQL
$articles = Article::all();

// dumpする
dd(DB::getQueryLog());
```
