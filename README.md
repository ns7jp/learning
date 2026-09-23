# learning — 未経験からのサーバー構築エンジニア学習教材

未経験からサーバー構築エンジニアを目指す人のための、やさしい解説・24 週の学習プラン・演習キット・用語集・コマンド集です。
作者（[島田則幸 / ns7jp](https://github.com/ns7jp)）が自分の学習のために作り、同じ立場の人がそのまま使える形にまとめています。

> これらは学習用の教材と演習の設計です。作者の実務経験や、教材の全範囲を実施した実績を示すものではありません。
> 作者が実際に行った記録は、主作品 [server の検証証跡台帳](https://github.com/ns7jp/server/blob/main/docs/evidence/README.md)にあります。

## 最初に開くページ

| いまの状態 | 開くページ |
| --- | --- |
| サーバーの用語や構成図に初めて触れる | [やさしい用語・見方ガイド](docs/beginner-guide.md) |
| これから学習環境を準備する | [開始前診断と最初の 30 分](docs/learning-plan/00-start-here.md) |
| 24 週の計画を立てたい | [学習プラン（24 週）](docs/learning-plan/README.md) |
| 手を動かす演習を選びたい | [学習プランの演習設計とキット](docs/learning-plan/README.md) |

## 収録内容

| 分類 | ファイル | 内容 |
| --- | --- | --- |
| 入門 | [docs/beginner-guide.md](docs/beginner-guide.md) | 主作品 `server` の構成図を読むための用語と見方 |
| 学習プラン | [docs/learning-plan/](docs/learning-plan/README.md) | 24 週のカリキュラム、環境準備、Phase 1〜13 の演習設計と実施キット（Hyper-V・Bash・PowerShell・Python・AD・AWS など） |
| 用語集 | [docs/it-glossary.md](docs/it-glossary.md) | IT 基礎用語（20 分野） |
| コマンド集 | [docs/linux-commands.md](docs/linux-commands.md)・[docs/windows-commands.md](docs/windows-commands.md) | Linux / Windows の運用コマンド |
| 演習スクリプト | [scripts/rehearse-linux-web.py](scripts/rehearse-linux-web.py) | Linux Web の変更と復元を使い捨て環境で試すリハーサル |

学習の記録や教材の不具合は、[Issue テンプレート](.github/ISSUE_TEMPLATE/)から送れます。

## 関連リポジトリ

- [ns7jp/ns7jp](https://github.com/ns7jp/ns7jp)：作者のプロフィールと経歴
- [ns7jp/server](https://github.com/ns7jp/server)：主作品（Linux / Windows Server の構築・監視の学習ラボ）

## この教材の来歴

2026-09-23 に、[ns7jp/ns7jp](https://github.com/ns7jp/ns7jp) の `docs/` 配下からこのリポジトリへ移しました。移動前の変更履歴は ns7jp/ns7jp のコミット履歴に残っています。移動に合わせて、他のリポジトリにある文書へのリンクは絶対 URL に張り替えています。作者が非公開で運用している育成システムへの参照は、リンクを外して文中で説明しています。

## License

[MIT License](LICENSE)
