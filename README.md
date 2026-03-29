# ゲームタイマー - iPhoneアプリ化の手順

## ファイル構成
```
index.html   ← メイン画面
manifest.json ← アプリ情報
sw.js        ← オフライン対応
icon.svg     ← ホーム画面アイコン
```

---

## ① GitHubアカウントを作る（持っている人はスキップ）

1. https://github.com にアクセス
2. 「Sign up」でアカウント作成（無料）

---

## ② リポジトリを作る

1. GitHubにログイン後、右上の「＋」→「New repository」
2. Repository name に `game-timer` と入力
3. **Public** を選択（重要）
4. 「Create repository」をクリック

---

## ③ ファイルをアップロードする

1. 作成したリポジトリのページで「uploading an existing file」をクリック
2. 4つのファイルをすべてドラッグ＆ドロップ
   - index.html
   - manifest.json
   - sw.js
   - icon.svg
3. 「Commit changes」をクリック

---

## ④ GitHub Pagesを有効にする

1. リポジトリの「Settings」タブをクリック
2. 左メニューの「Pages」をクリック
3. Branch: **main** を選択 → Save
4. 数分待つと URL が表示される
   例: `https://あなたのユーザー名.github.io/game-timer/`

---

## ⑤ iPhoneのホーム画面に追加する

1. iPhoneのSafariで上記URLを開く
2. 画面下の「共有」ボタン（□↑）をタップ
3. 「ホーム画面に追加」をタップ
4. 「追加」をタップ

これでアプリとして起動できます！

---

## メモ
- オフラインでも動作します（一度開いた後）
- URLバーが消えてフルスクリーン表示になります
- Chromeでも同様の手順でホーム画面に追加できます
