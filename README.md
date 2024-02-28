# proofreading-tool_setup
文章校正ツール (proofreading-tool) の初心者向け導入方法と設定ファイル。  
[開発元サイト](https://github.com/gecko655/proofreading-tool?tab=readme-ov-file)を読んでインストールできる人は読まなくても大丈夫です。

## macOS版 インストール方法
1. proofreading-tool の[開発元サイト](https://github.com/gecko655/proofreading-tool?tab=readme-ov-file)に行く
2. [Installページ](https://github.com/gecko655/proofreading-tool/releases)に行く 
3. 最新バージョンの dmg ファイルをダウンロード。これを書いている時点では proofreading-tool-1.0.11.dmg が該当。
4. dmg ファイルをダブルクリックで実行
5. 「文章校正ツール」のアイコンを “Applications” フォルダにドラッグ＆ドロップする
6. Finder の「アプリケーション」の中に「文章校正ツール」があるのでダブルクリックして実行
7. ダイアログで「“文章校正ツール” は開発元を検証できないので開けません」と言われる。「キャンセル」を選択。
8. 左上のリンゴマーク → 「システム設定」 → 「プライバシーとセキュリティ」 → 「セキュリティ」欄の「“文章校正ツール” は開発元を検証できないため、使用がブロックされました」にて「このまま開く」を選択。
9. パスワードを聞かれるので入力する。さらに「“文章校正ツール” を開いてもよろしいですか？」と聞かれる。「開く」を選択。
10. 文章校正ツールのウィンドウが起動する。「設定ファイルを開く」をクリック。
11. 設定ファイル一式を収納した “textlint_config” というフォルダが表示される。こちらのフォルダに、当レポジトリで配布する [textlintrc.yml](/textlintrc.yml ) をコピーする。
12. 文章校正ツールを再起動する。（いったん閉じてまた開く）
13. 文章校正ツールに原稿ファイル（Word, PowerPoint ファイルなど）をドラッグ＆ドロップする。要修正箇所が表示される。

## Windows版 インストール方法
1. proofreading-tool の[開発元サイト](https://github.com/gecko655/proofreading-tool?tab=readme-ov-file)に行く
2. [Installページ](https://github.com/gecko655/proofreading-tool/releases)に行く
3. 最新バージョンの exeファイルをダウンロード。これを書いている時点では proofreading-tool-setup-1.0.11.exe が該当。
4. exe ファイルをダブルクリックで実行
5. 「Windows によって PC が保護されました」が表示される場合は、詳細情報を押したうえで実行をクリック
6. すべてのアプリでみると「文章校正ツール」が追加されているので、ダブルクリックして開く
7. 文章校正ツールのウィンドウが起動する。「設定ファイルを開く」をクリック。
8. 設定ファイル一式を収納した “textlint_config” というフォルダが表示される。こちらのフォルダに、当レポジトリで配布する [textlintrc.yml](/textlintrc.yml ) をコピーする。
9. 文章校正ツールを再起動する。（いったん閉じてまた開く）
10. 文章校正ツールに原稿ファイル（Word, PowerPoint ファイルなど）をドラッグ＆ドロップする。要修正箇所が表示される。


## ライセンス
当レポジトリの [textlintrc.yml](/textlintrc.yml ) は GPL-3.0 ライセンスのソフトウェア https://github.com/gecko655/proofreading-tool のオリジナルの設定ファイル textlintrc.yml にパラメータ値の変更を加えたものです。
