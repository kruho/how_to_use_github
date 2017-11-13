# how_to_use_github
GitHubの使い方

## リポジトリを作る
- トップページのYour profileをクリック
![](https://github.com/kruho/how_to_use_github/blob/master/Your_profile.png)

- RepositoriesのNewをクリック
![](https://github.com/kruho/how_to_use_github/blob/master/New.png)

- Repository nameに好きな名前をいれて、Initialize this repository with a READMEにチェックをいれて、Create repositoryをクリック
![](https://github.com/kruho/how_to_use_github/blob/master/create.png)

### リポジトリをクローンする
- クローンとは、GitHub上にあるリポジトリを自分のパソコンにダウンロードすること。
先ほど作ったtestリポジトリを開いてClone or downloadをクリックするとアドレスが表示される。
![](https://github.com/kruho/how_to_use_github/blob/master/clone.png)

- 端末で`git clone リポジトリアドレス（末尾がgit）`と打てばクローンできる。クローンが成功すると`test`というディレクトリが作成される。`cd`で`test`に入ると、デフォルトで作成されたREADMEがあるはず。

### add, commit, push
- testディレクトリに`hello.txt`という名前のファイルを作る。このファイルをtestリポジトリに加えてみる。
1. `git add hello.txt`
2. `git commit -m "add hello"`
3. `git push`

![](https://github.com/kruho/how_to_use_github/blob/master/add_commit_push_command.png)

- 1.でリポジトリに追加するファイルを登録する。
- 2.で前回のpushから現在までに新たに登録されたファイルにコメントをつける（ここでは`add hello`というコメントをつけた）。
- 3.で現在登録されているファイルをGitHubにアップロードする。

- ブラウザで確認すると、`hello.txt`というファイルが追加されているのが確認できる。また、コメントに`add hello`と書かれているのも確認できる。
![](https://github.com/kruho/how_to_use_github/blob/master/add_hello.png)
