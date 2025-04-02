# WildRift-Feed! 🎮✨

> 💫 **Wild Rift の最新情報をお届け！**
>
> 毎日 2 回、自動で最新ニュースをチェックして RSS フィードに変換するよ〜！

> 🎯 **このプロジェクトについて**
>
> このプロジェクトは [Vinnl/feeds](https://github.com/Vinnl/feeds) からフォークして作ったよ！
> 元のプロジェクトはいろんな RSS フィードを作れるツールだったけど、Wild Rift のニュースに特化させちゃった ✨

## ✨ 主な特徴 ✨

- 🎮 Wild Rift の公式ニュースを 1 日 2 回自動でチェック
- 📱 最新のアップデートやイベント情報を RSS フィードでお届け
- ⚡ GitHub Actions で常に最新情報をキャッチ

## 🛠️ セットアップ方法

### GitHub で設定する場合

1. このリポジトリをフォークするよ〜
2. `gh-pages` という名前のブランチを作成
3. フォークしたリポジトリの _Actions_ タブでワークフローを有効化
4. GitHub Pages の設定で `gh-pages` ブランチを選択
   [詳しい設定方法はこちら](https://docs.github.com/ja/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site)

これで設定完了！GitHub Actions が 1 日 2 回（午前と午後）自動的に実行されて、最新ニュースをチェックするよ〜✨

### GitLab で設定する場合

1. このリポジトリをフォーク
2. [新しいパイプラインスケジュールを作成](../../pipeline_schedules/new)（Build ˃ Pipeline schedules）
3. 実行時間を設定（例：`30 5,17 * * *` で 5:30 と 17:30 に実行）
4. "Save pipeline schedule" をクリック

これで準備 OK！GitLab CI/CD が設定した時間に自動で実行されるよ〜💫

## 📱 フィードの内容

- 📝 パッチノート
- 🎉 イベント情報
- 👑 チャンピオン情報
- 🎮 ゲームシステムの更新
- 📰 その他の Wild Rift 関連ニュース

---

> 💖 このプロジェクトを気に入ってくれたら、スターを付けてくれると嬉しいです！
