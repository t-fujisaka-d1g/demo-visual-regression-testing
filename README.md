# Visual Regression Testing デモ
## ローカルで実行する手順
### 1. 依存関係をインストール
```shell
npm ci
```

### 2. スクリーンショットを撮影・保存
```shell
npm run screenshot
```

### 3. 画像比較
```shell
npm run report-gen
```

### 4. 結果を確認
```shell
open ./docs/index.html
```
※ docs/index.htmlをブラウザで開く

