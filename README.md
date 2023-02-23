## GitHub Actions ワークフローを使用した簡単な Javaアプリケーション のビルドのサンプル
- Spring Boot を使用した HelloWorld を表示するWebアプリケーション
- スターターワークフローの `Java with Maven` を流用。ビルドのみでデプロイはしない。
- Memo: 依存関係グラフとは?
  - https://docs.github.com/ja/code-security/supply-chain-security/understanding-your-software-supply-chain/about-the-dependency-graph
- advanced-security/maven-dependency-submission-action が **Resource not accessible by integration** で失敗する場合の対処
  - リポジトリのSettings > Actions > General > Workflow permissionsを
Read repository contents permission から Read and write permissions に変更する

