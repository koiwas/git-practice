# git-branch

## ブランチ操作

### ブランチの確認

```
git branch
```

### ブランチの切替

```
git switch
```

### ブランチの作成と切替

```
git switch -c {branch-name}
```

### ブランチの確認

```
git branch -a
```

### ブランチの削除

```
git branch -d {branch-name}
```

### ブランチ名の変更

```
git branch -m {branch-name} {branch-name}
```

## マージ操作

### マージ

```
git merge {branch-name}
```

### diff

```
git diff {branch-name} {branch-name}
```

### マージの種類
- Fast forward

    merge先に変更がなくmerge元の内容を直線的に反映する

- Automatic merge

    merge先とmerge元のコミット間に同一箇所の変更がない(自動で対処)

- Merge conflict

    merge先とmerge元とのコミット間に同一箇所の変更がある(手動で対処)
