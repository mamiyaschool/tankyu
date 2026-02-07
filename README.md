# 探究スキルカード

## GitHub へのアップロード手順

1. **GitHub で新しいリポジトリを作成**
   - https://github.com/new にアクセス
   - リポジトリ名を入力（例: `tankyu-skill-card`）
   - 「Create repository」をクリック

2. **ターミナルで以下を実行**（リモートはすでに登録済みです）

```bash
cd /Users/daisukemamiya/Desktop/探究カード
git branch -M main
git push -u origin main
```

3. **GitHub Pages で公開する場合**
   - リポジトリの「Settings」→「Pages」
   - Source で「Deploy from a branch」を選択
   - Branch で「main」、フォルダで「/ (root)」を選んで Save
   - 数分後、`https://mamiyaschool.github.io/tankyu/skillcard03.html` でアクセスできます

## カード裏面の画像について

Web 公開後、カード裏面画像を GitHub の URL で表示するには、`skillcard03.html` の `card_back_image_url` を次の形式に変更してください。

```
https://raw.githubusercontent.com/mamiyaschool/tankyu/main/カード裏面.png
```

※ ファイル名に日本語が含まれる場合は、GitHub 上での URL エンコードされた名前をブラウザのアドレス欄で確認して使用してください。
