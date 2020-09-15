Three.jsの練習場です。

- [初めてのThree.js 1章 サンプル](chapter_1.html)
- [回転する立方体](cube.html)
- [線](line.html)

# watch.rb について

次のように実行すると、`index.htmml`ファイルを変更したときに、Google chromeで`localhost`を開いているタブをリロードしてくれる。
htmlファイルに含まれるJavaScript内のパラメーターを変更した際に、即座に画面に反映されて便利！

```sh
ruby watch.rb . index
```

ただし、`localhost`である必要があるので、`python -m SimpleHTTPServer`などをつかってHTTPサーバーを起動し、Google chromeそこからHTMLファイルを取得して表示している必要があります。
