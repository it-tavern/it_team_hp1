# it_team_hp1
チーム開発の1個目->内容はみんなできめる
## git cloneする
```
git clone https://username:password@github.com/it-tavern/it_team_hp1
```
を打つ  
※passwordはloginパスワードではなく、tokenを取得する  
Settings/Developer settings/Personal access tokensから取得  
※clone先のURLはgit 右上の緑ボタンからコピー

## branchを切って、pushしてみる
注意事項として、mainブランチに直接pushしてはいけません。  
後日作りますが、developブランチからブランチを切ってください。
```
git branch #現在のブランチを確認
git branch feature/name_作業 #ブランチの命名規則をつけるかは決めてません ブランチ作成
```
feature/name_作業でコードを変更します。  
```
git add . #.(dot)は変更全ファイルです
git commit -m "作業内容" #コメント
git push
```
上記でpush完了です。  
終わったらdevelopにPRしてください。

## タスク
1. どんなものを作るか会議(HP)
IT 酒場のHPを作成
2. どんな言語を使うか
フロントエンド
- three.js
- cssはもちろん使うよ。

バックエンド
- js
- msyql


フロントエンド兼簡単なデザイン
・figma予定
・FV
・コミュニティについて
・サービス内容
・コミュニティのようす
・開発チーム紹介
・ログイン機能
・料金プラン
・申し込み

バックエンド
・料金
・申し込み

大枠でインフラ(ロリポップ)
・ゆいさん、僕、やりたい人いれば