# タイトル：Wikipediaのログ解析システム

### タスク
- データベース及びテーブルを作成し、データをインポートしてください。その上で、以下を算出するコマンドラインプログラムを作成してください。

1. 最もビュー数の多い記事を、指定した記事数分だけビュー数が多い順にソートし、ドメインコードとページタイトル、ビュー数を提示する

2. 指定したドメインコードに対して、人気順にソートし、ドメインコード名と合計ビュー数を提示する

### 要件

- 1つのタスクは1つのクエリで算出する
- SQLのスタイルガイドを意識してクエリを書く
- PHPのコードはコーディング規約に則って書く
- プロジェクトのディレクトリトップにREADME.mdファイルを作成し、プログラムの使い方を書く

#### データ

- データは2022年12月1日のもの
  - https://dumps.wikimedia.org/other/pageviews/2022/2022-12/

