- 特定のディレクトリを一掃するコマンド
```
for /R %d in (.svn) do rmdir /S /Q "%d"
```

- yymmddを取得する
```
%DATE:~-8,2%%DATE:~-5,2%%DATE:~-2%
```