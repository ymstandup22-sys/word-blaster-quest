# Word Blaster Quest

英単語をテーマにした、ブラウザで遊べるオフライン対応のHTMLゲームです。

## 公開方法

このリポジトリをGitHub Pagesで公開すると、`index.html` がゲーム本体として表示されます。

1. GitHubのリポジトリ設定を開く
2. `Pages` を開く
3. `Deploy from a branch` を選ぶ
4. `main` / `/root` を選ぶ
5. 表示されたURLを共有する

## 学校・Chromebook向け

- ゲーム本体は単一HTMLです。
- 画像やライブラリを外部CDNから読み込みません。
- 生徒側でファイルをダウンロードする必要はありません。
- 学校のフィルタでGitHub Pagesが止まる場合は、公開URLを許可リストに追加してください。

## ファイル

- `index.html`: ゲーム本体
- `teacher.html`: 学校管理者向け案内
- `privacy.html`: プライバシーポリシー
- `terms.html`: 利用規約
