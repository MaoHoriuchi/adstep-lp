# AdStep LP

AdStep のランディングページ。GitHub Pages で公開。

## 公開 URL

https://maohoriuchi.github.io/adstep-lp/

## 構成

```
adstep-lp/
├── index.html          メインページ（元: AdStep Site.html）
├── assets/             画像・ロゴ
├── tweaks-panel.jsx    調整用パネルコンポーネント
└── README.md
```

## ローカル確認

任意のブラウザで `index.html` を開く、または：

```bash
npx serve .
```

## デプロイ

`main` ブランチに push すると GitHub Pages が自動更新。

## 編集

- ローカル編集: VS Code 等で `index.html` を直接編集 → push
- GitHub Web エディタ: ファイルを開いて画面右上の鉛筆アイコン
- VS Code Web: リポジトリ画面で `.` キーを押すと vscode.dev で開く
