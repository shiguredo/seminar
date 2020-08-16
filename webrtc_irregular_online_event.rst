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

2020 年 8 月 25 日 (火) のイベントへの参加申込方法
=====================================================

まず ``Sora Labo / Sora SDK`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/TJg5DR4

その後、新規参加者は 10 分ほど書き込みを待って頂く必要があります。
その間に **アイコンの設定** をお願いします。

``Sora Labo / Sora SDK`` サーバの ``#event`` チャンネルで、
以下のメッセージを **コピペして** 参加を表明してください。

::

    2020 年 8 月 25 日 (火) 20:00~ のイベントに参加します

アイコンが設定済みであれば、 
ロールが時雨堂のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2020-08-25`` というロールが付与されます。

注意
----

- 雑談なので話は発散します
- 開始時間に 1 人でも集まればやります
- 弊社が競合他社と判断した方の参加は禁止します
- 撮影や配信などは全て禁止します
- 今の所 SNS への共有などは禁止します
- このセミナーは開発者向けです
- 申し込み締切は前日の 23:59 とします
- 視聴用 URL は当日の 18:45 に共有します
- 当日の 18:55 からテスト配信を行います

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

2020 年 8 月 25 日 (火) 20:00~
----------------------------------------------------

- WebRTC 雑談
  
  - Threema. Cryptography Whitepaper

    - https://threema.ch/press-files/2_documentation/cryptography_whitepaper.pdf
  - `Signal >> Blog >> A new platform is calling: Help us test one-to-one voice and video conversations on Signal Desktop <https://signal.org/blog/desktop-calling-beta/>`_
  - `Video Calls and Seven Years of Telegram <https://telegram.org/blog/video-calls>`_
  - https://github.com/microsoft/winrtc

    - http://webrtcbydralex.com/index.php/2020/07/26/native-libwebrtc-for-windows-winrtc/
  - `周囲雑音抑制需要の高まりを受けスマートノイズ抑制技術を擁するKrispが5.3億円を調達 | TechCrunch Japan <https://jp.techcrunch.com/2020/08/07/2020-08-05-krisp-snags-5m-a-round-as-demand-grows-for-its-voice-isolating-algorithm/>`_
  - `2034 - WebRTC: usrsctp is called with pointer as network address - project-zero <https://bugs.chromium.org/p/project-zero/issues/detail?id=2034>`_

    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 1 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-1.html>`_
    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 2 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-2.html>`_
    - `Project Zero: Exploiting Android Messengers with WebRTC: Part 3 <https://googleprojectzero.blogspot.com/2020/08/exploiting-android-messengers-part-3.html>`_
  - @voluntas
- WebRTC Native Client Momo 雑談

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
  - @voluntas
- WebRTC Signaling Server Ayame 雑談

  - Ayame Lite リプレイス

    - 今年は無理です
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
  - @voluntas
- React Native WebRTC Kit

  - Simulcast 対応
  - M85 対応
  - @voluntas
- 時雨堂の今後の新規プロジェクト

  - Sora 向け統計解析パッケージの OSS 提供
  - Sora 向け録画合成パッケージの OSS 提供
  - Sora 向け負荷試験パッケージの OSS 提供
  - @voluntas


質問については答えられる範囲で答えます。

今後の予定
=================

今の所未定です。

過去
================

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
