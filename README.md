# 📍 GeoPhoto Map

現在地を取得して、その場所で撮影した写真をマップ上にピン留め・確認できるiOS最適化Webアプリケーションです。サーバー不要で、HTMLファイルを1つ置くだけでブラウザ単体で動作します。

## ✨ 特徴
- **スマホ(iOS Safari)完全対応**: セーフエリア対応、iOSネイティブ風のガラスモーフィズムUI、スムーズな操作感。
- **カメラ連携**: ボタンをタップすると外カメラが起動し、その場で撮影。
- **自動画像圧縮**: iPhoneの高解像度写真によるメモリ不足（クラッシュ）を防ぐため、自動で縮小・圧縮して保存。
- **永続化対応**: `localStorage` を使用しているため、ブラウザを閉じてもピン情報が消えません。
- **GitHub Pages対応**: 設定するだけで、スマホから簡単にアクセスしてテストできます。

## 🚀 使い方
1. リポジトリをクローンまたはダウンロード。
2. GitHubリポジトリに `index.html` をアップロード。
3. リポジトリの **Settings** > **Pages** から `main` ブランチを有効化して公開。
4. スマホのSafariで公開URLにアクセスし、位置情報の許可をしてお使いください。

## 🛠️ 使用技術
- [Leaflet.js](https://leafletjs.com/) (Open-source JavaScript library for mobile-friendly interactive maps)
- [CartoDB Basemaps](https://carto.com/basemaps/)
