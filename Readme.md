## 2 系と 4 系の比較

[Notion](https://www.notion.so/3D-195d66877e088046832cf1a8a142aa3a?pvs=4)

- 2025/02/07:ページ設定
- 2025/02/08:
  - ボタンのホバー設定
  - コアとカスタマイズファイルの配置
- 2025/02/09:3D セキュア認証対応


## Linux

- ディレクトリを消す`rm -r ファイル名`

## git

- 強引にローカルの状態で push する`git push origin main --force`
- -u オプションの解除`git push origin --unset-upstream`
- 基本操作
  注意：ls と pwd でディレクトリ確認してから！

```
git init
git commit -m "first commit"
git branch -M main
git remote add origin https://github.com/yu-ka3028/pra_eccube2.git
git push -u origin main
```

# pra_eccube2

### db

`docker exec -it コンテナ名`


# issue テンプレート(設定するまで一時置き場)

```md
# 概要

---

## 実装内容

### path

### todo

- [ ]
- [ ]
- [ ]

### ゴール

-

# 参考文献と考察

# 備考
```