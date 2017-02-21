- 重複検索
```
select 重複見つけたいカラム from テーブル group by 重複見つけたいカラム having count(重複見つけたいカラム) <> 1
```
