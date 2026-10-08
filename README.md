# 関東学園大学附属高校野球部 サイト

## 公開手順（GitHub Pages）
1. GitHubで新規リポジトリ `kgf-baseball` を作成（Public）
2. 「uploading an existing file」から、このフォルダの中身をすべてドラッグ＆ドロップ → Commit
3. Settings → Pages → Source: Deploy from a branch / Branch: main・/(root) → Save
4. 数分後 https://hato-ux.github.io/kgf-baseball/ で公開

※ リポジトリ名や独自ドメインを変える場合は、次の4ファイルの
  `https://hato-ux.github.io/kgf-baseball/` を一括置換してください：
  index.html / robots.txt / sitemap.xml（＋このREADME）

## Google登録
1. https://search.google.com/search-console →「URLプレフィックス」に公開URLを入力
2. 所有権の確認：「HTMLタグ」を選び、表示された <meta name="google-site-verification" ...> を
   index.html の <head> 内に貼って再アップロード → 確認
3. 左メニュー「サイトマップ」に `sitemap.xml` を送信
4. 「URL検査」→ 公開URL →「インデックス登録をリクエスト」

## 更新するとき
index.html を編集して同じ場所に再アップロードするだけ。画像は img/ フォルダ。
