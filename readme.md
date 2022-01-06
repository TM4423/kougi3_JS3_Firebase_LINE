1. 受講番号:18 
1. 氏名: 三浦寿也
1. 課題番号: 18 
1. Github_URL: https://github.com/TM4423/kougi3
1. レビュー会参加: あり
1. API_KEY（任意）:
# ★何ができるか
- kadai-challenge.html
  - RealtimeDatabaseの振る舞いを確認するために、データの挿入、削除、keyを使った検索、並べ替えに加えて、1レコード削除を実現しました。
# ★頑張ったこと・こだわった点
- 一連の動作をできるだけ少ないコードで可読性よく書けるよう、短くするように心がけました。
- 課題の宿題として出されていたレコードの削除について、importしているのに使っていなかったonChildRemovedをつかって実装したかったのですが、keyの取得方法がわからず、苦労しました。
- 削除について、はじめはnullをsetする方法を使っていました。remove()の使い方がわからず、keyを埋めてもうまく動作しないので悩みましたが、/で階層を指定することができることに気づいて、うまく実装することができました。
- 最終的には、htmlソースの書き換えをonChildRemoved()に実施させて、データベースを操作しているルーチンとは書き分けることができました。
- とにかく、コピペをしたくないので、躓くことが多いですが、これだけは続けようと思います。形態素解析のモジュールをimportしたとき、ようやくCORSの問題に気づくことができましたので、これは大成果でした。
# ★疑問・質問/次回チャレンジしたいこと
- 言い訳にしかなりませんが、pythonに時間がかかりすぎたこと、理解するためにコードを一から手打ちしたために、時間が足りなくなったことで、思い通りの仕上がりには程遠くなりました。
- その代わりに、reactが向いていそうなこと、形態素解析ライブラリの導入に成功したこと（今回はRealtimeDatabaseへ値を渡せなかった）で、次に作りたいもののイージが膨らみました。
- データベースのリファレンスの使い方が、最後まで理解できませんでした。56行目のdbRef変数を使って、keyを指定する方法がわかりません。
- デザインに関することについて関心がなく、非常に苦手な意識を持っていましたが、reactで解決できそうな気がしてきましたので、次回から使ってみようと思います。