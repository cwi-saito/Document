- 重複検索
```
select 重複見つけたいカラム from テーブル group by 重複見つけたいカラム having count(重複見つけたいカラム) <> 1
```

- Identityリセット
```
-- ID値を0に設定
DBCC CHECKIDENT ('tablename', RESEED, 0); 
-- ID値を100に設定
DBCC CHECKIDENT ('tablename', RESEED, 100);
```
