# system callの確認
```
$ strace -o <output> <executable>
```

# C言語のコンパイル
```
// static link
$ cc -static -o <output> <source>

// dynamic link
$ cc -o <output> <source>
```
※NOTE: ccコマンドはgccのエイリアス
