# thumbnail-assist

簡単なサムネ生成アシストツールです。
このアシストツールには以下の機能があります：
* **WIP:** `カラーアナライザー`： 指定されたフォルダにあるイラストファイルを分析し、直近で一番使用されていない色を検出します。
* **WIP:** `アセットマネージャー`： 指定されたフォルダに置いてあるイラストファイルを色順に表示し、特定の色のイラストを探しやすくします

## ビルド方法

ビルドするにはまず以下のツールをインストールしてください：
- [`node.js`](https://nodejs.org/en)
- [`rust`](https://www.rust-lang.org/ja/tools/install)
- [`tauri`](https://tauri.app/v1/guides/getting-started/prerequisites)

インストール後、`cargo tauri build`を行えば`src-tauri/target/release`のフォルダにビルドされたファイルが生成されます