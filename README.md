# はなちょうちんパッチン！ 🐻💤

眠っているクマの「はなちょうちん（鼻ちょうちん）」を、大きく膨らんだ瞬間を狙ってタップして割るタイミングゲームです。

<img width="458" height="632" alt="Screenshot 2026-07-26 at 8 29 36" src="https://github.com/user-attachments/assets/fa3b5889-2947-4cef-a76b-d2caf74f3a95" />

## 🎮 遊ぶ

GitHub Pages で公開しています。

**https://ham0215.github.io/snot-bubble-game/**

## 📖 遊び方

1. 眠っているクマの鼻から、はなちょうちんが膨らんだり縮んだりします
2. はなちょうちんをタップ（クリック）すると割れて、クマが起きます
3. 割った瞬間のはなちょうちんの大きさでスコアが決まります

| タイミング | 判定 | スコア |
| --- | --- | --- |
| 小さいとき | Good! | 10点 |
| 中くらいのとき | Great! | 50点 |
| 大きく膨らんだ瞬間 | PERFECT!! | **100点** |

クマはしばらくするとまた眠るので、繰り返し起こしてハイスコアを目指しましょう。

https://github.com/user-attachments/assets/df64ac16-242c-4caa-a61a-2bc5b37c2d0c

## 🛠 技術構成

- 単一の `index.html` のみで動作（ビルド不要）
- [React 18](https://react.dev/)（UMD版）+ [Babel Standalone](https://babeljs.io/docs/babel-standalone) でブラウザ上で直接JSXを実行
- [Tailwind CSS](https://tailwindcss.com/)（CDN版）でスタイリング
- SVG + CSSアニメーションでクマとはなちょうちんを描画

## 🚀 ローカルで動かす

ビルドやインストールは不要です。`index.html` をブラウザで開くだけで遊べます。

```bash
git clone https://github.com/ham0215/snot-bubble-game.git
cd snot-bubble-game
open index.html  # またはブラウザで index.html を開く
```

## 📦 GitHub Pages の公開設定

リポジトリの **Settings → Pages** で以下を設定すると公開されます。

- **Source**: Deploy from a branch
- **Branch**: `main` / `/ (root)`

## 📄 ライセンス

[MIT License](LICENSE)
