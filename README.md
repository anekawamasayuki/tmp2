# 大問 2

本大問はアプリケーションを開発する上で重要となる設計力を問う問題である。  
以下の「問題」と「解答の提出」をよく読んで、解答してください。

## 問題

この問題は自由記述です。基本的にテキストのみで回答可能ですが、画像等を回答に含めても構いません。  
以下の要件を満たすシステム構成と構成に含まれるコンポーネントの役割に関する仕様書を作成してください。

- 本アプリケーションはオセロ AI との対局をするものである。
- クライアント
  - クライアントにはウェブブラウザを想定し、オセロ AI と対局できる Web アプリケーションを利用する。
  - Web アプリケーションに関してはすでに実装済みであり、任意の方法でデプロイすることが可能とする。
- サーバー
  - サーバーはクライアントから受け取った盤面情報を AI モデルに渡し、解析結果をブラウザに返却する。
  - 勝敗情報と盤面のデータをデータベースに格納する。
  - デプロイ方法、デプロイ先に制限はなく、任意の方法でデプロイすることが可能とする。
- ネットワーク
  - データベースにはサーバーからのみアクセス可能な状態とすること。
  - テーブルスキーマについては考える必要はありません。
- SNS 等で広まることによる一時的な大規模トラフィックを想定した構成にすること。
- 環境はオンプレでもクラウドでもよいことにする。
  - オンプレの場合はハードウェアやソフトウェア名を記述すること。
  - クラウドの場合は AWS や GCP、Azure 等のサービス名を用いること。
  - ハードウェア、ソフトウェア、サービス名それぞれの役割を記述すること。

## 解答の提出

- 作成した仕様書を Problem2 直下に配置し、**ご自身の** 公開 git レポジトリにプッシュしてください。
- 仕様書のフォーマットに指定はありませんが、MD ファイルを推奨します。
