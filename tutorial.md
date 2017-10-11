# Git入門



# 初期設定

- 最初にやっておくべき設定

```bash
$ git config --global user.name ["your name"]
$ git config --global user.email [your mailaddress]
```



# `$ git init`

- リポジトリの初期化

`$ git init`



# `$ git clone`

- 既存のリポジトリのクローン

`$ git clone [url]`



# `$ git status`

- ファイルの状態を確認

`$ git status`



# `$ git diff`

- ファイルの差分を確認

`$ git diff`



# `$ git log`

- リポジトリの更新履歴を表示

`$ git log`

- リポジトリの更新履歴を見やすく表示

`$ git log --oneline --graph --decorate`



# `$ git branch`

- 現在のブランチを確認

`$ git branch`

- 新たなブランチを作成

`$ git branch [ブランチ名]`

- ブランチの削除

`$ git branch -d [ブランチ名]`



# `$ git checkout`

- ブランチの切り替え

`$ git checkout [ブランチ名]`

- 新たなブランチを作成し，ブランチを切り替え

`$ git checkout -b [ブランチ名]`



# `$ git add`

- 指定したファイルをインデックスへ追加

`$ git add [path to file]`

- カレントディレクトリ以下のファイルをインデックスへ追加

`$ git add .`



# `$ git commit`

- インデックスへ追加されたファイルをコミット

`$ git commit -m ['コミットメッセージ']`



# `$ git push`

- ローカルの履歴をリモートへ反映

`$ git push [リモート名] [ブランチ名]`



# `$ git fetch`

- ローカルリポジトリの内容をリモートリポジトリの内容に更新

`$ git fetch [リモート名]`



# `$ git merge`

- ブランチをマージする

`$ git merge [ブランチ名]`



# `$ git pull`

- fetchとmergeを一度に行う

`$ git pull [リモート名] [ブランチ名]`

は以下の作業を一度に行う

```
$ git fetch [リモート名]
$ git merge [リモート名]/[ブランチ名]
```



# その他コマンド

- `$ git stash`
- `$ git rm`
- `$ git reset`
- etc...



# Git入門資料ブックマーク

- [サルでもわかるGit入門](https://www.backlog.jp/git-guide/)
- [Learn Git Branching](http://k.swd.cc/learnGitBranching-ja/)



# GUIクライアント

- [Sourcetree](https://ja.atlassian.com/software/sourcetree)
- [GitKraken](https://www.gitkraken.com)
- etc...



# Gitホスティングサービス

- [GitHub](https://github.com)
- [Bitbucket](https://bitbucket.org)
- [GitLab](https://about.gitlab.com)
- etc...