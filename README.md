# Monochrome Image Converter 📷

ブラウザ上で画像を読み込み、瞬時にモノクロ（グレースケール）画像に変換するWebアプリケーションです。
サーバーへのアップロードを行わず、すべての画像処理をクライアントサイド（ブラウザ）だけで完結させるため、高速かつ安全です。

**👉 [デモサイトはこちら (Demo URL)](https://kobayasiayumu.github.io/Monochrome/)**

## ✨ 特徴 (Features)

* **直感的な操作**: クリックして画像を選ぶだけのシンプル設計。
* **リアルタイム処理**: HTML5 Canvas APIを使用し、ピクセルデータを直接操作して変換します。
* **高画質ダウンロード**: 変換した画像は JPEG または PNG 形式で保存可能です。
* **プライバシー保護**: 画像データは外部サーバーに送信されず、すべてユーザーのブラウザ内で処理されます。

## 🛠 使用技術 (Tech Stack)

ライブラリやフレームワークに頼らず、標準的なWeb技術のみで構築しました。

* **HTML5 / CSS3**
* **JavaScript (Vanilla JS)**
    * **Canvas API**: 画像のピクセルデータ（RGBA）の取得と書き換え
    * **FileReader API**: ローカルファイルの読み込み
    * **NTSC係数**: 自然なグレースケールを実現するための加重平均計算
      > 計算式: `Gray = 0.299*R + 0.587*G + 0.114*B`

## 🚀 使い方 (How to use)

1. **画像を選択**: 画面中央の枠をクリックし、変換したい写真（JPEG/PNG）を選択します。
2. **変換**: プレビューが表示されたら、「🔄 モノクロに変換」ボタンをクリックします。
3. **保存**: 変換結果を確認し、「JPEGで保存」または「PNGで保存」ボタンでダウンロードします。

## 👨‍💻 Author

* GitHub: [@AYUMU](https://github.com/KobayasiAyumu)
* Student at Human Academy IT College

---
&copy; 2026 Monochrome Converter
