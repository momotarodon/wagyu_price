# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
- リモートリポジトリはネット上に配置して複数人で共有するためのリポジトリ。
- ローカルリポジトリは開発者一人ひとりが使用するために,自分のPC上に配置するためのリポジトリ。

## プッシュとマージの違いは何でしょうか？
- プッシュは現在のブランチの変更をリモートのブランチに反映させること
- マージは別のブランチの変更履歴(commit履歴)を対象ブランチに取り込むこと

## コミットとプッシュの違い
- コミットはgitのリポジトリに変更内容を登録すること
- プッシュは現在のブランチの変更をリモートのブランチに反映させること

## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
- 対象コミットで行った変更内容を簡潔に記述すること。

## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
- ローカルでマージする場合、他の人からのコードレビューを受けることができない。
- リモートでマージする場合はプルリクエストを作成することで、
他の人からのコードレビューを受けることができ、バグを未然に防ぐことができる。

## コンフリクトを起こしてしまった場合、どう対処すべきですか？
- 話し合いをしながら適切な差分を取り込み後、対象ブランチにてadd -> commit -> pushを行う。