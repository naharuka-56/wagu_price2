# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？

* リモートリポジトリ
  * ネット上にファイルやディレクトリの状態を記録する場所のこと
* ローカルレポジトリ
  * はPCにファイルやディレクトリの状態を記録している場所のこと

## プッシュとマージの違いは何でしょうか？

* プッシュ
  * ローカルリポジトリで変更した内容をリモートリポジトリに反映させること。
* マージ
  * ブランチの変更内容をブランチに取り込むとこ。

## コミットとプッシュの違い

* コミット
  * リポジトリに作業内容をセーブすること
* プッシュ
  * ローカルリポジトリで変更した内容をリモートリポジトリに反映させること。

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？

* 一目で変更内容が分かるように書く。
* プレフィックスをつけるなど各チームやプロジェクトのルールに従う。
* プレフィックスとは
  * コミットメッセージの先頭につける接頭辞。
  * つけることで、レビュワーが何に対する変更なのか見やすくなる。
* プレフィックスの例
  * add:ちょっとしたファイル・コードの追加 
  * change:ちょっとしたファイル・コードの変更 
  * fix:バグ修正

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？

* レビュー担当者のチェックが入るので、事前にバグを発見することが出来る。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？

1. 先にマージされた変更内容を取り込む
2. 後にマージしようとしている変更内容を取り込む
3. どちらの変更内容も取り込む
* 以上３通りがある
* プロジェクト内で起きてしまった起こしてしまった場合は、プロジェクトリーダーに報告をして、話し合いのうえで上記３通りから選んで行う。