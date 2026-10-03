# よぴぴっぴのゲーム棚

Claude で作ったブラウザゲーム41本と、その攻略・BGMをまとめたサイト。GitHub Pages でそのまま公開できる静的ファイルだけでできている。

- `index.html` … ゲーム棚(ゲーム / 解説・攻略 / BGM の3タブ)
- `games/<id>/` … 各ゲーム本体(1ファイル完結)
- `guides/<name>/` … 攻略・解説ページ
- `shots/` … スクリーンショット、`bgm/` … BGM の mp3

## 公開のしかた
1. GitHub で新しいリポジトリを作る(例: `game-shelf`、Public)
2. このフォルダの中身をすべてアップロード(「Add file → Upload files」にドラッグ)
3. Settings → Pages → Source を「Deploy from a branch」、Branch を `main` / `(root)` にして Save
4. 数分後に `https://<ユーザー名>.github.io/<リポジトリ名>/` で公開される

メモ: 「人気順」は claude.ai 版だけの機能なので、GitHub Pages 版では自動で非表示になる。
