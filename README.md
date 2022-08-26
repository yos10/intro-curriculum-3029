# リポジトリを削除しない方法

2021 レベルアッププログラミング GitHub でチーム開発 基礎編

リモートリポジトリを追加する  
https://www.nnn.ed.nico/contents/guides/5593#header-3-b9cc26c24d6988df56dfbaef554c8bc2

```
git remote add upstream git@github.com:nnn-training/intro-curriculum-3002.git
```

```
git fetch --all
```

`git push` した時に origin に push するように

```
git push -u origin
```

あとはいつもどおりに

```
git switch main-2022
```
