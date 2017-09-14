# IT Fundamentals

## 概要
- ITに関する基本的な知識やスキル

## 日程
- 毎週、水、木曜日(9月中)
- 試験日 9/29(金)<予定>

### ５大装置
- 入力装置
- 記憶装置 => 主記憶装置(メインメモリ)、補助記憶装置
- 制御装置、演算装置 => CPU
- 出力装置

### クライアントとサーバ
- クライアント => サービスの提供を受ける
- サーバ => サービスを提供する
  - メールサーバー
  - Webサーバー
  - ファイルサーバー
  - プリントサーバー

### 大きさによる分類
- ラックマウントPC => ラック(棚)に格納するために平らな構造になっている。

### ソフトウェア
- アプリケーション
- システムソフトウェア(OS)
 - ミドルウェア(データベース、ネットワーク)
 - OS
 - デバイスドライバー

### マザーボード
 - バス => マザーボードに接続された各装置(部品)の間をつなぎ、信号をやり取りするための伝送路(バススピード)
 - BIOS(Basic Input Output System)(チップセット)
  => コンピュータの基本的な動作を制御するためのプログラム
  - フォームファクター => マザーボードの規格

### 電源ユニット(PSU: Power Supply Unit)
- 各種電源コネクタ
  - 周辺機器とコンピュータの接続
    - 周辺機器には、接続インタフェースによって、コンピュータの電源を入れる前に
    接続しなければコンピュータに認識されないものもあります。
    - ホットスワップ

### CPU => 演算装置/制御装置/内部レジスタ

#### 性能
- クロック周波数 => １秒あたりの同期の回数(Hz)
    - 1000 => 1k
    - 1000k => 1M(メガ)
    - 1000M => 1G(ギガ)
    - 1000G => 1T(テラ)
    - 0.001 => 1m
    - 0.001m => 1μ(マイクロ)
    - 0.001μ => 1n(ナノ)
    - 0.001n =>1p(ピコ)
- コア数 => 演算や制御を実行するための「中核」の回路の数
  - マルチコアプロセッサ/シングルコアプロセッサ
- 32/64bit => プロセッサが一度に扱える情報量
- CPUキャッシュ => CPUとメインメモリの間のバッファをおこなう高速なメモリ
- ディスクキャッシュ => メインメモリとハードディスクの間のバッファを行うメモリエリア

#### プロセッサの種類
  - Intel社、AMD社などの複数のベンダーから提供

### GPU(Graphics Processing Unit)
  - 画像処理を行う半導体チップ、CPUの負荷を軽減
  - 3Dゲームや3Dグラフィックデザインなどで使用するコンピュータ

#### VRAM
  - VRAMに書き込んだデータがディスプレイに表示される

### 冷却装置
- 熱暴走を防ぐために仕組み
- ヒーシンク => プロセッサに取り付ける放熱板

### メモリの種類
  - ROM => 不揮発性 => 電気の供給がなくてもデータを保持する
  - RAM => 揮発性 => 電気の供給がないとデータが消えてしまう
    - SRAM => 高速/高価、キャッシュメモリ、リフレッシュの必要がない
    - DRAM => 低速/比較的安価、メインメモリ、リフレッシュ必要

### メモリモジュール
- デスクトップPC => DIMM
- ノート型PC => S.O.DIMM
- 切り欠き => メモリモジュールを間違った方向に指すのを防ぐ

### メモリの性能
- SDRAM -> DDR SDRAM -> DDR2 SDRAM -> DDR3 SDRAM
- 種類の異なるDRAMには互換性がなく、マザーボードのメモリスロットの形状を確認
- 増設時、現在刺さっているモジュールと同一規格、同一メーカーのものを使用する

### ハードディスク vs SSD(ソリッドステートドライブ)

#### ハードディスクの問題点
- 衝撃や落下に弱い
- 消費電力が大きく、低電力化が難しい
- 振動が発生し、音がうるさい
- 読み書きの高速化が難しい

#### SSDの問題点
- ハードディスクの問題点は解決するが高価

### ハードディスクの種類
- 接続方法 => 内蔵、外付け

### 接続インターフェース
- 一般のPCのハードディスク : IDE(P(パラレル)ATA) => S(シリアル)ATA
- データセンタ: SCSI => SAS、デイジーチェーン

### 性能
- rpm => １分間の回転数
- シークタイム  => 磁気ヘッド部分とアームの移動時間
- データ転送速度
- キャッシュ(ディスクキャッシュ)
- 容量

### 拡張カード
- PCI/ PCI-Express => 汎用
- AGP => グラフィック専用
- プラグ&プレイ => Windowsにおいて、周辺機器を接続した際に、自動的にその機器を認識させる仕様。

### 拡張カードの種類
- ビデオカード
- オーディオカード
- ネットワークカード(LANカード、NIC)
- モデム

## 周辺機器

### 入力装置
- キーボード
    - テンキー => 数字を入力する専用のキー
- ポインティングデバイス
    - マウス
        - メカニカルマウス => ボールの回転でマウスポインタを移動
        - 光学式マウス => 光の反射で検知
    - トラックボール => メカニカルマウスを裏返したような構造
    - ジョイスティック => レバーによる方向入力を行う
    - タッチパッド
    - スライラスペン => タッチパネルに押し当てて使う棒状の筆記具
- スキャナー => 書籍や写真などを光学的に読み取り、デジタルデータに変換する
    - dpi(dot per inch) => 大きいほど精細な取り込み
- マイク
- Webカメラ => 撮影された画像や動画をインターネット経由で配信するために使用する
### 出力装置
- ディスプレイデバイス
    - CRT => ブラウン管を使用したデイスプレイ
    - 液晶ディスプレイ => 消費電力が少ない、フラット
    - プロジェクタ => スクリーンへ投影
    - 設定
        - 明度 => 画面全体の明るさ
        - コントラスト => 明るい部分と暗い部分の差を調整
        - 解像度
            - 画像を構成する一つ一つの点のこまかさ
            - 800 x 600、1024 x 768、1152 x 864、1280 x 1024 のように
            縦と横のドット数で表す
            - 解像度が低い(ドット数が少ない) => 画像や文字のギザギザが目立つ
        - 画面の上下や左右のサイズと位置
- プリンター
    - インクジェットプリンター => 用紙にインクを吹き付けて印字
    - サーマルプリンター => ヘッド部分が発熱し、感熱紙に印刷
    - ターミナルプリンター => 軽量な携帯プリンター
    - レーザープリンター => コピー機と同様な原理、トナーを熱処理で用紙に定着、高速な印字、オフィスの共有プリンター
- スピーカー => 20Hz〜18kHz
### 入出力装置
- FAX => 通信回線を通して画像情報を遠隔地へ伝送する装置
- 複合機 => スキャナー + プリンタ=> コピー
- 外部ストレージ
    - 外部ハードデイスク => コンピューターのバックアップやテレビの録画の保存など、大容量のデータ保存に用いられる
    -CD/DVD/Blu-ray(BD)
        - xx-ROM/xx-R/xx-RW(RE)
            - xx-ROM => 読み取り専用
            - xx-R => 1回だけ書き込みができる
            - xx-RW(RE) => データの書き換え
        - 容量
            - CD => 650MB,700MB => 音声データ
            - DVD => 4.7GB,8.5GB => 動画データ
            - BD => 25GB,50 => 高画質が動画データ
    - フラッシュメモリ
        - USBメモリ
        - メモリスティック
        - SDメモリカード(SD, miniSD, MicroSD)
        - マルチカードリーダー
    - ネットワークアタッチドストレージ(NAS) => ネットワークに接続して使用するファイルサーバ専用機(ネットワーク上でファイルを共有できるハードディスク)
    - モバイルメディアプレイヤー
    - スマートフォン
    - タッチスクリーン

### 接続インタフェース

#### 映像伝送用
- VGA => アナログで映像を出力、15ピン
- DVI 、DisplayPort => デジタルで映像を出力、主にmacで使用
- HDMI => デジタルで映像と音声を高品質に伝送する
- S-Video => アナログテレビやビデオテープレコーダなどで用いられるアナログ信号のインタフェース
- Component-RGB => DVDレコーダーと古いテレビなどを接続するのに利用

#### キーボード/マウス接続インターフェース
- PS/2 => キーボードやマウスを接続する専用のインターフェース、色分けで、キーボードとマウスの挿し間違いを防ぐ
- USB => 周辺機器を接続する汎用的なインタフェース
- 無線接続 => Bluetooth

#### プリンター接続インターフェース
- RS-232C(シリアル)
- IEEE-1284(パラレル) => セントロニクス
- IEEE-1394/FireWire or USB

### ネットワーク接続インターフェース
- イーサネット => RJ-45
- IEEEE 802.11a/b/g/n... => 2.4/5GHz

### モデムとの接続インターフェース
- 電話線との接続 => RJ-11

### 外部ハードディスク接続インタフェース
- eSATA => Excternal SATA => 従来の内部用を外部用にした
- Thumderbolt => USBより多機能、高性能

- オーディオ => ミニジャック(ミニプラグ)
- 電源コネクタ => AC(交流) -> DC(直流)

## ソフトウェアの種類
- OS => 基本ソフトウェア、必須、コンピュータのハードウェアを管理
- アプリケーション => 応用ソフトウェア、利用目的に応じた機能
- ミドルウエア => OSとアプリケーションの仲介、データベース、ネットワーク
- デバイスドライバ => 周辺機器の制御を行うソフトウェア

### オープンソースソフトウェア
- ソースコードが公開、それの改変、再配布が可能

### OSの役割
- プロセス管理 => 実行中のプログラムの管理
- メモリ管理 => メモリを効率的に使用する
- ファイル管理 => ディレクトリ、ファイル
- 周辺機器管理 => デバイスドライバ
- ネットワーク => PCをネットワークに接続できる
- ユーザインタフェースの機能 => シェル(cui)
- シングルユーザとマルチユーザ
    - シングルユーザ => 1台のコンピュータを1人のユーザのみが使用する
    - マルチユーザシステム => 1台のコンピュータを複数のユーザで共有することを前提、各ユーザが各自の環境を持てる
- CUIとGUI
    - CUI(Character-based User Inteface) => コンソール画面で、コマンドを入力し操作
    - GUI(Graphical Usesr Interface) => マウスを使用し、アイコン、メニューを操作
- マルチプロセッサ => 複数のCPUを搭載するシステム
- 32ビット、64ビット
    - 32ビット=> 4GBを超えるメモリを扱うことができない

### OSの種類
- PC
    - Windows => Microsoft社が開発、販売している
    - Unix => AT&Tベル研究所で開発、ソースコードが公開されていて、研究機関や企業で広く利用。C言語で書かれているために移植性が高い
    - Linux => Unixの派生OSの1つ、Linus氏によって開発されオープンソースOS。
    - Mac OS => AppleのMacintosh専用のOS、Unix技術を採用したMac OS X(マックオーエステン)
    - Chrome OS => Chrominus OS(オープンソース)をもとに開発、Webの閲覧とWebアプリケーションの動作に適したOS
- モバイル
    - Apple iOS => Appleが開発した、iPhone、iPad、iPod touchに搭載されている
    - Andrid => GoogleがLinuxベースに開発、スマートフォンで広く採用
    - Windows Phone => Microsoft社が開発
    - BlackBerry => BlackBerry社

### アプリケーションの種類
- リモートデスクトップソフトウェア => コンピュータから別のコンピュータにアクセスし、遠隔操作を行うソフト。
- VoIP(Voice over IP)ソフトウェア => IP電話(ネットワーク上で音声通話する)で使用する
- 特定の用途向けソフトウェア => 業種や業務に特化したもの
- プラットフォーム => デスクトップ(Windows/Mac)、モバイルデバイス(iPhone/Android)、Webベース

## OSの設定
- デスクトップ
- スタート画面
- タスクバー
    - スタートボタン
    - クイック起動ツールバー
    - 通知領域
- スタートメニュー
- 時計の設定
- 言語の設定
- 画面の解像度 => 解像度(デジタル画像を構成する1つ1つの点の細かさ)を調整
- 音声の設定
- 電源の設定 => 省電力(パワーセーブ)に関する設定
    - スリープモード => 作業中のコンピュータの状態をメモリに保存した上で、コンピュータを一時停止し消費電力を抑える機能
- ユーザアカウントの設定
    - 標準ユーザー => コンピュータを利用する一般のアカウント
    - 管理者 => アプリケーションのインストール/アンインストール
    - Guest => 特定のアカウントを持たず、コンピュータに一時的にアクセするユーザのためのもの
- ユーザ補助オプション => 拡大鏡、テキスト読み上げ、スクリーンキーボード
- スクリーンキャプチャー => ディスプレイに表示されている画像イメージをコピーする機能

## OSのツール
- デバイスマネージャー => デバイスドライバーソフトの管理
    - Pnp(Plug and Play) => OSが追加したデバイスを認識して、自動で設定を行う
- パフォーマンスモニター => CPU、ディスク、ネットワーク、メモリの動作状況をグラフで表示
- ディスクの管理 => ハードディスクのフォーマット、パーティションの作成や削除、サイズ変更
    - フォーマット => ハードディスクはフォーマットしなければデータが保存できない
        - FAT
        - FAT32
        - NTFS
    - パーティション
- イベントビューアー => エラーログを確認するためのもの
    - アプリケーション
    - セキュリティ
    - セットアップ
    - システム
    - 転送されたイベント

## ファイルやフォルダーの管理
### ファイル
- 文書
    - txt => テキストファイル、文字データのみ
    - rtf => Microsoft社、txtに書式情報を埋め込む
    - doc/docx => word
    - xls/xlsx => excel
    - ppt/pptx => powerpoint
    - pdf => Adobe によって開発された、電子文書のためのファイル形式。
- 音声
    - mp3 => 圧縮された音声ファイル形式
    - wav => windows独自の音声ファイル
    - acc => appleのituneで採用
- 画像
    - jpg => 写真
    - gif => 画像、アニメーション
    - tiff
    - png => gif後継、画像
    - bmp





#### GUI
#### CUI