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

- Chrome M83 以降必須です
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

- 最新の WebRTC 雑談
  
  - @voluntas
- WebRTC SFU Sora 雑談
  
  - @voluntas
- WebRTC Native Client Momo 雑談
  
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




