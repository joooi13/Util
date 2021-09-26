# Util

### Hugo
https://gohugo.io/getting-started/quick-start/

### テーマ
https://themes.gohugo.io/themes/hallo-hugo/


```
//dev配下でローカルで起動
$ hugo server -D
※http://localhost:1313/ で接続可能になる

//cloneし直したときはsubmoduleをupdateする
$ git submodule update --init --recursive

// deployするときはdev配下でbuild
$ hugo
//portfolio配下で
$ firebase deploy
```