# crates-category-slugs.ja
Cargo.tomlに書ける有効なカテゴリーと説明の日本語訳一覧

---

### accessibility
支障を克服して、できるだけ多くの人がソフトウェアを利用できるようにするための支援技術。

### aerospace
航空（大気内）および宇宙航行（外宇宙）に関するクレート。

### aerospace::drones
マルチコプター、固定翼、VTOL（垂直離着陸機）、飛行船/気球に関連するクレート。

### aerospace::protocols
航空宇宙におけるプロトコルの実装に関するクレート。

### aerospace::simulation
流体、空気力学など、航空宇宙で使用されるあらゆる種類のシミュレーションに関連するクレート。

### aerospace::space-protocols
CCSDSなど、宇宙での使用に関するプロトコル実装。

### aerospace::unmanned-aerial-vehicles
マルチコプター、固定翼、VTOL（垂直離着陸機）、飛行船/気球、ローバー、ボート、潜水艦など、無人航空機に関連するクレート。

### algorithms
ハッシュ、ソート、検索などのコアアルゴリズムのRust実装。

### api-bindings
特定のAPIへの便利なアクセスを提供するための慣用的なラッパー。HTTP APIのラッパーも含む。非慣用的または安全でないバインディングは、外部FFIバインディングに含まれる。

### asynchronous
未来、約束、待機、イベントなどの技術を使用して、メインプログラムのフローとは独立してイベントを処理するためのクレート。

### authentication
身元確認のプロセスを支援するクレート。

### caching
前の計算結果を保存し、その結果を再利用するためのクレート。

### command-line-interface
コマンドラインインターフェースを作成するためのクレート。引数パーサー、行編集、出力の色付けやフォーマットなど。

### command-line-utilities
コマンドラインで実行するアプリケーション。

### compilers
コンパイラの実装、インタープリタ、トランスパイラを含む。

### compression
データを小さくするためのアルゴリズム。

### computer-vision
ビデオや画像から世界を理解するためのクレート。

### concurrency
並行および並列計算を実装するためのクレート。

### config
アプリケーションの設定管理を支援するクレート。

### cryptography
データを保護するためのアルゴリズム。

### cryptography::cryptocurrencies
デジタル通貨、ウォレット、分散型台帳に関するクレート。

### data-structures
特定の目的に適したデータを整理するためのRust実装。

### database
データベース管理システムとインターフェースするためのクレート。

### database-implementations
クライアントが大量のデータを効率的に保存および照会できるようにするデータベース管理システムのRust実装。

### date-and-time
四次元の扱いに伴う複雑さを管理するためのクレート。

### development-tools
テスト、デバッグ、リンティング、パフォーマンスプロファイリング、自動補完、フォーマットなど、開発者向けの機能を提供するクレート。

### development-tools::build-utils
ビルドスクリプトやその他のビルド時ステップのためのユーティリティ。

### development-tools::cargo-plugins
Cargoの機能を拡張するサブコマンド。

### development-tools::debugging
ログ、トレース、アサーションなど、コードの状況を把握するためのクレート。

### development-tools::ffi
他の言語とインターフェースをより良くするためのクレート。バインディングジェネレータや便利な言語構造を含む。

### development-tools::procedural-macro-helpers
Rustで手続きマクロを書くのを支援するクレート。

### development-tools::profiling
コードのパフォーマンスを把握するためのクレート。

### development-tools::testing
コードの正確性を検証するのを支援するクレート。

### email
メールの送受信、フォーマット、解析を支援するクレート。

### embedded
組み込みデバイスまたはオペレーティングシステムなしで主に使用されるクレート。

### emulators
あるコンピュータが他のコンピュータのように振る舞うことを可能にするエミュレータ。ビデオゲームシステムが一般的にエミュレートされる。

### encoding
データをあるデータ形式から別のデータ形式にエンコードおよびデコードする。

### external-ffi-bindings
他の言語で書かれたライブラリへの直接的なRust FFIバインディング。通常は-sys接尾辞で示される。安全で慣用的なラッパーはAPIバインディングカテゴリに含まれる。

### filesystem
ファイルおよびファイルシステムを扱うクレート。

### finance
会計、取引、投資、税金、銀行、政府支援の通貨を使用した支払い処理に関するクレート。

### game-development
ゲーム開発の一部を加速することに焦点を当てたクレート。

### game-engines
ゲーム開発のすべてのニーズに対応する「ワンストップショップ」を提供しようとするクレート。

### games
楽しみとエンターテイメントのためのアプリケーション。Rustプログラミング言語で実装されたRustというビデオゲームはこのカテゴリに含まれる。ビデオゲームを作成するためのライブラリはGame enginesカテゴリに含まれる。

### graphics
グラフィックライブラリおよびアプリケーションに関するクレート。幾何学、曲線、色などのラスタおよびベクタグラフィックスプリミティブを含む。

### gui
グラフィカルユーザーインターフェースを作成するのを支援するクレート。

### hardware-support
特定のCPUやその他のハードウェア機能とインターフェースするためのクレート。

### internationalization
様々な言語や地域に適応可能なソフトウェアを開発するのを支援するクレート。

### localization
国際化されたソフトウェアを特定の言語や地域に適応させるのを支援するクレート。

### mathematics
数学的な側面を持つクレート。

### memory-management
メモリアロケーション、メモリマッピング、ガベージコレクション、参照カウント、または外部メモリマネージャへのインターフェースを支援するクレート。

### multimedia
音声、ビデオ、画像の処理またはレンダリングエンジンを提供するクレート。

### multimedia::audio
音声の録音、出力、処理に関するクレート。

### multimedia::encoding
マルチメディア形式でバイナリデータをエンコードまたはデコードするクレート。

### multimedia::images
画像を処理または作成するクレート。

### multimedia::video
ビデオの録画、出力、処理に関するクレート。

### network-programming
FTP、HTTP、SSHなどの高レベルネットワークプロトコルや、TCP、UDPなどの低レベルネットワークプロトコルを扱うクレート。

### no-std
Rust標準ライブラリなしで機能するクレート。

### no-std::no-alloc
Rustのallocクレートなしで機能するクレート。

### os
オペレーティングシステム固有のAPIへのバインディング。

### os::android-apis
Android固有のAPIへのバインディング。

### os::freebsd-apis
FreeBSD固有のAPIへのバインディング。

### os::linux-apis
Linux固有のAPIへのバインディング。

### os::macos-apis
macOS固有のAPIへのバインディング。

### os::unix-apis
Unix固有のAPIへのバインディング。

### os::windows-apis
Windows固有のAPIへのバインディング。

### parser-implementations
特定の形式や言語のために実装されたパーサー。

### parsing
バイナリおよびテキスト形式のパーサーを作成するのを支援するクレート。形式固有のパーサーは他の、より具体的なカテゴリに含まれる。

### rendering
通常はグラフィックカードの助けを借りて、2Dまたは3Dグラフィックスをリアルタイムまたはオフラインでレンダリングする。

### rendering::data-formats
3Dモデルやアニメーションシートなど、2Dまたは3Dレンダリングに関連するデータ形式の読み込みと解析。

### rendering::engine
画面にレンダリングするための高レベルのソリューション。

### rendering::graphics-api
ハードウェアまたはオペレーティングシステムのレンダリング機能に直接アクセスするクレート。

### rust-patterns
Rustのプログラミングに特有の状況に対する共通のソリューション。

### science
物理学、化学、生物学、機械学習、地球科学などの科学分野に関連する問題を解決するためのクレート。

### science::bioinformatics
大規模な生物学的データを処理するクレート。

### science::bioinformatics::genomics
配列、豊富性、変異、および解析を含む遺伝データを処理するクレート。

### science::bioinformatics::proteomics
配列、豊富性、および解析を含むタンパク質データを処理するクレート。

### science::bioinformatics::sequence-analysis
アライメント、アセンブリ、および注釈を含む生物学的配列を処理するクレート。

### science::geo
空間情報、地図、ナビゲーションデータ、および地理情報システムの処理。

### science::neuroscience
脳および神経系に関連するデータの研究ツールおよび処理。

### science::robotics
ロボティクスに関連するクレート。

### simulation
ネットワークプロトコルをシミュレートするなど、ある活動をモデル化または構築するために使用されるクレート。

### template-engine
テンプレートとデータを組み合わせて結果ドキュメントを生成するために設計されたクレート。通常はテキスト処理を重視する。

### text-editors
テキストを編集するためのアプリケーション。

### text-processing
テキスト形式で表現される人間の言語の複雑さを処理するためのクレート。

### value-formatting
アプリケーションがユーザーに表示する値をフォーマットするためのクレート。表示を様々な言語や地域に適応させる可能性がある。

### virtualization
あらゆる形式の仮想環境およびリソースの作成と管理を行うためのクレート。コンテナ化システムを含む。

### visualization
データを視覚化するための方法。プロットやグラフ化など。

### wasm
WebAssemblyをターゲットとする場合やWebAssemblyを操作するためのクレート。

### web-programming
ウェブアプリケーションを作成するためのクレート。

### web-programming::http-client
HTTPネットワークリクエストを行うためのクレート。

### web-programming::http-server
HTTP経由でデータを提供するためのクレート。

### web-programming::websocket
WebSocketプロトコルを使用して通信するためのクレート。
