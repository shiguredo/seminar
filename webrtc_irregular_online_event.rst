#######################################################
時雨堂 WebRTC 不定期オンライン雑談配信 (SHIGURADIO)
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

`サーバーブースト 💨 – Discord <https://support.discord.com/hc/ja/articles/360028038352>`_

2024 年 1 月 16 日 (火) のイベントへの参加申込方法
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

今回は ``2024-01-16`` というロールが付与されます。

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

- Chrome の最新版が必須です
- WebRTC の基本的な話などは一切しません

  - 以下は読んでる前提です
  - `WebRTC コトハジメ <https://gist.github.com/voluntas/67e5a26915751226fdcf>`_
  - `WebRTC の未来 <https://gist.github.com/voluntas/59a135343538c290e515>`_

開催
====

2024 年 1 月 16 日 15:00-16:30
---------------------------------------

今回から 15:00 スタート 16:30 終了の 90 分です。今後は平日昼間のみの開催なります。

- 雑談
- WebRTC SFU Sora

  - Sora 2023.2.x の新機能について

    - 新しい録画機能 (セッション単位)
    - レガシー録画機能の廃止
      
      - 2025 年 12 月
    - 両方の録画機能の共存
    - クラスター機能の改善
    
      - セッション状態のクラスターによる共有
    - 転送フィルター機能の紹介
- Sora Cloud

  - Sora 最新版の反映
  - 録画機能を管理コンソールから利用する
- Sora SDK

  - H.265 対応
  - iOS / Android の C++ SDK 化

    - 完全互換で対応する方針で進めてる
  - モバイルの音声デバイス周りの改善
  - Sora C SDK

    - リダイレクトや複数シグナリング URL
    - Raspberry Pi Zero 対応
    - recvonly (受信のみ) 対応
    - RISC-V 対応
- Momo

  - NVIDIA Jetson H.265 対応
  - メンテナンスモードで機能追加の予定は優先実装以外ではなし
  - 積極的なアップデートはしないが、セキュリティアップデートはする

過去
================

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
