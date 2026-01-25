#######################################################
時雨堂 不定期オンライン雑談配信 (SHIGURADIO)
#######################################################

:日時: どこかの火曜日 15:00 ~ から
:場所: Discord https://discord.gg/shiguredo

.. image:: https://i.gyazo.com/0a6b81c59054c9a2d1918df5b6da110d.jpg

この絵は @sassembla が書いてくれました。

概要
====

時雨堂の WebRTC 関する Discord 上で開催するオンライン雑談イベントです。

参加者は一方向での雑談配信を視聴するという形です。そのためカメラやマイクは不要です。
質問はすべて Discord にコメントを書いて頂く形を取ります。

Discord サーバーブースト
========================

Discord で Sora Lab / Sora SDK の Discord サーバへサーバブーストをしてくれているユーザは申請なしで全てのイベントに参加可能です。
また、イベントの過去ログを見ることができるようになります。締め切りを過ぎたイベントでも参加が可能です。

`サーバーブースト 💨 - Discord <https://support.discord.com/hc/ja/articles/360028038352>`_

2026 年 2 月 17 日 (火) のイベントへの参加申込方法
=====================================================

まず ``時雨堂コミュニティ`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/shiguredo

電話番号認証と **アイコンの設定** をお願いします。

``時雨堂コミュニュティ`` サーバの ``#event`` チャンネルの、
イベントの投稿に **参加します** とメッセージを残してください。

アイコンが設定済みであれば、 
ロールが管理者のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2026-02-17`` というロールが付与されます。

注意
----

- 雑談なので話は発散します
- 開始時間に 1 人でも集まればやります
- 競合他社の参加は禁止します
- 撮影や配信、録画、録音などは全て禁止します
- SNS への共有などは禁止します
- このセミナーは開発者向けです
- 申込は開始後 30 分までとします
- 視聴用 URL は当日の開始 15 分前に共有します
- 当日の 5 分前からテストも込めて配信を開始します

キャンセル
==========

報告は不要です。

途中退場
===========

自由です。

配信について
============

- Sora Labo を利用して、画面共有と音声を配信します
- 質問は Discord に書いてください、見ながら話します

事前準備
========

- Chrome または Safari の最新版が必須です
- WebRTC の基本的な話などは一切しません

開催
====

2026 年 2 月 17 日 15:00-17:00
---------------------------------------

今回から 15:00 スタート 17:00 終了の 120 分です。

時雨堂のライブ配信ツール Misora を利用して配信します。

- Rust

  - shiguredo/http11-rs
  - shiguredo/websocket-rs
  - shiguredo/rtmp-rs
  - shiguredo/srt-rs
  - shiguredo/rtsp-rs
  
    - 開発中
  - shiguredo/moqt-rs

    - 開発中
- Sora Rust SDK

  - libwebrtc-c
  - WHIP / WHEP も対応予定
  - 開発中
- WebRTC SFU Sora

  - Sora 2025.2.x について
  - Sora 2026.1.x について
- Toki (仮)

  - Sora 専用のリバースプロキシ
  - nginx を置き換える TLS Proxy
  - UI
  - クローズドソース
  - 既に検証サーバーで動作確認中
- Kogane (仮)

  - Sora 専用のログ解析ソリューション
  - ログ転送エージェント
    - QUIC
    - OpenMetrics
  - ログ保存と解析サーバー
    - DuckLake
    - QUIC
    - SQLite
    - 組み込みオブジェクトストレージ

      - 外部も利用可能
    - OpenMetrics
    - UI
  - クローズドソース
- Media Pipeline Tool Hisui

  - Sora の録画合成ツールからマルチプロトコル対応のメディアパイプラインツールへ
  - WebRTC / WebSocket / WebTransport を利用してブラウザでリアルタイムな編集
  - Sora Rust SDK 入出力対応
  - RTMP 入出力対応
  - SRT 入出力対応
  - RTSP 入出力対応
  - MOQT 入出力対応
  - JSON-RPC 2.0 を利用したフックポイント
  - Hisui UI
  - オープンソース
- QUIC

  - Media over QUIC Transport (MOQT)

    - Erlang/OTP

      - フルスクラッチの QUIC / HTTP/3 / WebTransport 実装
      - MOQT 対応
      - Sora 搭載
      - クローズドソース
    - TypeScript によるクライアント実装
    
      - https://github.com/shiguredo/moqt-js
      - draft-16 対応中
      - 依存 0
    - Python (C/C++) によるクライアント/サーバー/リレー実装
    
      - msquic + nghttp3 を利用した MOQT 実装

        - msquic は IO 周りが優秀なので採用
      - クローズドソース
    - Rust によるクライアント/サーバー実装
    
      - Cloudflare Quiche を利用した MOQT 実装
    - iOS/Android 向けにも提供したい
  - マルチパス QUIC

    - Erlang/OTP には実装済み
    - ngtcp2 利用で Python 経由で利用
- Python

  - Python で WebCodecs API が利用できる webcodecs-py の提供

    - https://github.com/shiguredo/webcodecs-py
  - Python で生データ (NV12 や I420) を再生できるプレイヤー

    - https://github.com/shiguredo/raw-player
  - https://github.com/shiguredo/uvc-py
  - https://github.com/shiguredo/portaudio-py
  - https://github.com/shiguredo/blend2d-py
  - https://github.com/shiguredo/libdatachannel-py
  - https://github.com/shiguredo/mp4-py
- Misora

  - Sora Labo / Sora Cloud で利用できる会議サービス
  - クローズドソース
- Mikan

  - md/mdx を利用した日本語全文検索組み込みドキュメントツール
  - オフライン日本語全文検索エンジン搭載
  - クローズドソース


過去
================

2025 年 7 月 8 日 15:00-17:00
---------------------------------------

今回から 15:00 スタート 17:00 終了の 120 分です。

開発中の Misora を利用して配信します。

- 雑談

  - WebRTC

    - Chrome で WebRTC H.265
    - Safari で WebRTC AV1
    - https://www.daily.co/blog/how-lemon-slice-builds-ai-characters-with-pipecat-and-daily/
    - https://github.com/coturn/coturn/releases/tag/4.7.0
  - MOQT

    - https://quic.video/blog/application-first
    - https://github.com/shiguredo-webrtc-build/libmoqt-build
  - OBS

    - https://github.com/obsproject/obs-studio/pull/10885
- WebRTC SFU Sora

  - Sora 2025.1.x の新機能について

    - https://blog.shiguredo.jp/webrtc-sfu-sora-2025-1-0-release-notes/
    - Plumtree を利用した複数ノードでのスケールアウト
    - H.265 パラメーター指定
    - セッションのグルーピング
    - セッション単位での最大同時接続数制限
    - セッション単位でのクライアント ID 重複時の既存接続の追い出し
    - 帯域推定
    - シグナリング通知 network.status に帯域推定を追加
    - メディア配信ワーカー自動スケール
    - WHIP/WHEP RFC 追従
  - 今後の Sora の新機能と戦略

    - RPC 機能
      
      - JSON-RPC 2.0 over DataChannel による Sora API の実行
    - サイマルキャスト rid: auto
    - サイマルキャスト rid: none
    - DTLS 1.3 対応
    - WHIP サイマルキャスト
    - 帯域推定改善
    - マルチコーデックサイマルキャスト

      - 録画
- Sora Cloud

  - DuckDB を利用したログ解析
  - 監視周り強化
  - Hisui Cloud
  - Suzu Cloud
- Misora

  - Claude Code で作成しているミーティング＆ライブツール
  - 静的サイトなのでデプロイが簡単
  - DuckDB-Wasm (OPFS) を利用した統計情報
- Sora JavaScript SDK

  - RPC 機能
  - ステレオ関連
- Sora C++ SDK

  - 積極的な改善
- Sora Python SDK

  - 積極的な改善
- Sora iOS/Android SDK

  - ステレオ関連
  - CA 証明書の指定
  - 開発ツール
- Unity SDK

  - Apple Vision Pro 向けビルド追加調査
- Sora ESP32 SDK

  - https://github.com/espressif/esp-webrtc-solution

    - https://github.com/espressif/esp-webrtc-solution/issues/5
    - https://github.com/espressif/esp-webrtc-solution/issues/43
- Kohaku

  - DuckDB 版のリリース
- Hisui

  - Rust 版の正式リリース
  - 録画ファイル解析ツール
  - 録画ファイル画質チェックツール
  - NETINT ハードウェアアクセラレーターに対応
- Zakuro

  - 統計情報の改善
  - H.265 対応
  - NETINT ハードウェアアクセラレーターに対応
- Momo

  - 最新の libwebrtc へ追従
  - コード改善
  - MOQT 対応版の準備
- Media Processors

  - @shiguredo/rnnoise-wasm

    - 最新の RNNoise にアップデート
- libdatachannel-py

  - Opus / AV1 / H.264 / H.265 対応


2024 年 7 月 9 日 15:00-17:00
---------------------------------------

今回から 15:00 スタート 17:00 終了の 120 分です。

- 雑談

  - WebRTC

    - `Debugging with about:webrtc in Firefox, Getting Data Out - Advancing WebRTC <https://blog.mozilla.org/webrtc/debugging-with-aboutwebrtc-in-firefox-getting-data-out/>`_
    - `How WebRTC speaker selection works - Advancing WebRTC <https://blog.mozilla.org/webrtc/how-webrtc-speaker-selection-works/>`_
    - `WebRTC & HEVC - how can you get these two to work together • BlogGeek.me <https://bloggeek.me/webrtc-hevc-work-together/>`_
  - QUIC

    - `Never* use Datagrams - Media over QUIC <https://quic.video/blog/never-use-datagrams/>`_
    - `draft-kazuho-quic-quic-on-streams-00 <https://datatracker.ietf.org/doc/html/draft-kazuho-quic-quic-on-streams-00>`_
  - WebTransport
  - Media over QUIC Transport
- WebRTC SFU Sora

  - Sora 2024.1.x の新機能について

    - なぜ Raft を採用し、分散システム化したのか
    - クラスターリレー機能
    - クラスターリレーアフィニティ機能
    - クラスターテンポラリーノード機能
    - クラスター合計接続数維持機能
    - OBS WHIP / WHEP

      - HEVC
      - TURN-UDP
    - 統計ウェブフック
    - RTC 統計
    - ライフタイム機能
    - サイマルキャストマルチコーデック機能
    - H.264 / HEVC B-frame 対応
    - プレイアウト遅延機能
  - 今後の Sora の新機能と戦略

    - データチャネル積極的改善

      - `RFC 8260 - Stream Schedulers and User Message Interleaving for the Stream Control Transmission Protocol <https://duckduckgo.com/?q=RFC8260&atb=v376-1&ia=web>`_
    - リダイレクトトークンの検討

      - リダイレクト時に認証をスキップできる仕組み
    - セキュリティ強化
    - H.265 (HEVC) 録画機能
    - MP4 出力機能
    - サイマルキャストマルチコーデック録画
    - サイマルキャストマルチコーデックフォールバック
    - マルチフィンガープリント SHA-256/512 対応
    - OBS WHIP/WHEP
    
      - サイマルキャスト
    - RTP/RTCP ダンプ機能

      - pcap で出力できるようになる
    - Media over QUIC Transport (MOQT)

      - 最初は C++ SDK でのサポートを想定
      - WebTransport ではなく QUIC のみの対応を想定
      - コーデックは AV1/Opus １択で進める想定
      - サーバーは Erlang/OTP の QUIC 実装 (自前) を利用
      - クライアントは OpenSSL の QUIC 実装を利用
- Sora Cloud

  - Sora 最新版の反映
  - Suzu Cloud の提供
  - Kohaku Cloud の提供
- Sora C++ SDK

  - [x] サイマルキャストマルチコーデック
  - [x] メンテナンス強化のためのプライオリティ付け
  - Raspberry Pi 対応
- Sora Python SDK

  - [x] nanobind 2.0 による型提供
  - 多機能化
  - Jetson などの別パッケージ化
- Sora Unity SDK

  - WebGL 対応版の検討
- React Component の提供

  - Sora JS SDK を利用した React Component の提供
- Momo

  - 積極的な改善予定
  - [x] NVIDIA Jetson 6 対応
  - [x] NVIDIA Jetson H.265 対応
  - [x] NVIDIA Jetson 5.1.3 対応
  - [x] Intel VPL 対応
- Kohaku

  - [x] TimescaleDB から ClickHouse へ
  - [x] 統計エクスポーターから統計ウェブフックへ
- WebRTC 統計ローカル可視化ツール

  - OSS として公開予定
  - Sora に限定しない MediaProcessors の可視化ツール版

    - WebRTCStatistics とか？
  - WebRTC Stats をローカルでため込みローカルで確認できる仕組み

    - Sora-DevTools に組み込み予定
  - DuckDB-Wasm + OPFS

    - https://github.com/duckdb/duckdb-wasm

2024 年 1 月 16 日 15:00-16:30
---------------------------------------

今回から 15:00 スタート 16:30 終了の 90 分です。今後は平日昼間のみの開催なります。

- 雑談

  - `M121 Release Notes <https://groups.google.com/g/discuss-webrtc/c/N8QOWRz39hc>`_
  - `M120 Release Notes <https://groups.google.com/g/discuss-webrtc/c/U12Vs7hKDMY/m/2DINDrU3AQAJ>`_
  - `WebRTC M119 Release Notes <https://groups.google.com/g/discuss-webrtc/c/LCTbG0jMT9k/m/eNZYttO1AAAJ>`_
  - `WebRTC 118 Release Notes <https://groups.google.com/g/discuss-webrtc/c/6FL4yW3UdZg/m/EoRYc83UAwAJ>`_
  - `WebRTC 117 release notes <https://groups.google.com/g/discuss-webrtc/c/GKl4zc5kTog/m/_QzhHW3GAwAJ>`_
  - `WebRTC 116 Release Notes <https://groups.google.com/g/discuss-webrtc/c/bEsO8Lz7psE/m/wVDwcuhIAAAJ>`_
  - `WebRTC 115 Release Notes <https://groups.google.com/g/discuss-webrtc/c/1CTKFxJsrmQ/m/2v_RuAJdAAAJ>`_
  - `WebRTC 114 release notes <https://groups.google.com/g/discuss-webrtc/c/GS-28AVIhg4/m/wGgWSt0TAgAJ>`_
  - `WebRTC 113 Release Notes <https://groups.google.com/g/discuss-webrtc/c/imXxtjKJfIA/m/kTj9D_PtAQAJ>`_
  - `Mixed-codec simulcast と WebRTC Codec Selection API <https://zenn.dev/shiguredo/articles/webrtc-mixed-codec-simulcast>`_

    - https://chromestatus.com/feature/5200982281027584
    - https://github.com/Orphis/webrtc-extensions/blob/explainer/explainers/codec-selection.md
    - https://bugs.chromium.org/p/webrtc/issues/detail?id=15064
    - https://webrtc.googlesource.com/src/+/43a5dd86c20df887496979acf5041f9920b1b501
    - https://github.com/w3c/webrtc-extensions/issues/43
    - https://www.w3.org/2023/01/17-webrtc-minutes.html#t07
    - https://github.com/w3c/webrtc-extensions/issues/126
    - https://github.com/w3ctag/design-reviews/issues/836
    - https://developer.mozilla.org/en-US/docs/Web/API/RTCRtpCodecParameters
  - `obs-webrtc: Add AV1 Support by Sean-Der · Pull Request #9331 · obsproject/obs-studio <https://github.com/obsproject/obs-studio/pull/9331>`_
  - `The Hidden AV1 Gift in Google Meet - webrtcHacks <https://webrtchacks.com/the-hidden-av1-gift-in-google-meet/>`_
  - `Twilio layoffs: Company to cut 5% of employees <https://www.cnbc.com/2023/12/04/twilio-layoffs-company-to-cut-5percent-of-employees.html>`_
  - `WebCodecs, WebTransport, and the Future of WebRTC - webrtcHacks <https://webrtchacks.com/webcodecs-webtransport-and-webrtc/>`_
  - `Replacing WebRTC - Media over QUIC <https://quic.video/blog/replacing-webrtc/>`_
- WebRTC SFU Sora

  - Sora 2023.2.x の新機能について

    - https://sora-doc.shiguredo.jp/RELEASE_NOTE
    - 新しい録画機能 (セッション単位)
    - レガシー録画機能の廃止
      
      - 2025 年 12 月
    - 両方の録画機能の共存
    - クラスター機能の改善
    
      - セッション状態のクラスターによる共有
    - 転送フィルター機能の紹介
  - 今後の Sora の新機能について

    - リレー機能
    - 音声ストリーミング失敗処理対応
    - OBS HEVC 対応
    - OBS AAC 対応
    - 録画 HEVC や AAC 対応
    - WebRTC Codec Selection API 対応
    - 録画ファイル出力時に WebM の TAG を利用したメタデータ付与
  - アプリケーション連携ドキュメントの提供

    - https://develop.shiguredo-sora-doc.pages.dev/APP_INTEGRATE_TUTORIAL
- Sora Cloud

  - Sora 最新版の反映
  - 録画機能を管理コンソールから利用する
  - ログ検索機能
  - ウェブフック再送信機能
- Sora SDK 全般

  - H.265 対応
  
    - oneVPL
    - NVIDIA Video Codec SDK
  - iOS / Android の C++ SDK 化

    - 完全互換で対応する方針で進めてる
    - まずは iOS から
  - モバイルの音声デバイス周りの改善
- Sora C SDK

  - リダイレクトや複数シグナリング URL

    - この機能に対応した時点でリリース予定
  - Raspberry Pi Zero 対応
  - recvonly (受信のみ) 対応
  - RISC-V 対応
- Sora Python SDK

  - サーバー向け SDK の提供
- React Component の提供

  - Sora JS SDK を利用した React Component の提供
- Momo

  - NVIDIA Jetson 5.1.2 対応
  - NVIDIA Jetson 6 対応
  - NVIDIA Jetson H.265 対応
  - Jetson Orin Nano と Raspberry Pi 5 は優先実装対応

    - HWA エンコーダー非搭載のため積極的に対応する理由がない

2023 年 4 月 18 日 19:00-20:30
---------------------------------------

今回は 19:00 スタート 20:30 終了の 90 分バージョンです。少し延長戦があるかも知れません。

- 雑談

  - `WebRTC 110 Release notes <https://groups.google.com/g/discuss-webrtc/c/fe567r-UUrA>`_
  - `WebRTC 111 Release Notes <https://groups.google.com/g/discuss-webrtc/c/qo2-96L5jEw>`_
  - `WebRTC 112 Release Notes <https://groups.google.com/g/discuss-webrtc/c/V-XFau9W9gY>`_
  - `PSA: wildcard rtcp-fb is coming to Chromium M112+ <https://groups.google.com/g/discuss-webrtc/c/Y_h2B-NOzW0>`_
  - `PSA: VP9/AV1 simulcast support in M113 <https://groups.google.com/g/discuss-webrtc/c/-QQ3pxrl-fw?pli=1>`_
  - `Neural encoding enables more-efficient recovery of lost audio packets - Amazon Science <https://www.amazon.science/blog/neural-encoding-enables-more-efficient-recovery-of-lost-audio-packets>`_

  - `Use of TURN in WebRTC Revisited: It may be more useful than you thought | by Gabor Retvari | L7mp Technologies | Mar, 2023 | Medium <https://medium.com/l7mp-technologies/use-of-turn-in-webrtc-revisited-it-may-be-more-useful-than-you-thought-856059fd27a3>`_
  - `Amazon Chime SDK で 250 本のウェブカム動画ストリームのサポートを開始 <https://aws.amazon.com/jp/about-aws/whats-new/2023/01/amazon-chime-sdk-250-webcam-video-streams/>`_
  - `Safari Technology Preview で WebRTC AV1 が利用可能になった <https://zenn.dev/shiguredo/articles/safari-webrtc-av1>`_
  - `RTC @Scale 2023 | At Scale Conferences <https://atscaleconference.com/events/rtc-scale-2023/>`_
  - `EZDRM debuts WebRTC-DRM for low-latency streaming - Digital TV Europe <https://www.digitaltveurope.com/2023/03/10/ezdrm-debuts-webrtc-drm-for-low-latency-streaming/>`_
  - `Breaking changes in getStats | WebRTC for Developers <https://www.webrtc-developers.com/breaking-changes-in-getstats/>`_
  - `Video Frame Processing on the Web - WebAssembly, WebGPU, WebGL, WebCodecs, WebNN, and WebTransport - webrtcHacks <https://webrtchacks.com/video-frame-processing-on-the-web-webassembly-webgpu-webgl-webcodecs-webnn-and-webtransport/>`_
  - `coturn: No Time to Die - Q&A with new project leads - webrtcHacks <https://webrtchacks.com/coturn-no-time-to-die-qa-with-new-project-leads/>`_
  - `Real-Time Video Processing with WebCodecs and Streams: Processing Pipelines (Part 1) - webrtcHacks <https://webrtchacks.com/real-time-video-processing-with-webcodecs-and-streams-processing-pipelines-part-1/>`_
  - `Cyara Acquires Spearline <https://www.spearline.com/news/cyara-acquires-spearline-to-deliver-worlds-most-comprehensive-customer-experience-assurance-platform/>`_
  - `agones 上に作る QUIC を使った音声通信機能【MIXI TECH CONFERENCE 2023】 - Speaker Deck <https://speakerdeck.com/mixi_engineers/voice-communication-function-using-quic-which-created-on-agones>`_

- WebRTC SFU Sora

  - Sora 2023.1.0 リリースに向けて

    - 転送フィルター機能

      - https://develop.shiguredo-sora-doc.pages.dev/FORWARDING_FILTER
    - OBS (WHIP) 対応

      - https://develop.shiguredo-sora-doc.pages.dev/OBS_WHIP
      - `draft-ietf-wish-whip-08 <https://datatracker.ietf.org/doc/html/draft-ietf-wish-whip-08>`_
    - サイマルキャスト VP9/AV1 対応
    - Lyra 録音

      - そのままでは再生できないので Hisui を使って変換して
    - シグナリング通知に timestamp
    - SDP 再利用
    - クラスターディスク障害強化
    - OpenSSL 3.1.0

      - AVX512 対応
      - 1024 バイト以上での暗号処理が 2 倍以上性能向上
    - IPv6 のみ
  - 次のリリースに向けて

    - **ノード間転送機能**

      - https://develop.shiguredo-sora-doc.pages.dev/INTER_NODE_TRANSFER
    - セッション単位録画機能
- Sora Cloud

  - https://sora-cloud.shiguredo.jp/
  - https://doc.sora-cloud.shiguredo.app/
  - シグナリング URL の一本化
  - 次のリリースに向けて

    - Sora 2023.1 へのアップデート
    - 録画合成機能
    - 文字起こし機能
  - 今後

    - 録画合成エディター
    - Suzu を利用したリアルタイム文字起こし
    - Kohaku を利用した解析
- Sora Labo

  - シグナリング URL の一本化
  - ipv6 専用サーバーの準備
  - WHIP 対応
  - チャネル ID 破壊的変更  

    - # 区切りを _ 区切りに変更する
    - まさか チャネル ID が URL を使う事になると思っていなかった
- Sora Andorid SDK

  - メンテナンスモード
  - Sora 最新版に追従予定
  - C++ SDK 化を予定
- Sora iOS SDK

  - Sora 最新版に追従予定
  - メンテナンスモード
  - C++ SDK 化を予定
- Sora C++ SDK

  - libwebrtc M113
  - バグ退治
- Sora Unity SDK

  - https://github.com/shiguredo/sora-unity-sdk
  - バグ退治
- Sora Python SDK

  - https://github.com/shiguredo/sora-python-sdk/
  - 急いでないのでゆっくり
- Sora Flutter SDK

  - https://github.com/shiguredo/sora-flutter-sdk/
  - 急いでないのでゆっくり
- MediaProcessors

  - https://github.com/shiguredo/media-processors
  - 光量が不足している映像保管
  
    - https://github.com/shiguredo/media-processors/tree/develop/packages/light-adjustment
- Audio Stremaing Gateway Suzu

  - https://github.com/shiguredo/suzu
  - AWS / GCP に対応
  - 無限リトライ対応
  - メッセージ選択機能
- Recording Composition Tool Hisui

  - https://github.com/shiguredo/hisui
  - いくつかのバグ対応
  - Ubuntu 22.04 対応
  - ARM64 対応
  - MP4 (VP9/AAC) が Safari や Win アプリで再生可能に
  - OpenH264 エンコード
  - AV1 デコード/エンコード
  - Lyra デコード
  - 分割録画対応
  - oneVPL による HWA 対応
  
    - `oneapi-src/oneVPL: oneAPI Video Processing Library (oneVPL) dispatcher, tools, and examples <https://github.com/oneapi-src/oneVPL>`_
- WebRTC Stats Collector Kohaku

  - https://github.com/shiguredo/kohaku
  - https://github.com/shiguredo/kohaku/pull/69

    - リライト
- WebRTC Signaling Server Ayame

  - https://github.com/OpenAyame/ayame
  - スタンドアローンモード
- 時雨堂の今後の取り組み

  - ノード間転送による大規模対応
  - WebCodecs + WebTransport + Warp による片方向配信

    - Zig + Erlang で開発していく予定
    - 仕様が安定してからで十分と判断している
  - WebAssembly (Wasm) や WASI を利用したポータビリティを持たせたメディア処理
  
    - MediaProcessors のブラウザ以外の適用
    - MediaAnalyzers の開発

      - 送受信するメディアの品質をブラウザなどでスコアリングする仕組み
      - ベンダーロックフリーの仕組み
      - Sora は送信部分に DataChannel を利用する
    - Sora から Audio/Video を HTTP/2 で受け取って RTMP or RTMP+ で配信する機能

      - CGO 避けたい
      - Go + Wasmtime + Opus to MP3 (WASI) で検討中
- https://roadmap.shiguredo.jp/


2022 年 12 月 6 日 19:00-20:30
---------------------------------------

今回は 19:00 スタート 20:30 終了の 90 分バージョンです。

- 雑談
- WebRTC SFU Sora

  - Sora 2022.2.0 リリースに向けて

    - https://sora-doc-canary.shiguredo.jp/
    - クラスター改善
    - Lyra 対応
    - 音声ストリーミング機能
    - センシティブデータ
    - ウェブフック統計
    - クラスターアルゴリズム変更 (Raft 採用)
    - JSONL 形式ログ対応
    - 録画関連ウェブフック追加
    - ウェブフック mTLS 対応
    - クラッシュログ出力 API
  - 次のリリースに向けて

    - **ノード間転送機能**

      - https://develop.shiguredo-sora-doc.pages.dev/INTER_NODE_TRANSFER
    - 接続時にストリーム受信しない機能
- Sora Cloud

  - https://sora-cloud.shiguredo.jp/
  - https://doc.sora-cloud.shiguredo.app/
  - 正式リリース
  - 今後の展望

    - とにかく安く安定して提供するがテーマ
    - トラフィック可視化機能
    - ログ全部検索機能
    - 文字起こし機能
    - 録画合成機能
    - 統計可視化機能
- Sora C++ SDK

  - Lyra 対応
  - iOS が課題
- Sora Andorid SDK

  - メンテナンスモード
  - Sora 最新版に追従予定
  - C++ SDK 化するか検討中
- Sora iOS SDK

  - Sora 最新版に追従予定
  - メンテナンスモード
- Sora Unity SDK

  - https://github.com/shiguredo/sora-unity-sdk
  - ソフトウェアミュート対応
  - HoloLens2 ソフトウェアミュート対応
- Sora Flutter SDK

  - https://github.com/shiguredo/sora-flutter-sdk/
- Lyra

  - https://github.com/shiguredo/lyra-wasm/
- Audio Stremaing Gateway Suzu

  - https://github.com/shiguredo/suzu

これ以前のイベント内容は以下からどうぞ。
https://github.com/shiguredo/seminar/blob/master/old_webrtc_irregular_online_event.rst

http://66.42.39.71:5000/whip/shiguradio



