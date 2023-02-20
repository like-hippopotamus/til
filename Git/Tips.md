[.gitignoreの書き方](http://www-creators.com/archives/1662)

[Github の master ブランチ変更](https://qiita.com/hokorobi/items/b884b8e854596a124159)

##### 不要なブランチ削除
```sh
# remoteリポジトリのマージ済みブランチを表示
git branch -a --merged | grep -v 'master\|develop' | grep remotes/origin | sed -e 's% *remotes/origin/%%'

# remoteリポジトリのマージ済みブランチを削除
git branch -a --merged | grep -v 'master\|develop' | grep remotes/origin | sed -e 's% *remotes/origin/%%' | xargs -I% git push origin :% --no-verify

# localブランチのマージ済みブランチを表示
git branch --merged | grep -v 'master\|develop'

# localブランチのマージ済みブランチを削除
git branch --merged | grep -v 'master\|develop' | xargs -I% git branch -D %
```
