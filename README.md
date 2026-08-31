# gene_solist_ai_gui_app

株式会社ピーバンドットコムが提供する [Solist-AI™ × gene｜ノーコード組み込みAI開発キット](https://www.p-ban.com/services/gene/solist-ai.html) 用の GUI アプリケーション。

gene (ESP32-S3) と UART で通信し、Solist-AI (ML63Q2537) の ML 処理を操作する。

アプリケーションは**バイナリ配布物**として提供する。ソースコードは非公開。

## 入手

[Releases](https://github.com/pban-rd-dev/gene_solist_ai_gui_app/releases) から、環境に合ったアーカイブをダウンロードする。

| プラットフォーム | ファイル |
| --- | --- |
| Linux x64 | `gene_solist_ai_gui-<version>-linux-x64.tar.gz` |
| Windows x64 | `gene_solist_ai_gui-<version>-windows-x64.zip` |

GitHub が自動生成する Source code (zip / tar.gz) にはアプリケーションが含まれない。上記のアーカイブを使うこと。

## 実行

Linux:

```bash
tar xzf gene_solist_ai_gui-<version>-linux-x64.tar.gz
cd gene_solist_ai_gui
./gene_solist_ai_gui
```

Windows: zip を展開し、`gene_solist_ai_gui.exe` を実行する。

## 接続

開発キットの gene (ESP32-S3) を USB で PC に接続する。シリアルポートはアプリケーション側で選択する。

## ライセンス

本リポジトリの内容は Solist-AI™ × gene｜ノーコード組み込みAI開発キット の購入者による、同キットの操作および評価に限り使用を許可する。詳細は [`LICENSE.ja`](LICENSE.ja)（日本語 / 正本）または [`LICENSE`](LICENSE)（English）を参照。

同梱されている第三者コンポーネントは [`NOTICE`](NOTICE) および配布物内の `THIRD-PARTY-LICENSES.md` を参照。

Copyright © 株式会社ピーバンドットコム. All rights reserved.
