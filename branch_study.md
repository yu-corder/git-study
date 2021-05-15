# branch
git branch

git checkout

git branch -d 

## git fetch git merge とは

ローカルリポジトリの中にはmasterブランチとorigin/masterブランチ（追跡ブランチ）の２つの情報が置かれている。
git fetch を行った時にリモートリポジトリに新しい更新があるとorigin/masterが最新になる。しかし、masterには更新が行われていない状態なのでmergeする必要がある。

git fetch

git merge

## git pull

git pull は git fetch と git mergeの二つを合わせたもの