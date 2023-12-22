# git-fundamental

## 基本操作1

### リモートリポジトリのクローン

```
git clone {remote-url}
```

### リモートリポジトリの確認
```
git remote -v
```

### ブランチの確認

```
git branch
```

### ブランチの作成と切替

```
git switch -c {branch-name}
```

### 作業状態の確認

```
git status
```

### ステージング

```
git add README.md
```

### コミット

```
git commit -m "update readme"
```

### コミットの履歴
※origin=リモート, HEAD=現在のブランチ
```
git log
```

### プル

```
git pull origin {branch-name}
```

### プッシュ

```
git push origin {branch-name}
```

### マージ(PR)

*Check Pull requests*

### ブランチの削除

```
git branch -d {branch-name}
```

### リモート追跡ブランチの削除

```
git fetch --prune
```

## 基本操作2

### init
※スクラッチでも既存でも可
```
git init {project-name}
```

### track済みファイルの確認

```
git ls-files
```

### unstage

```
git restore --staged {file-name}
```

### working directoryの内容を破棄

```
git restore {file-name}
```

### ファイル名の変更
※track済みファイルのみ
```
git mv {file-name} {new-file-name}
```

### ファイルの削除
※ステージング不可
```
git rm {file-name}
```

### ログの短縮表示
```
git log --oneline
```
