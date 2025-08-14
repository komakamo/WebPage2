# GitHub Pages Starter (JP)
最小構成の GitHub Pages サイトです。`index.html` を含むルートを `Settings > Pages` から公開します。

## 公開手順（ブランチから）
1. このフォルダを GitHub にプッシュ（例: `my-website`）
2. GitHub のリポジトリ画面で **Settings > Pages**
3. **Build and deployment** を **Deploy from a branch** に設定
4. **Branch**: `main` / **Folder**: `/ (root)` を選択して **Save**
5. 数分後、右上に公開 URL が表示されます

## 備考
- 画像や CSS/JS は同階層に置いて OK
- SPA の場合は 404 対策が必要（`404.html` を用意）
- Jekyll を無効化したい場合は `.nojekyll` を追加
