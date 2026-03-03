# The Ash 🥃

4人のバーテンダーと、今夜の一杯を。Powered by Anthropic's Claude.

## Deploy to GitHub Pages

### 1. GitHubリポジトリを作る

[github.com/new](https://github.com/new) で新しいリポジトリを作成。
名前は何でもOK（例：`the-ash`）。**Public** を選択。

### 2. ファイルをアップロード

リポジトリのページで **Add file → Upload files** をクリック。
`index.html` をドラッグ＆ドロップしてアップロード。

### 3. GitHub Pages を有効化

リポジトリの **Settings → Pages** を開く。

- **Source**: `Deploy from a branch`
- **Branch**: `main` / `(root)`
- **Save** をクリック

数分後、`https://[あなたのID].github.io/[リポジトリ名]/` でアクセスできる。

### 4. APIキーを入力して使う

初回アクセス時にAnthropicのAPIキー取得手順が表示される。
キーは [console.anthropic.com/settings/keys](https://console.anthropic.com/settings/keys) で取得できる。

キーはあなたのブラウザのlocalStorageにのみ保存される。サーバーには一切送信されない。

---

## ローカルで動かす場合

```
# ファイルをそのままブラウザで開くとCORS制限でAPIが動かないことがある
# 簡易サーバーを立てる

npx serve .
# または
python3 -m http.server 8080
```

---

## Bartenders

| | Name | Specialty |
|---|---|---|
| 🥃 | **Angus MacLeod** | スコッチ・バーボン・ウイスキー全般 |
| 🍶 | **雪乃** | 日本酒・焼酎・泡盛 |
| 🍹 | **Carlos Reyes** | カクテル・ラム・テキーラ・ジン |
| 🍷 | **Céleste Morel** | ワイン・シャンパン・コニャック |
