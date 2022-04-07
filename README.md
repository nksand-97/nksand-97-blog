# nksand-97.github.io

ブログのurl: (https://nksand-97.github.io/)

## 記事の書き方

### 1. 作業ディレクトリに移動，記事を作成する．
```
$ hugo new post/<記事ファイル名>.md
```
### 2. 公開用リソースを作成する．
```
$ hugo -D
```
### 3. ブログのリポジトリに移動，publicディレクトリの中身をコピー．
```
$ cd ../nksand-97.github.io
$ cp -pr ../hugo/public/* .
```
### 4. pushする.
```
$ git add .
$ git commit -m "<コメント>"
$ git push
```

## サイトの編集