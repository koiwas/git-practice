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

## 基本操作2

### イニット
※スクラッチでも既存でも可
```
git init {project-name}
```
