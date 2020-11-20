#######################################################
時雨堂 WebRTC 不定期オンライン雑談配信 (SHIGURADIO)
#######################################################

:日時: どこかの火曜日 20:00 から
:場所: Discord https://discord.gg/TJg5DR4

.. image:: https://i.gyazo.com/0a6b81c59054c9a2d1918df5b6da110d.jpg

概要
====

時雨堂の WebRTC 関する Discord 上で開催するオンライン雑談イベントです。

参加者は一方向での雑談配信を視聴するという形です。そのためカメラやマイクは不要です。
質問はすべて Discord にコメントを書いて頂く形を取ります。

2020 年 11 月 10 日 (火) のイベントへの参加申込方法
=====================================================

まず ``Sora Labo / Sora SDK`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/TJg5DR4

その後、新規参加者は 10 分ほど書き込みを待って頂く必要があります。
その間に **アイコンの設定** をお願いします。

``Sora Labo / Sora SDK`` サーバの ``#event`` チャンネルで、
以下のメッセージを **コピペして** 参加を表明してください。

::

    2020 年 11 月 10 日 (火) 20:00~ のイベントに参加します

アイコンが設定済みであれば、 
ロールが時雨堂のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2020-11-10`` というロールが付与されます。

注意
----

- 雑談なので話は発散します
- 開始時間に 1 人でも集まればやります
- 弊社が競合他社と判断した方の参加は禁止します
- 撮影や配信などは全て禁止します
- 今の所 SNS への共有などは禁止します
- このセミナーは開発者向けです
- 申し込み締切は前日の 23:59 とします
- 視聴用 URL は当日の 19:45 に共有します
- 当日の 19:55 からテスト配信を行います

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

- Chrome M83 または Edge M83 以降が必須です
- Sora Labo で **E2EE** が送受信できるかどうかを確認しておいてください
- 当日は繋がらないなどに対して対応は一切行いません
- WebRTC の基本的な話などは一切しません

  - 以下は読んでる前提です
  - `WebRTC コトハジメ <https://gist.github.com/voluntas/67e5a26915751226fdcf>`_
  - `WebRTC の未来 <https://gist.github.com/voluntas/59a135343538c290e515>`_

開催
====

2020 年 12 月 22 日 (火) 14:00~ の予定
----------------------------------------------------

**日程が決定次第共有します**

いつもと違い、今回は WebRTC SFU Sora に特化したイベントになります

Sora を実際に開発しているメンバーと自由に意見交換ができるイベントです。

2021 年 1 月 19 or 26 日 (火) 20:00~  の予定
----------------------------------------------------

**日程が決定次第共有します**

いつもと違い、今回は DataChannel / QUIC / WebTransport に特化したイベントになります。

過去
================

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








