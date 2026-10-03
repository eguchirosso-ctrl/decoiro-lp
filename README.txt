デコいろ X需要検証LP

内容
- index.html : LP本体
- .nojekyll : GitHub Pages向け（Jekyll処理を無効化）
- assets/decoiro-hero.webp : 採用したLPファーストビュー画像（WebP圧縮済み）
- assets/x/decoiro-x-organic-square.png : X通常投稿用 1:1画像
- assets/x/decoiro-x-ad-landscape.png : X広告用 横長画像

設定済み
- Formspree endpoint: https://formspree.io/f/myezrddy
- UTM自動取得: utm_source / utm_medium / utm_campaign / utm_content / utm_term
- LP URL / referrer の送信
- スマホ対応

ファーストビュー
- デコいろ
- 好きなデコを、もっと見つける。
- 硬質ケース、手帳、スマホケース、痛バッグ、ぬい小物。いろいろなデコ作品を投稿して、見つけて、保存できるコミュニティ。
- CTA: リリース通知を受け取る

用語ルール
- 正式ブランド名: デコいろ
- 一般語: デコ
- 完成物: デコ作品
- カテゴリ: ○○デコ
- ひらがなの「でこ」は使用しない

タイポグラフィ方針
- 大人っぽく洗練されたモダンなサンセリフ系
- 濃いチャコールを基本文字色とする
- ウェイト・サイズ・余白で階層化する
- 子どもっぽい丸文字、手書き風、過度な多色文字、太い縁取り、派手な影、文字まわりのキラキラ・ハート装飾は使わない
- LP・X・広告・アプリ内UIで同じ方針を維持する

GitHub Pages 公開設定
1. GitHubで新しいリポジトリを作成（推奨名: decoiro-lp）
2. このフォルダの中身をリポジトリ直下に配置
3. Settings > Pages を開く
4. Source: Deploy from a branch
5. Branch: main / /(root)
6. Save
7. 公開URLは通常 https://<GitHubユーザー名>.github.io/decoiro-lp/

公開後テスト
- LPがPC/スマホで正しく表示される
- CTAからフォーム位置へ移動する
- Formspreeへテスト登録が1件送信される
- Formspree Submissionsに登録が表示される
- support@marueworks.com に通知メールが届く
- UTM付きURLから登録し、utm_source等がFormspreeに保存される

需要検証用UTM例
通常投稿:
?utm_source=x&utm_medium=organic&utm_campaign=demand_validation&utm_content=post_01

広告:
?utm_source=x&utm_medium=paid&utm_campaign=demand_validation&utm_content=ad_01
