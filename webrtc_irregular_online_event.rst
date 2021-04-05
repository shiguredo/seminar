#######################################################
時雨堂 WebRTC 不定期オンライン雑談配信 (SHIGURADIO)
#######################################################

:日時: どこかの火曜日 19:30~20:00 あたりから
:場所: Discord https://discord.gg/TJg5DR4

.. image:: https://i.gyazo.com/0a6b81c59054c9a2d1918df5b6da110d.jpg

概要
====

時雨堂の WebRTC 関する Discord 上で開催するオンライン雑談イベントです。

参加者は一方向での雑談配信を視聴するという形です。そのためカメラやマイクは不要です。
質問はすべて Discord にコメントを書いて頂く形を取ります。

Discord サーバーブースト
========================

Discord で Sora Lab / Sora SDK の Discord サーバへサーバブーストをしてくれているユーザは申請なしで全てのイベントに参加可能です。また、イベントの過去ログを見ることができるようになります。

`サーバーブースト 💨 – Discord <https://support.discord.com/hc/ja/articles/360028038352>`_

2021 年 4 月 6 日 (火) のイベントへの参加申込方法
=====================================================

まず ``Sora Labo / Sora SDK`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/TJg5DR4

その後、新規参加者は 10 分ほど書き込みを待って頂く必要があります。
その間に **アイコンの設定** をお願いします。

``Sora Labo / Sora SDK`` サーバの ``#event`` チャンネルで、
以下のメッセージを **コピペして** 参加を表明してください。

::

    2021 年 4 月 6 日 (火) 19:30~ のイベントに参加します

アイコンが設定済みであれば、 
ロールが時雨堂のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2021-04-06`` というロールが付与されます。

注意
----

- 雑談なので話は発散します
- 開始時間に 1 人でも集まればやります
- 競合他社の参加は禁止します
- 撮影や配信、録画、録音などは全て禁止します
- SNS への共有などは禁止します
- このセミナーは開発者向けです
- 申し込み締切は前日の 23:59 とします
- 視聴用 URL は当日の 19:15 に共有します
- 当日の 19:25 からテスト配信を行います

資料などの公開
==================

参加者限定で公開します。

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

- Chrome M90 以降が必須です (M90 がリリースされていない場合は Dev/Beta/Canary を利用してください)
- Sora Labo で **AV1** が送受信できるかどうかを確認しておいてください
- Sora Labo で **E2EE** が送受信できるかどうかを確認しておいてください
- 当日は繋がらないなどに対して対応は一切行いません
- WebRTC の基本的な話などは一切しません

  - 以下は読んでる前提です
  - `WebRTC コトハジメ <https://gist.github.com/voluntas/67e5a26915751226fdcf>`_
  - `WebRTC の未来 <https://gist.github.com/voluntas/59a135343538c290e515>`_

開催
====

2021 年 4 月 6 日 (火) 19:30~
----------------------------------------------------

**雑談中心のイベントです**

今回は 19:30 スタート 21:00 終了の 1.5 時間バージョンです。

- WebRTC
  
  - `PSA: TURN server ports - intent to limit <https://groups.google.com/g/discuss-webrtc/c/dPklFzpRd9Q/m/d67VDiK0AgAJ?pli=1>`_
  - `バーチャルイベントプラットフォームのユニコーンHopinがさらに2社を買収しビデオ事業に3倍賭け | TechCrunch Japan <https://jp.techcrunch.com/2021/03/25/2021-03-23-hopin-buys-two-more-companies-as-it-triples-down-on-video-focus/>`_
  - `Chromium Blog: Chrome 90 Beta: AV1 Encoder for WebRTC, New Origin Trials, and More <https://blog.chromium.org/2021/03/chrome-90-beta-av1-encoder-for-webrtc.html>`_
  - `8133 - OPUS stereo audio over RTP is muxed to mono - webrtc <https://bugs.chromium.org/p/webrtc/issues/detail?id=8133#c61>`_
  - Twitterのスペースについて

    - https://help.twitter.com/ja/using-twitter/spaces
    - `Twitter is using Janus WebRTC for Twitter Spaces #TwitterSpaces #ReverseEngineering : twitterspaces <https://www.reddit.com/r/twitterspaces/comments/lz5ls1/twitter_is_using_janus_webrtc_for_twitter_spaces/>`_
- WebRTC SFU Sora

  - Erlang VM JIT 対応

    - Ubuntu 限定で RHEL は非対応 ...
  - リップシンク改善
  - DataChannel 対応
  - AV1 対応
  - スポットライト対応
- Sora E2EE

  - 現状共有
  - 今後の予定
  - LINE の E2EE について
- Sora デモ

  - DataChannel 対応
- Sora JavaScript SDK

  - DataChannel 対応
- Sora iOS SDK

  - 2021.1 に向けて開発進めてます
  - サイマルキャスト対応予定
  - スポットライト対応予定
  - libwebrtc M90 アップデート予定
- Sora Android SDK

  - 2021.1 出ました
  - サイマルキャスト対応
  - スポットライト対応
  - libwebrtc M90 アップデート予定
- Sora Unity SDK

  - 2021.1 出ました
  - サイマルキャスト対応
  - スポットライト対応
  - AV1 対応予定
  - libwebrtc M90 アップデート予定
- WebRTC Load Testing Tool Zakuro

  - 2021.1 出ました
  - スポットライト機能
  - YAML 対応
  - libwebrtc M89 対応
  - AV1 対応予定
  - libwebrtc M90 対応予定
- Recording Composition Tool Hisui

  - audio のみ合成対応
  - 変換パラメータチューニング
  - 合成レポート出力対応
  - マルチチャネル合成対応
- Quality Management Tool Kohaku

  - Python にてプロトタイプ開発中
  - プロダクション用の Go 版も並行して開発中
  - TimescaleDB を採用
  - Grafana を採用
  - getStats データのフィルタリングなどに対応 
  - W3C に準拠しつつ Firefox/Safari などにもうまくやっていく
  - 最初は JavaScript SDK
  - iOS / Android / Unity SDK にも対応予定
  - Momo にも対応予定
- WebRTC Native Client Momo

  - バグフィックス版リリース
  - libwebrtc M90 アップデート
- Sora Labo

  - 利用の仕組みを変更の紹介

過去
================

2021 年 2 月 16 日 (火) 20:00~
----------------------------------------------------

**雑談中心のイベントです**

- WebRTC

  - `WebRTC 1.0: Real-Time Communication Between Browsers <https://www.w3.org/TR/webrtc/>`_

    - `WebRTC is now a W3C and IETF standard <https://web.dev/webrtc-standard-announcement/>`_
    - `Web Real-Time Communications (WebRTC) transforms the communications landscape as it becomes a World Wide Web Consortium (W3C) Recommendation and Internet Engineering Task Force (IETF) standards <https://www.w3.org/2021/01/pressrelease-webrtc-rec.html>`_
  - `Chrome 89 Preparing To Ship With AV1 Encoder For WebRTC Usage - Phoronix <https://www.phoronix.com/scan.php?page=news_item&px=Chrome-89-AV1-Encoding>`_

    - `AV1 Encoder - Chrome Platform Status <https://www.chromestatus.com/feature/6206321818861568>`_
    - `The AV1 video codec comes to Webex! <https://blog.webex.com/engineering/the-av1-video-codec-comes-to-webex/>`_
  - `Project Zero: The State of State Machines <https://googleprojectzero.blogspot.com/2021/01/the-state-of-state-machines.html>`_
  - `Details about CVE-2020-26262, bypass of Coturn's default access control protection | Communication Breakdown - real-time communications security <https://www.rtcsec.com/post/2021/01/details-about-cve-2020-26262-bypass-of-coturns-default-access-control-protection/>`_
  - `Release Notes for Safari Technology Preview 120 | WebKit <https://webkit.org/blog/11548/release-notes-for-safari-technology-preview-120/>`_
  
    - Enabled WebRTC VP9 profile 0 by default
  - `Release Notes for Safari Technology Preview 118 | WebKit <https://webkit.org/blog/11439/release-notes-for-safari-technology-preview-118/>`_

    - Fixed ICE not resolving for turns relay candidates rooted in LetsEncrypt CA (r270626)
  - `Release Notes for Safari Technology Preview 117 | WebKit <https://webkit.org/blog/11364/release-notes-for-safari-technology-preview-117/>`_
  - `PSA: WebRTC M88 Release Notes <https://groups.google.com/g/discuss-webrtc/c/A0FjOcTW2c0/m/UAv-veyPCAAJ>`_
  - `PSA: WebRTC M89 Release Notes <https://groups.google.com/g/discuss-webrtc/c/Zrsn2hi8FV0/m/KIbn0EZPBQAJ>`_
  - `PSA: usage of rtp payload types in the range 35-65 in webrtc.org/chrome <https://groups.google.com/g/discuss-webrtc/c/w1SY3bozdvs/m/jX5KhuF4AwAJ>`_
  - `WebRTC Today & Tomorrow: Interview with W3C WebRTC Chair Bernard Aboba - webrtcHacks <https://webrtchacks.com/webrtc-today-tomorrow-bernard-aboba-qa/>`_
  - `Update: Discord confirms raising $100M at a valuation of $7B | TechCrunch <https://techcrunch.com/2020/12/17/filing-discord-is-raising-up-to-140m-at-a-valuation-of-up-to-7b/>`_
  - `Signal >> Blog >> Adding Encrypted Group Calls to Signal <https://signal.org/blog/group-calls/>`_
  - `Solutions - Zero-Trust Security for Webex White Paper - Cisco <https://www.cisco.com/c/en/us/solutions/collateral/collaboration/white-paper-c11-744553.html>`_
  - `10Gbps Unmetered Dedicated Servers | DataPacket.com <https://www.datapacket.com/>`_
  - `xflagstudio/requiem: QuicTransport (WebTransport over QUIC) framework for Elixir <https://github.com/xflagstudio/requiem>`_
  - `PSA: Timeline for Plan B SDP Deprecation and Removal - Please Migrate to Unified Plan <https://groups.google.com/g/discuss-webrtc/c/UBtZfawdIAA/m/-UVQQcubBQAJ>`_
  - @voluntas
- Zenn

  - `iOS 14.3 で Chrome などで getUserMedia が利用できるようになった <https://zenn.dev/voluntas/articles/ios143-wkwebview-getusermedia>`_
  - `WebRTC Insertable Media using Streams <https://zenn.dev/voluntas/articles/webrtc-insertable-streams>`_
  - `Clubhouse リアルタイム配信の仕組みについて (妄想編) <https://zenn.dev/voluntas/scraps/9403b803320d6f>`_
  - `Clubhouse リアルタイム配信の仕組みについて (解説編) <https://zenn.dev/voluntas/scraps/8f35e80a5b5427>`_
  - `WebRTC を今から学ぶ人に向けて <https://zenn.dev/voluntas/scraps/82b9e111f43ab3>`_
  - `Chrome Canary で WebRTC の AV1 が利用できるようになった <https://zenn.dev/voluntas/scraps/a19680d1d349b4>`_
  - `2021 年に出た WebRTC 関連 RFC 一覧 <https://zenn.dev/voluntas/scraps/0dee6d1e838ee8>`_
  - `"Real time communication at scale with Elixir at Discord" の解説と感想を雑に書いていく <https://zenn.dev/voluntas/scraps/2c534189771710>`_
  - `ブラウザにおける VP9 の現状 <https://zenn.dev/voluntas/scraps/8743ceef1a701a>`_
  - `サーバ転送料金まとめ <https://zenn.dev/voluntas/scraps/2650bc3e6b4ea6>`_
  - @voluntas

- 時雨堂製品全体的方針

  - SDK 強化
  - コミュニティ強化
  
    - 5 月からコミュニティマネージャ増強
  - ドキュメント強化

    - 独自ドキュメントテーマ用意
    
      - https://github.com/shiguredo/sphinx_shiguredo_theme
    - 検索機能対応
      
      - Sphinx が検索は頑張らないということなので
      - https://www.algolia.com/ 利用予定
- WebRTC SFU Sora

  - 2020.3 リリース

    - https://sora-doc.shiguredo.jp/release_note#v2020-3
  - 2021.1 に向けて

    - AV1 対応

      - `RTP Payload Format For AV1 <https://aomediacodec.github.io/av1-rtp-spec/>`_
    - VP9 Simulcast 対応
    - AV1 Simulcast 対応
    - DataChannel によるシグナリング
    - DataChannel によるシグナリング通知
    - スポットライト改善

      - ブロックノイズ対策
      - 遅延フォーカス機能
      - 一定時間発話がない場合アンフォーカス機能
      - シグナリング時にフォーカス/アンフォーカスの rid 指定機能

        - アンフォーカス時でも r2 を受信するなどが可能になる
        - フォーカス時も映像を受信しないなどが可能になる
      - ファンフォーカス時でも音声を配信する割合を指定する機能
      - フォーカルからアンフォーカスに切り替わった後でも音声を配信し続ける機能
    - インターコネクト検討
    - リファクタリング
    - E2E テスト強化
  - @voluntas
- Sora E2EE

  - ACME-SSO 調査＆プロトタイプ開発中

    - `E2E Encryption + Identity <https://zenn.dev/voluntas/articles/e2e-encryption-identity>`_
    - `Automated Certificate Management Environment (ACME) Extension for Single Sign On Challenges <https://zenn.dev/voluntas/scraps/abd108a9626b92>`_
    - ブラウザからの利用を想定
    - クライアントは Go で WebAssembly 
    - サーバも Go 
    - 全て Apache Liecnse 2.0 にて公開予定
  - WebRTC の DTLS 利用する証明書を ACME-SSO で発行する仕組みを検討中
  - SFrame 署名調査
  - SFrame セキュリティ検証
  - MLS 調査
  
    - Cisco / Google / Wire / Cloudflare が協力的
- Sora デモ

  - マイク/カメラオフを Sora JavaScript SDK のヘルパー機能を利用
  - 映像枠の追加
  - recoil の利用検討

    - 今のところ保留になった
    - `Recoil <https://recoiljs.org/>`_
  - リファクタリング
- Sora JavaScript SDK

  - Helper 機能の充実
  - テストの充実
  - リファクタリング
- Sora iOS SDK

  - 開発メンバー追加
  - サイマルキャスト対応
  - スポットライト対応
  - libwebrtc M89 対応
  - @voluntas
- Sora Android SDK

  - 開発メンバー追加
  - API v2 追加
  - サイマルキャスト対応
  - スポットライト対応
  - libwebrtc M89 対応
  - @voluntas
- Sora Unity SDK

  - サイマルキャスト対応
  - スポットライト対応
  - 音声のみの配信を検討
  - @voluntas
- Sora Labo

  - さくらインターネット様のさくらクラウドから Vutlr の Dedicated Server に置き換えた
  - 申請前の最大接続時間を 100 分に制限した
  - 申請前の最大連続接続時間を 10 分に制限した
  - 申請後の最大連続接続時間を 60 分に制限した
  - ビットレート制限を 15Mbps まで上げた
  - @voluntas
- WebRTC Load Testing Tool Zakuro

  - 今後の予定
  
    - CentOS 8 非対応
    - マルチチャネル対応
    - YAML によるシナリオ設定対応
    - Apple Silicon 対応検討
    - Prometheus exporter_zakuro 検討
  - @voluntas
- Recording Composition Tool Hisui / cpp-mp4

  - 現状

    - MP4 出力対応
  - 今後

    - 音声のみ合成出力対応
    - AV1 入力対応
    - AV1 出力対応
    - 接続情報埋め込み機能
    - アイコン埋め込み機能
    - タイトル埋め込み機能
    - 時間埋め込み機能
    - JSON によるレイアウト指定対応
    - 複数チャネル対応
    - エンコード時間の改善
    - Prometheus exporter_hisui 検討
  - @voluntas
- WebRTC Native Client Momo

  - 今後

    - Apple Silicon hWA 対応
  - 基本的にはメンテナンスモードで libwebrtc のアップデートが中心

    - これだけでも結構重い
  - @voluntas
- WebRTC Signaling Server Ayame

  - メンテナンスモードで更新はない
  - @voluntas
- Ayame Labo

  - メンテナンスモードで更新はない
  - @voluntas

質問については答えられる範囲で答えます。

2020 年 11 月 10 日 (火) 20:00~
----------------------------------------------------

- WebRTC 雑談

  - WebRTC M87 リリースノート
  - MediaStreamTrack for Insertable Streams of Media

    - https://github.com/alvestrand/mediacapture-insertable-streams/blob/main/explainer.md
  - Native E2E Encryption API

    - https://github.com/youennf/webrtc-insertable-streams/blob/modif/modifications.md
  - Firefox ダメダメ問題

    - https://w3c.github.io/webrtc-interop-reports/webrtc-pc-report.html

  - 背景ぼやかし/バーチャル背景

    - https://ai.googleblog.com/2020/10/background-features-in-google-meet.html
- WebRTC Native Client Momo

  - 2020.10 リリースに向けて

    - 11 月末くらいにリリース予定

      - 焦らずやっていってるのでゆるゆると行きます
    - Jetson Nano VP8 HWA 対応
    - libwebrtc M87 対応
    - --use-native を --hw-mjpeg-decoder bool に名前変更
    - Jetpack 4.4.1 に上げる
- WebRTC SFU Sora 雑談

  - 2020.3 リリースに向けて

    - リリースは 2020 年 12 月
    - サイマルキャスト録画対応

      - Sora Labo に設定済み
      - H.264 の録画は課題あり
    - スポットライト録画対応
    - サイマルキャストカスタマイズ対応

      - それぞれのストリームを自由に変更できる
    - サイマルキャスト転送対応

      - なんとか入れ込みたい
    - E2EE 対応

      - Wasm は公開済み

        - https://github.com/shiguredo/sora-e2ee

          - https://sora-e2ee-wasm.shiguredo.jp/
      - TypeScript 化して Sora JS SDK へ取り込み中
      - Chrome M87 で Stream API が Web Worker で利用可能になる
      
        - Chrome M87 が 11/17 リリースなのでリリース後にサクッと出したい
    - 録画フォルダ構成変更

      ::

        ├── archive
        │   ├── 1CS9QJ0XPN4C76HBGBN6MGMK5M
        │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC.json
        │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC.webm
        │   │   ├── archive-H2NDA2YCGH7S1E9CVMFMXMA34R.json
        │   │   ├── archive-H2NDA2YCGH7S1E9CVMFMXMA34R.webm
        │   │   ├── archive-PBVZQQN3JS3MQF8XHVFXDMCEEC.json
        │   │   ├── archive-PBVZQQN3JS3MQF8XHVFXDMCEEC.webm
        │   │   └── report-1CS9QJ0XPN4C76HBGBN6MGMK5M.json
        │   └── CZZ8A8KZB16A1DF5PKERBHGFNR
        │       ├── archive-3B7AFF8ZRX6VNEYV40B35Z9S2C.json
        │       ├── archive-3B7AFF8ZRX6VNEYV40B35Z9S2C.webm
        │       ├── archive-DGSN3TC0E91RSCZT5KVPRWCDHR.json
        │       ├── archive-DGSN3TC0E91RSCZT5KVPRWCDHR.webm
        │       └── report-CZZ8A8KZB16A1DF5PKERBHGFNR.json

  - 録画ファイル分割

    - 2020.3 には含まれない
    - 分割しないという選択をできなくする予定あり
    - デフォルトは 180 分単位で分割していく
    - API で分割時間を指定可能、最大 1440 分 (24 時間) まで指定可能
    - ウェブフックも分割録画単位で発火する予定
    - ファイル名は *_0001.webm となる

      - _9999 の次は _10000 となる
    ::

      ├── archive
      │   ├── 1CS9QJ0XPN4C76HBGBN6MGMK5M
      │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC_0001.json
      │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC_0001.webm
      │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC_0002.json
      │   │   ├── archive-A4756MXP914ZB265E92JE3ZMWC_0002.webm
      │   │   └── report-1CS9QJ0XPN4C76HBGBN6MGMK5M.json
      │   └── CZZ8A8KZB16A1DF5PKERBHGFNR
      │       ├── archive-3B7AFF8ZRX6VNEYV40B35Z9S2C_0001.json
      │       ├── archive-3B7AFF8ZRX6VNEYV40B35Z9S2C_0001.webm
      │       ├── archive-DGSN3TC0E91RSCZT5KVPRWCDHR_0001.json
      │       ├── archive-DGSN3TC0E91RSCZT5KVPRWCDHR_0001.webm
      │       └── report-CZZ8A8KZB16A1DF5PKERBHGFNR.json
  - iOS / Anroid / Unity SDK の E2EE 対応

    - エンコード済みのフレームに触れる API は見つけてある
    - 来年どこかで対応したい
  - 2021 年の主な対応

    - DataChannel シグナリング
      
      - コストが高すぎて 2020.3 間に合わず
      - ゆっくりやっていきたい
    - WebCodecs / WebTransport 

      - ただ Chrome / Edge 限定なので焦らなくていい
    - Sora 同士の相互通信機能

      - わかりやすく言えばクラスタリング
      - Client -> Sora -> Sora -> Client が可能になる
      - Sora <-> Sora はインターナルネットワークを利用する
  - Sora iOS SDK 2020.7 リリース

    - https://medium.com/shiguredo/sora-ios-sdk-2020-7-%E3%83%AA%E3%83%AA%E3%83%BC%E3%82%B9-bc843773d75e
    - libwebrtc M86 へアップデート
    - 音声モードの音声出力先 API の追加
  - @voluntas
- WebRTC Load Testing Tool Zakuro 雑談

  - 複数チャンネル対応をしていく予定
  - 設定ファイルの用意
  - @voluntas
- Recording Composition Tool Hisui 雑談

  - https://medium.com/shiguredo/%E9%8C%B2%E7%94%BB%E5%90%88%E6%88%90%E3%83%84%E3%83%BC%E3%83%AB%E3%82%92%E9%96%8B%E7%99%BA%E4%B8%AD-a4c75445d4ce
  ::

     $ hisui --help 
     hisui
     Usage: release/hisui [OPTIONS]

     Options:
       -h,--help                   Print this help message and exit
       -f,--in-metadata-file       Metadata filename (REQUIED)
       --out-video-codec           Video codec (VP8 or VP9) default: VP9
       --out-video-frame-rate      Video frame rate (INTEGER/RATIONAL) default: 25)
       --out-webm-file             Output filename
       --max-columns               Max columns (POSITIVE INTEGER) default: 3
       --libvpx-cq-level           libvpx Constrained Quality level (NON NAGATIVE INTEGER) default: 10
       --libvpx-min-q              libvpx minimum (best) quantizer (NON NEGATIVE INTEGER) default: 3
       --libvpx-max-q              libvpx maximum (worst) quantizer (NON NEGATIVE INTEGER) default: 40
       --verbose                   Verbose mode

  - OSS にて公開済み

    - Apache License 2.0
    - https://github.com/shiguredo/hisui
  - Sora 専用の録画合成ツール
  - FFmpeg を利用しない独自ツール
  - 1 バイナリで提供
  
    - ``./hisui [OPTIONS] <recording.report メタデータ>.json``
  - docker 経由での利用も想定
  
    - ``docker run `` で簡単に利用可能
  - 最初は webm (複数) to webm のみ
  - 今後の予定

    - MP4 対応
    - OpenH264 対応
    - レイアウト指定
    - 時間埋め込み
    - 文字列埋め込み

      - タイトル
      - ConnectionID

        - metadata で何かしら埋め込めるようにしたい
  - @voluntas
- WebRTC Signaling Server Ayame

  - Erlang/OTP で実装してみた

    - 商用利用を意識して開発
    - Go で書いたのも残す
    - シグナリングの仕組みはGo 版と完全互換

      - 商用向けにログやエラー周りを強化
    - パッケージを用意
    - スケールするように書いている
  - @voluntas
- Sora Labo

  - https://sora-labo.shiguredo.jp/
  - サンプルを一新したい

    - サイマルキャスト録画を導入済み
    - サイマルキャスト API をさわれるようにしたい
    - 新スポットライトを提供
    - E2EE (Wasm 版) のサンプルを用意する
  - さくらさんから提供いただいているサーバとは別に転送速度制限がない環境を用意するかもしれない

    - 現在 Sora Labo リファクタリング中なので、それが終わったらチャレンジしたい
  - @voluntas
- Ayame Labo

  - https://ayame-labo.shiguredo.jp/
  - Ayame 正式版
  - アカウントを登録してなくても使えるのは維持する
  
    - STUN/TURN が利用できない
    - ルームに認証をかけられない
  - すでに Ayame Labo へ移動していただいている
  - @voluntas

質問については答えられる範囲で答えます。



2020 年 9 月 29 日 (火) 20:00~
----------------------------------------------------

- WebRTC 雑談

  - WebRTC M86 リリースノート

    - https://groups.google.com/g/discuss-webrtc/c/pKCOpi9Llyc/m/QhZjyE02BgAJ
  - Safari 14

    - 開発者メニューで VP9 対応
  - WebCodecs

    - Chrome M86 から Origin Trial 開始
    - https://wicg.github.io/web-codecs/
    - https://www.chromestatus.com/feature/5669293909868544
    - https://www.w3.org/2018/12/games-workshop/slides/21-webtransport-webcodecs.pdf
  - Insertable Streams

    - Chrome M86 からデフォルト搭載
    - Origin Trial から少し仕組みが変わっている
  - Azure Communication Services

    - https://azure.microsoft.com/en-us/blog/build-rich-communication-experiences-at-scale-with-azure-communication-services/
- WebRTC SFU Sora 雑談

  - 2020.2 リリース

    - 新スポットライト
    - 新デモ機能
  - Safari サイマルキャスト対応

    - 次の Sora JS SDK で対応
  - Firefox サイマルキャスト対応

    - 83 で対応
    - https://bugzilla.mozilla.org/show_bug.cgi?id=1663368
    - まだいくつか課題はあるが、すでにチケットになっている
  - 今後の予定

    - 次のリリースは 2020 年 12 月
    - スポットライト 3 レイヤー
    - サイマルキャスト周りの強化

      - レイヤーパラメータ指定可能
      - 録画

        - 最初は最高画質でのみ録画する
      - 転送

        - 最初は全部転送になる可能性あり
    - E2EE 対応

      - wasm 版
      - X3DH / Double Ratchet / Sender Keys
  - @voluntas
- WebRTC Load Testing Tool Zakuro 雑談

  - 2020.1 リリース
    
    - Blend2D の Fake 機能
  - 2020.2 リリース

    - 遅延確認用ゲーム
  - `WebRTC Load Testing Tool Zakuro を作った話 <https://dev.to/wandbox/webrtc-load-testing-tool-zakuro-p61>`_
  - 今後の予定

    - InfluxDB 対応検討
    - 複数シナリオ対応

      - 複数コーデック
      - 複数チャネル ID 対応
    - 設定ファイル対応

      - YAML ベースで行く予定
  - @voluntas
- Sora Labo

  - サンプルを一新する

    - 新スポットライトを提供
    - wasm 版 E2EE のサンプルを用意する
  - さくらさんから提供いただいているサーバとは別に転送速度制限がない環境を用意するかもしれない
  - @voluntas
- WebRTC Signaling Server Ayame

  - Erlang/OTP で実装中

    - 商用利用を意識して開発
    - Go で書いたのも残す
    - 仕様はまったくおなじ

      - 商用向けにログやエラー周りを強化
    - パッケージを用意
    - スケールするように書いている
  - 1:1 からは崩さない
  - @voluntas
- Ayame Labo

  - Ayame 正式版
  - Ayame Lite の利用規約追加版
  - アカウントを登録してなくても使えるのは維持する
  
    - TURN が利用できない
    - ルームに認証をかけられない
  - Sora Labo っぽい感じにする
  - 10 月末リリースを目指す
  - @voluntas
- Recoridng Composition Tool Hisui

  - 9 月から作り始めた
  - Sora 専用の録画合成ツール
  - FFmpeg を利用しない独自ツール
  - OpenH264 は自前で用意する必要あり
  - 1 バイナリで提供
  - ``./hisui [OPTIONS] <recording.report メタデータ>.json``
  - 2020 年 11 月 OSS 公開予定

    - Apache License 2.0 で公開
  - 2020 年 12 月 2020.1 リリース予定
  - 今後の予定

    - WebM 出力対応
    - AV1 / Opus 出力対応
    - レイアウト指定
  - @voluntas

質問については答えられる範囲で答えます。


2020 年 8 月 25 日 (火) 20:00~
----------------------------------------------------

- WebRTC 雑談
  
  - Threema. Cryptography Whitepaper

    - https://threema.ch/press-files/2_documentation/cryptography_whitepaper.pdf
  - `Signal >> Blog >> A new platform is calling: Help us test one-to-one voice and video conversations on Signal Desktop <https://signal.org/blog/desktop-calling-beta/>`_
  - `Video Calls and Seven Years of Telegram <https://telegram.org/blog/video-calls>`_
  - `End-to-End Encryption: The Past, Present and Future of Security <https://resources.frozenmountain.com/developers/blog/end-to-end-encryption-the-past-present-and-future-of-security>`_
  - https://github.com/microsoft/winrtc

    - http://webrtcbydralex.com/index.php/2020/07/26/native-libwebrtc-for-windows-winrtc/
  - `周囲雑音抑制需要の高まりを受けスマートノイズ抑制技術を擁するKrispが5.3億円を調達 | TechCrunch Japan <https://jp.techcrunch.com/2020/08/07/2020-08-05-krisp-snags-5m-a-round-as-demand-grows-for-its-voice-isolating-algorithm/>`_
  - `2034 - WebRTC: usrsctp is called with pointer as network address - project-zero <https://bugs.chromium.org/p/project-zero/issues/detail?id=2034>`_

    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 1 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-1.html>`_
    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 2 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-2.html>`_
    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 3 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-3.html>`_
  - @voluntas
- WebRTC Native Client Momo 雑談

  - 破壊的変更のお知らせ --multistream true | false へ
  - 破壊的変更のお知らせ --simulcast true | false へ
  - SDL に利用したミュート/アンミュート対応
  - `Horo TsuyoshiさんはTwitterを使っています 「先日、病院にPCR検査を受けに行ったら、血液検査の結果の説明を隣の部屋にいる先生からのPCの画面越しに受けた際に、Momo WebRTC Native Clientが使われててちょっとびっくりした。ちなみに、PCR検査は陰性でした。とりあえず良かった。」 / Twitter <https://twitter.com/horo/status/1290113158426763265?s=20>`_
  - macOS 版での H.265 対応

    - Add HEVC codec name.

      - `f026592a6611944ee2ee7face4e56d589a3f08c4 - src - Git at Google <https://webrtc.googlesource.com/src/+/f026592a6611944ee2ee7face4e56d589a3f08c4>`_
  - VP8 / H.264 でのサイマルキャスト対応
  - Jetson Xavier NX 問題

    - ハードウェア Motion JPEG デコーダーが遅い
  - 4K でサイマルキャスト対応？
  - H.265 でサイマルキャスト対応？
  - hakobera プロダクツ紹介

    - `hakobera/go-sora: go-sora is go signaling client library for WebRTC SFU Sora <https://github.com/hakobera/go-sora>`_
    - `hakobera/go-ayame: go-ayame is go client library for WebRTC Signaling Server Ayame <https://github.com/hakobera/go-ayame>`_
    - `hakobera/go-webrtc-decoder: Decoders for WebRTC apps written in go and Pion <https://github.com/hakobera/go-webrtc-decoder>`_
    - おまけ

      - `Support VP9 Scalability Structure (SS) by hakobera · Pull Request #74 · pion/rtp <https://github.com/pion/rtp/pull/74>`_
  - @voluntas @tnoho
- WebRTC SFU Sora 雑談
  
  - Sora Unity SDK の iOS 対応
  - 新スポットライト機能開発状況共有

    - https://gyazo.com/7c7f89244de2f51f924129bcc4d1d6e9
    - https://gyazo.com/e99e8fad2f974d07f73bb0b53a6256cd
  - 新デモ機能開発状況共有

    - https://gyazo.com/42e0a1742a828b62a31cd3e6a72438a0
  - E2EE (鍵合意アルゴリズム利用) 開発状況共有

    - https://github.com/shiguredo/sora-e2ee-wasm
    - https://github.com/shiguredo/sora-e2ee/tree/feature/wasm
  - H.264 プロファイルレベル ID 変更可能機能
  - 統計レポートに項目追加

    - total_connection_created
    - total_connection_updated
    - total_connection_destoryed
  - @voluntas
- WebRTC Signaling Server Ayame 雑談

  - Ayame WebSocket ライブラリの変更予定
  - Ayame Lite リプレイス

    - 今年は無理ですが、来年は正式リリースに向けてやっていきます
    - 利用数はめちゃくちゃ増えてる
    
      - 現時点で累計 25 万接続
  - 自動ビルド復活させてパッケージングを公開する予定
  - Go 1.15 に上げた

    - そのうちリリースする予定
  - iOS / Android SDK は作らない

    - メンテナンスコストが高すぎる
    - React Native WebRTC Kit を使ってもらいたい
  - Unity SDK は作らない

    - メンテナンスコストが高すぎる
    - 公式を使ってほしい

      - https://github.com/Unity-Technologies/com.unity.webrtc
      - ロードマップが増えてた
  - Go / Python サンプルを検討中

    - OpenAyame/ayame-go-samples
     
      - Pion を使ったサンプル
    - OpenAyame/ayame-python-samples

      - aiortc によるサンプル
    - SDK は提供しない
  - @voluntas
- React Native WebRTC Kit

  - Simulcast 対応
  - getStats 対応
  - M85 対応
  - @voluntas
- Sora Labo

  - Sora Labo 向け iOS / Android サンプルの用意

    - Sora SDK を利用したサンプル
    - ChannelID と SignalingKey を設定するだけで使えるようになる
    - shiguredo/sora-labo-ios-sdk-samples
    - shiguredo/sora-labo-android-sdk-samples
  - 鍵合意アルゴリズムを利用した E2EE サンプルの追加
- 時雨堂の今後の新規プロジェクト

  - Sora 向け負荷試験ツールの OSS 提供

    - WebRTC Load Testing Tool Zakuro
    - すでに開発を進めており 9 月末までにはアルファ版を公開する予定
    - ファーストリリースでは Ubuntu 20.04 x86_64 でのみ動作
  - Sora 向け統計解析ツールの OSS 提供

    - 名前まだ決めてない
  - Sora 向け録画合成ツールの OSS 提供

    - 名前まだ決めてない
  - @voluntas

2020 年 ７ 月 14 日 (火) 20:00~
----------------------------------------------------

- 最新の WebRTC 雑談
  
  - Firefox 78 で rid ベースの Simulcast

    - ただなんか仕様が怪しい
  - `Zoom on Web: Getting Connected with Advanced Web Technology <https://youtu.be/r3QPKK0JPtI?t=10032>`_
  
    - `WebAssembly SIMD - Chrome Platform Status <https://www.chromestatus.com/feature/6533147810332672>`_
    - `QuicTransport - Chrome Platform Status <https://www.chromestatus.com/feature/4854144902889472>`_
    - `WebCodecs - Chrome Platform Status <https://www.chromestatus.com/feature/5669293909868544>`_
  - WebTransport

    - `Experimenting with QuicTransport <https://web.dev/quictransport/>`_
    - `WebTransport over QUIC <https://tools.ietf.org/id/draft-vvv-webtransport-quic-02.html>`_
    - `The WebTransport Protocol Framework <https://tools.ietf.org/id/draft-vvv-webtransport-overview-01.html>`_
  - WebAssembly SIMD

    - `Fast, parallel applications with WebAssembly SIMD · V8 <https://v8.dev/features/simd>`_
    - `V8がWebAssembly SIMDをサポート <https://www.infoq.com/jp/news/2020/04/v8-webassembly-simd/>`_
  - @voluntas
- React Native WebRTC Kit

  - https://github.com/react-native-webrtc-kit/react-native-webrtc-kit
  - libwebrtc M83 への対応の苦労話
  - @voluntas
- WebRTC SFU Sora 雑談

  - Sora 2020.1 の機能紹介

    - PauseRtpStream / ResumeRTPStream API
    - Simulcast 個別画質指定 API

  - `Sora の今後について <https://medium.com/shiguredo/webrtc-sfu-sora-%E3%81%AE%E4%BB%8A%E5%BE%8C-2f0a9c3359a7>`_
    
    - Sora E2EE の wasm 実装について
    - Sora Signaling の DataChannel 実装について
    - Sora ARMv8 版の提供

      - Graviton2
  - @voluntas
- WebRTC Native Client Momo 雑談
  
  - Momo の今後について
    
    - VP9 HWA 対応
    - Simulcast VP8/H.264 対応
    - Intel Media SDK 対応
    - H.265 対応
  - NVIDIA Jetson の Xavier NX / AGX Xavier について
  - SDL の良さ
  - @voluntas @tnoho @melpon
- WebRTC P2P＋MCU Azuki 雑談
  
  - こんなの考えてるけどどうですか？という雑談会です
  - `WebRTC P2P+MCU Azuki (仮) <https://gist.github.com/voluntas/a9519de94f92102cc22b5f723d03dbd6>`_
  - @voluntas @tnoho @melpon

質問については答えられる範囲で答えます。

2020 年 6 月 23 日 (火) 20:00~
----------------------------------------------------

- 最新の WebRTC 雑談

  - 特になければ飛ばします
  - @voluntas
- WebRTC SFU + Message Layer Security + End to End Media Encryption 雑談
  
  - MLS / SFrame / Google Duo / Signal などについて
  - @voluntas
- オライリーとラムダノートから出版されている本の宣伝

  - `O'Reilly Japan - ハイパフォーマンス ブラウザネットワーキング <https://www.oreilly.co.jp/books/9784873116761/>`_
  - `O'Reilly Japan - Real World HTTP 第2版 <https://www.oreilly.co.jp/books/9784873119038/>`_
  - `プロフェッショナルSSL/TLS（紙書籍＋電子書籍） – 技術書出版と販売のラムダノート <https://www.lambdanote.com/products/tls>`_
  - @voluntas

質問については答えられる範囲で答えます。

2020 年 6 月 9 日 (火) 20:00~
----------------------------------------------------

- 最新の WebRTC 雑談
  
  - @voluntas
- WebTransport / HTTP/3 / QUIC 雑談

  - @voluntas @flano-yuki
- ImageFlux Live Streaming 宣伝

  - `ライブ配信サービス ImageFlux Live Streaming｜さくらインターネット <https://www.sakura.ad.jp/services/imageflux/livestreaming/>`_
  - @voluntas
- オライリーとラムダノートから出版されている本の宣伝

  - `O'Reilly Japan - ハイパフォーマンス ブラウザネットワーキング <https://www.oreilly.co.jp/books/9784873116761/>`_
  - `O'Reilly Japan - Real World HTTP 第2版 <https://www.oreilly.co.jp/books/9784873119038/>`_
  - `プロフェッショナルSSL/TLS（紙書籍＋電子書籍） – 技術書出版と販売のラムダノート <https://www.lambdanote.com/products/tls>`_
  - @voluntas

質問については答えられる範囲で答えます。


2020 年 5 月 26 日 (火) 20:00~
----------------------------------------------------

:当日参加者: 36 名

- 最新の WebRTC 雑談
  
  - @voluntas
- 最新の WebRTC SFU Sora 情報
  
  - @voluntas
- 最新の Sora Unity SDK 情報
  
  - @voluntas @melpon (予定)
- 最新の WebRTC Native Client Momo 情報
  
  - @voluntas @tnoho
- 今後の React Native WebRTC Kit について

  - @voluntas
- 今後の WebRTC Signaling Server Ayame について
  
  - @voluntas
- オライリーとラムダノートから出版されている本の宣伝

  - `O'Reilly Japan - ハイパフォーマンス ブラウザネットワーキング <https://www.oreilly.co.jp/books/9784873116761/>`_
  - `O'Reilly Japan - Real World HTTP 第2版 <https://www.oreilly.co.jp/books/9784873119038/>`_
  - `プロフェッショナルSSL/TLS（紙書籍＋電子書籍） – 技術書出版と販売のラムダノート <https://www.lambdanote.com/products/tls>`_
  - @voluntas

質問については答えられる範囲で答えます。



