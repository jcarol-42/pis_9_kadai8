# pis_9_kadai8

## study GitHub

## Contributing

### Forkする
GitHub上でforkする

### Forkしたリポジトリをローカルへcloneする

```
$ git clone https://github.com/Kahorin/pis_9_kadai8.git
```

### ローカルでのgit設定

```
$ cd pis_9_kadai8
$ git init
$ git config --global user.name "ユーザー名"
$ git config --global user.email メールアドレス
$ git remote add upstream https://github.com/Kahorin/pis_9_kadai8.git
```

### ブランチ作成＆ブランチ確認

```
$ git checkout -b 作成するブランチ名
$ git branch -a
```

### 編集してpushする

- 任意のファイルを編集/作成する

```
$ git add .
$ git commit -m "コミットメッセージ"
$ git push origin 作成したブランチ名
```

### プルリクエスト作成
GitHub上でプルリクエスト作成
Compare & pull requestボタン → Create pull requestボタン

### マージ（リポジトリオーナ）
プルリクエストを確認してリポジトリオーナがmasterへmergeする
trying jcarol
