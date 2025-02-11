# pra_eccube2

### db

`docker exec -it ec-cube2-mysql-1 mysql -u root -p`

### git

- 基本操作
  注意：ls と pwd でディレクトリ確認してから！

```
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yu-ka3028/pra_eccube2.git
git push -u origin main
```

- エラー対応
  ローカル -> リモート(強制)
  `git push -u origin main --force`
  