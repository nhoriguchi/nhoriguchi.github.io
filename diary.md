# ブログ的ななにか

基本的に普段思ったことなどは Twitter に流すようにしているが、たまにまとまった情報を公開したいと思うことがあり、Qiita やはてなは色々合わないなと思うことがあったので、ちょうどよい GitHub Pages のホスティング機能を利用してみる。

## GitHub Coder Owner (2020/05/23 03:22)

GitHub には [code owner 機能](https://help.github.com/en/github/creating-cloning-and-archiving-repositories/about-code-owners) というのがある。特定のディレクトリやファイルごとに所有者 (メイン担当者) を決めるというもので、PR が登録されたときに、その PR が変更するディレクトリやファイルに応じて自動的にレビュー担当者を決めてくれる。実運用していれば、誰がレビューするかお見合い状態になって、開発プロセスが遅くなってしまうということがあるので、この手の細かい自動化は重要である。私が最近主に活動している MinBFT では https://github.com/hyperledger-labs/minbft/pull/187/files のとおり担当者が決まった。PR の登録者がメンテナであることが多いため、全てのディレクトリ・ファイルに二人を担当することにしている。その結果、私は全部担当者になってしまったように見えるが、これでどこまで機能するか...。
