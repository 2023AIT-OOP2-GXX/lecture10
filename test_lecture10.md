# 第10回振り返りレポート

## 1. GitHubアカウント

| 氏名           | 学籍番号    | GitHubアカウント(登録メールアドレス) |
| -------------- | ----------- | -------------------------------------- |
| 愛工　大郎     | K00000      | AIT_TARO (k00000kk@aitech.ac.jp) |

## 2. 作成した日記リポジトリのコミットログ

チームのOrganaizationにて作成した日記リポジトリをcloneしたローカルディレクトリにて、mainブランチをfetch/pullした後に、`$ git --no-pager log --graph`を実行し、結果を以下の`<rpe>〜</pre>`内に貼り付けます。

<pre>

</pre>


## 3. Git及びGitHubに関する調査

お試し￥・・・・・・・・・・・・・・・・・

・・・・

・・・・
・・・・

うんちうにつfsかdfskjl；あdfsk；jldsjk；dlsfjfkds


fkdふぁs；jkぁdfskjl；あdsfkj；ぁdsfk；jldさ’あdsっdsdsds

dsだsdさdkdksfdfsdsfdsfdsf
おmなああいおあえいえwjけwjけwjk；えwjk；ぇw
あfjkだfshjkhj；かhjk；wjkl；jk；rdsっfdsdfsdfs
rfhjkぁえgrhjk；あえrgじぇらgれg’えgrjk’あえgrw

rwけgrえr；mぁえtgぇkljkljr；’rwgあえrgdsっっfdsdfdfs


えあrがrげあらrがgれあrげあえrgdfsdfsdfsdfっっっっっっっっっっっっs


あsdっっっっっっっっっっっっっっっっっっっっf
dsfdfsdfsdfsdfs
fds
dfsdsfdfs
dsfdsfdfsdsfdfs


dfsdsfdsfdsっfdっっっっっっっっっっっdsfっっっっs
sdf
fsdfdsfds





kgdfskんl；あgdfkjl；あdfgk；ljふぁgdkj；ぁfgdjk；ぁfgdkjl；あdfgjkl；dfsdsvf
### 3-1. Gitを始めとしたバージョン管理システムを利用することによるメリットはなにか



### 3-2. Gitにおけるキーワード「clone」「commit」「push」「branch」「fetch」「pull」「merge」「rebase」についてそれぞれ何をするものか (他者に説明できるよう、わかりやすく簡潔な文章で表すこと)
#### 「clone」
　Gitにおけるcloneとはリモートリポジトリに保存されているプロジェクトのコードをローカルリポジトリに複製することである。複製されたコードをローカルで編集し、変更を加えることが可能である。1つのシステムを複数人で、同時に開発する場合に利用する。
参考文献(https://cmc-japan.co.jp/blog/what-is-github/)

#### 「commit」
　Gitにおけるcommitとは、変更したファイルやコードを保存する操作のことを指す。変更履歴の管理やコードの復元など、開発者が作業を進める上で重要な操作である。
参考文献(https://cmc-japan.co.jp/blog/what-is-github/)
#　杉山担当

#### 「push」
git pushはローカルリポジトリのオブジェクトをリモートリポジトリに送信して更新を行うコマンドである。<br>
<参考文献>(https://qiita.com/yunano/items/49cee64b98e242458a15)
#　田川担当

#### 「branch」
　Gitにおけるブランチとは、メインブランチから独立して機能追加や修正を行うことができる機能のことである。メインブランチから独立しているため、他のチームメンバーと競合することなく開発を行うことができる。<br>
　ブランチでの変更が検証された際には、マージを行うことでブランチの作業内容をメインブランチへと統合することができる。<br>
　また、ブランチはメインブランチに直接変更を加えることはないため、メインブランチには安定して動作するプログラムを常に置いておくことができる。<br>
<参考文献><br>
GitHub「ブランチの概要」(https://docs.github.com/ja/pull-requests/collaborating-with-pull-requests/proposing-changes-to-your-work-with-pull-requests/about-branches) 2023年12月17日閲覧<br>
#　Tsuzuki担当

#### 「fetch」
　fetchは、変更をコミットせずに、リモートリポジトリからローカルで作業中のブランチに追加する場合に使う。pullとは異なり、フェッチすると、ローカルブランチにコミットする前に変更をレビューできる。<br>
<参考文献><br>
GitHub,「GitHub 用語集」,(https://docs.github.com/ja/get-started/quickstart/github-glossary) ,2023年12月19日閲覧<br>
#　高野担当

#### 「pull」
git pullとは、リモートリポジトリから最新の状態をローカルリポジトリに反映するコマンドのことです。
状態と記載した通り、反映される対象はソースコード等のファイルだけではなく、履歴やログも含まれます。
複数人でシステム開発をする場合、各々の環境から作業を行うため、他の開発者が実装した内容をローカルリポジトリに取り込む必要があります。
「作業の初めに必ずgit pullを実行する」といったルールを作ることで、リモートリポジトリと差分のない状態で開発に着手することができます。
<参考文献>(https://tech-blog.rakus.co.jp/entry/20220805/git)
#　伊澤

#### 「merge」
　Gitにおけるmergeとは、異なるブランチに存在するコードの変更を1つのブランチに統合することを指している。チームメンバーはそれぞれ自分の作業用ブランチにてコードの変更を行い、作業用ブランチにおける開発が完了したらその変更をマスターブランチに取り込む。このように、mergeを行うことで複数の開発者が別々に作業を行っているブランチを統合し、コードの変更を反映させることができる。これにより、複数の開発者が共同でより高品質なソフトウェアを開発が可能となる。
参考文献(https://cmc-japan.co.jp/blog/what-is-github/)
#　今井担当

#### 「rebase」
#　？担当


### 3-3. プロジェクト進行に、Pull Requestを用いたGitHub Flowを採用することで、解決できるチーム開発での問題はなにか (実際にGitHub Flowで作業する手順も説明できる範囲でする)



ヨッシーーーーーーーーーーーーーーーーーーーーー


