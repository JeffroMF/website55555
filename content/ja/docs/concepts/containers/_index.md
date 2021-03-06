---
title: コンテナ
weight: 40
description: アプリケーションとランタイムの依存関係を一緒にパッケージ化するための技術
reviewers:
content_type: concept
no_list: true
---

<!-- overview -->

実行するそれぞれのコンテナは繰り返し使用可能です。依存関係を含めて標準化されており、どこで実行しても同じ動作が得られることを意味しています。

コンテナは基盤となるホストインフラからアプリケーションを切り離します。これにより、さまざまなクラウドやOS環境下でのデプロイが容易になります。




<!-- body -->

## コンテナイメージ {#container-images}
[コンテナイメージ](/ja/docs/concepts/containers/images/)はすぐに実行可能なソフトウェアパッケージで、アプリケーションの実行に必要なものをすべて含んています。コードと必要なランタイム、アプリケーションとシステムのライブラリ、そして必須な設定項目のデフォルト値を含みます。

設計上、コンテナは不変で、既に実行中のコンテナのコードを変更することはできません。コンテナ化されたアプリケーションがあり変更したい場合は、変更を含んだ新しいイメージをビルドし、コンテナを再作成して、更新されたイメージから起動する必要があります。

## コンテナランタイム

{{< glossary_definition term_id="container-runtime" length="all" >}}

## {{% heading "whatsnext" %}}

* [コンテナイメージ](/docs/concepts/containers/images/)についてお読みください。
* [Pod](/ja/docs/concepts/workloads/pods/)についてお読みください。
