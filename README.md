# CNC 加工見積もりツール

DXFファイルからCNC加工のツールパスを計算し、概算見積もりを作成するWebアプリケーションです。

## 機能

- 📐 DXFファイルの読み込みと可視化
- 📊 ツールパス情報の自動計算（切削総長、穴加工数、直線数、曲線数）
- 💰 素材情報・加工単価・人工数から見積もりを自動計算
- 📄 見積書のHTML形式での出力
- 🎨 ダーク/ライトテーマの切り替え

## 使い方

### Web版（GitHub Pages）

**https://あなたのユーザー名.github.io/dxf_viwer/cnc_estimator/**

### ローカルで実行

1. `cnc_estimator/index.html` をブラウザで開く
2. DXFファイルをドラッグ＆ドロップまたは選択
3. 素材情報・加工単価・人工数を入力
4. 見積もり結果を確認し、見積書を出力

## 対応素材

- ラワン合板
- シナ合板
- CLT
- MDF
- ヒノキ
- スギ
- タモ
- ナラ
- カスタム

## 技術スタック

- HTML5
- CSS3 (CSS Variables, Flexbox, Grid)
- Vanilla JavaScript
- Canvas API

## ライセンス

MIT License

