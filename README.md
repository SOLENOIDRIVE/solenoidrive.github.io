# SOLENOIDRIVE - Research Projects Documentation

統合されたプロジェクトドキュメントサイトです。

## プロジェクト一覧

### 1. RealSense Road Scanner
深度センシング技術と物理フィードバックを統合した路面監視システム

- [初学者向けガイド](realsense-guide.html)
- [技術解説書](realsense-thesis.html)
- [GitHub Repository](https://github.com/SOLENOIDRIVE/RealSense-Road-Scanner)

### 2. QRコード回転速度測定システム
単眼カメラとQRコードによる非接触計測システム

- [初学者向けガイド](qrcode-guide.html)
- [技術解体新書](qrcode-thesis.html)
- [GitHub Repository](https://github.com/SOLENOIDRIVE/QRCode-inclination)

## ファイル構成

```
github pages/
├── index.html              # トップページ（プロジェクト一覧）
├── styles.css              # 統一スタイルシート
├── new-logo.png            # ロゴ画像
├── realsense-guide.html    # RealSense 初学者向けガイド
├── realsense-thesis.html   # RealSense 技術解説書
├── qrcode-guide.html       # QRCode 初学者向けガイド
├── qrcode-thesis.html      # QRCode 技術解体新書
└── README.md               # このファイル
```

## GitHub Pagesへのデプロイ

このフォルダをGitHub Pagesのソースとして設定してください。

1. リポジトリの Settings → Pages
2. Source: `main` branch, `/github pages` folder
3. または `docs` フォルダにリネームして使用

## ライセンス

© 2025 SOLENOIDRIVE
