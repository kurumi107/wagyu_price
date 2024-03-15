# Git Lesson

## リモートリポジトリとローカルリポジトリとはそれぞれ何でしょうか？
  -  リモートリポジトリはローカルリポジトリで作成したファイルや変更履歴を保存しておけるウェブ上の保存場所
  -  ローカルリポジトリは作成したファイルや変更履歴を保存しておける自分のPC内の保存場所

## プッシュとマージの違いは何でしょうか？
  -  プッシュはローカルリポジトリで作成されたファイルや変更履歴をリモートリポジトリへ反映させることで、マージは枝分かれしたブランチをまとめること



## コミットとプッシュの違い
  -  コミットはローカルリポジトリに変更した内容を記録することで、プッシュはローカルリポジトリからリモートリポジトリへ反映させること



## コミットのメッセージはどのように書いてあげるのが最適でしょうか？
  -  基本はどのファイルをどのように追加・変更・修正したのか入力して、過去の履歴に戻り値時にコミットメッセージを見ただけで分かるようにする。ただ今後作業に入ったときは各チームの記入ルールがあるため最初に確認する。


## ローカルでマージするフローと、プルリクエストでマージするフローの違いは何でしょうか？
  -  ローカルは作業ブランチからメインブランチへマージをして、リモートメインブランチにプッシュする。プルリクエストはローカル作業ブランチからリモート作業ブランチへプッシュする。リモート作業ブランチからリモートメインブランチへプルリクエストを行い問題なければリモートメインブランチへマージを行う。リモートメインブランチからローカルメインブランチへプルを行う。



## コンフリクトを起こしてしまった場合、どう対処すべきですか？
  -  複数人でコンフリクトが発生した場合、どのソースコードが合っているのか、全て統合するのか相談をする。最終的には上書きをする。