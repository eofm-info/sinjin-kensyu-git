# 新人研修: VCS(Git)

--

## 目次

- VCS とは
    - 何のためにあるのか
    - どんなものがあるのか
    - なんで Git なのか
- Git 入門
    - ひととおりの使い方


---


## VCS とは

--

Version Control System

バージョン管理システム


---

### 何のためにあるのか

- 以前の状態に戻れる
- 変更履歴を調べる
- ディレクトリ構造全体を1つの単位として記録する
- 「なぜ」と「誰が」を記録する
----
濱野純『入門Git』(秀和システム, 2009)

--

本当に？　手動でもよくない？

--

1. 以前の状態に戻れる
1. 変更履歴を調べる
1. ディレクトリ構造全体を1つの単位として記録する
1. 「なぜ」と「誰が」を記録する
----
1. ファイルをコピーしておけば…？
1. 新旧のファイルを横に並べて比較すれば…？
1. zip に固めておけば…？
1. テキストをコメントアウトして、理由と署名を書けば…？

--

やってみよう(ToT)


---

### VCS どんなものがあるのか

--

Google で検索してみよう!!


---

### なんで Git なのか

--

なぜだろう？

--

社内では…

- SVN(Subversion)
- Git

--

- SVN: 集中型
- Git: 分散型
----
何が？　→　リポジトリが

--

[ガチで5分で分かる分散型バージョン管理システムGit (3/6) - ＠IT](http://www.atmarkit.co.jp/ait/articles/1307/05/news028_3.html)


---

## Git 入門

- ひととおりの使い方
    - 個人での利用
    - (できたら)リモートリポジトリからの clone, push

--

チートシートの配布

--

やってみよう

----
[Git をはじめからていねいに](https://github.com/Shinpeim/introduction-to-git)

--

確認

----
    git config --global user.name
    git config --global user.email

---

## 参考リンク

[今さら聞けない Git](http://study.bp.dev.istyle.local/slides/git_study/index.html#/)

[社内GitBucket](http://dpm.istyle.local:8888/)

[高野さんの Github ページ](https://github.com/fortkle)

[VCS入門](https://github.com/masaru-b-cl/introduction-to-vcs)

[Git をはじめからていねいに](https://github.com/Shinpeim/introduction-to-git)

[Learn Git Branching](http://k.swd.cc/learnGitBranching-ja/)

[もっと早く知りたかった！ Gitが鬼のようにわかるスライド厳選7選](http://www.find-job.net/startup/7-git-slides)
