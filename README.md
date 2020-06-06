# Tritask
タスク管理メソッド Tritask

## 仕様と実装
Tritask は仕様と実装に分かれています。

**仕様** とは Tritask というタスク管理メソッドについて記したものを指します。

**実装** とは仕様に基づいて開発を行い、タスク管理ツールとして仕上げたもの全般を指します。

元々は仕様を Tritask と呼び、実装を Tritask-XXX( [tritask-sta](https://github.com/tritask/tritask-sta) など)と呼んでいましたが、現在では Tritask-XXX のことを Tritask と呼ぶこともあります。

## 仕様としての Tritask
- [Tritask ウェブサイト](https://tritask.github.io/tritask-web/)
  - Tritask のホームページです
  - コンセプトから導入方法まで全般知識を一通り扱っています
- [Tritask フォーマット](trita_format.md)
  - Tritask 仕様のうち、ファイルフォーマットについて記したものです
  - 実装を開発したい方向けです

## 実装としての Tritask
- [tritask-sta](https://github.com/tritask/tritask-sta)
  - @stakiran による実装です
  - 秀丸エディタと Python に依存しています
  - 最新のソースやドキュメントは[ダウンロードページ](https://tritask.github.io/tritask-sta-bin/)が確実です
    - [tritask-sta](https://github.com/tritask/tritask-sta)は更新が遅れることがあります
      - ソースのマスターがここではない（作者のプライベートリポジトリ）ためです
      - プライベートリポジトリでガシガシ開発し、きりの良いところで上記にリリースしています
- [tritask-vscode](https://github.com/tritask/tritask-vscode)
  - @stakiran による実装です
  - Visual Studio Code と Python に依存しています
