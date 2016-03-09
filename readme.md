githubに静的サイトを作る方法
=================

ネットの賢人たちを参考にしたメモ。新しいものは何もない。

手順
----

1. githubにリポジトリを作成。
2. パソコンにclone。この際、親フォルダで、コマンドを実行すると、リポジトリと同じ名前のフォルダができる。
3. 出来たフォルダに入り、git status。現状確認だけ。
4. このreadme.mdを作成。
5. add、commit。
6. push
7. 同期？を確認。
8. ローカルにgh-pagesのbranchを作る。
9. checkout
10. git push --set-upstream origin gh-pages
11. index.html作る。
12. 全部、addして、commit。
13. push
14. サイトできてる。