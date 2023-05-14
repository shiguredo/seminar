#######################################
時雨堂 WebRTC 入門 オンラインイベント
#######################################

:日時: 2023 年 5 月 25 日 (木) 14:00-18:00
:場所: オンライン Discord https://discord.gg/shiguredo

概要
====

**時雨堂主催の企業としてのイベントです**

実際に利用されている WebRTC 製品を 1 から開発している企業の中の人が WebRTC について説明します。
できるだけわかりやすく説明しますし、その場での質問を積極的に受け付けます。

ただし、コードを書くなどのハンズオン系は一切やりません。

WebRTC を理解している人を増やすことが目的であり、
自社製品を売ることが目的ではないので、自社製品の宣伝などは行いません。

3-4 ヶ月に一回、自社製品の宣伝イベントをやっているのでそちらにご参加ください。

目的
====

WebRTC の **正しい知識** を強制的にインプットさせ、
その後 WebRTC を触るときに「これ WebRTC 入門セミナーで習ったやつだ」となるのを目的とします。

講師
====

`時雨堂 <https://shiguredo.jp>`_ `@voluntas <https://twitter.com/voluntas>`_

時雨堂の創業者で、時雨堂が開発、販売している WebRTC SFU Sora の設計者です。

費用
====

無料です。

参加条件
==========

**競合他社の参加はお断りします**

WebRTC を学ぶ気がある人。

参加申込方法
===========

``時雨堂コミュニティ`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/shiguredo

電話番号認証と **アイコンの設定** をお願いします。

``時雨堂コミュニュティ`` サーバの ``#event`` チャンネルで、
参加したいイベントの投稿に **参加します** とメッセージを残してください。

アイコンが設定済みであれば、 
ロールが管理者のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2023-05-25`` というロールが付与されます。

その後は ``2023-05-25`` というイベント専用のチャネルが見えるようになります。

注意
----

- このイベントはオンラインで開催されます
- このイベントは開発者向けです
- 開始時間に 1 人でも集まればやります
- 競合他社の参加は禁止します
- WebRTC に批判的な方の参加を禁止します
- 撮影や配信、録画、録音などは全て禁止します
- アーカイブは残しません
- SNS への共有などは禁止します
- 申込は前日までとします
- 視聴用 URL は当日の開始 60 分前に共有します
- 当日の 10 分前からテストも込めて配信を開始します

お問い合わせ
================

不明点などは Discord の #event-announce にてお問い合わせください。

イベントの形式
================

資料を用意してそれに沿って進めつつ、
Discord でリアルタイムにコメントでの質問を拾いつつ説明していきます。

資料は公開します。また、 Discord のイベント用チャネルについては残します。
アーカイブは残しません。

録画、録音、SNS への共有は禁止します。こちらはご理解ください。

イベントの流れ
===================

**当日に予習を行います**

- 1/3 の時間を使い、まず最後まで大まかに説明をします
  - これが予習です
- 2/3 の時間を利用して、細かく説明します

休憩
================

適当にトイレ休憩とったりします。

キャンセルや退席
================

- 無言でのキャンセル可
- 無言での退席可

申請用
===========

WebRTC の正しい知識を学ぶ機会を提供する必要があると考え、
多くの企業に利用されている WebRTC SFU Sora の開発メーカーである時雨堂が主催するイベントです。

学べること
============

**資料は当日共有します**

現時点での WebRTC の状況を踏まえて話をします。

- WebRTC の歴史
  - プラン B とユニファイドプラン
  - マルチストリーム
  - ポート共通化
  - H.264
  - VP9
  - サイマルキャスト
  - AV1
  - mDNS
- WebRTC を学ぶポイント
  - どこまで深追いしたいかどうか
  - SDP は読めた方がいいの？
  - RTP や SCTP について学ぶ必要性は？
  - STUN や TURN の仕組みは理解した方がいい
- WebRTC の仕組み
  - Media Transport
  - Data Channels
  - W3C 解説
  - RFC 解説
- WebRTC シグナリング
  - 手動
  - XHR
  - WebSocket
  - XMPP
- WebRTC プロトコルスタック
  - SDP
  - ICE
  - STUN
  - TURN
  - DTLS
  - RTP
  - RTCP
  - SRTP/SRTCP
  - SCTP
- WebRTC SFU の仕組み
  - MCU との比較
  - SFU の仕組み
- WebRTC の今
  - AV1
  - SVC
  - WHIP / WHEP
- WebRTC の今後
  - QUIC
  - HTTP/3
  - WebTransport
  - WebCodecs
  - Warp
  - RTP over WebTransport
  - libwebrtc の代わり
- WebRTC の OSS
  - OSS を採用すべきかどうか
  - OSS を選ぶときのポイント
  - WebRTC の SaaS を選ぶときのポイント

学べないこと
============

- NAPT 関連

  - 時間がかかるので割愛します、学びたい人は Tailscale の記事を読んでください
  - `How NAT traversal works · Tailscale <https://tailscale.com/blog/how-nat-traversal-works/>`_
- libwebrtc 関連

  - 講師が明るくないので話しません
- ハードウェア関連

  - 講師が明るくないので話しません

参考資料
==========

**そのうち消します**

- WebRTC 関連 RFC

  - `RFC 8825: Overview: Real-Time Protocols for Browser-Based Applications <https://www.rfc-editor.org/rfc/rfc8825.html>`_
  - `RFC 8835: Transports for WebRTC <https://www.rfc-editor.org/rfc/rfc8835.html>`_
  - `RFC 8853: Using Simulcast in Session Description Protocol (SDP) and RTP Sessions <https://www.rfc-editor.org/rfc/rfc8853>`_
- WebRTC 関連 RFC ドラフト

  - `draft-uberti-rtcweb-rfc8829bis-04 <https://datatracker.ietf.org/doc/html/draft-uberti-rtcweb-rfc8829bis-04>`_
- WebRTC 関連 W3C

  - `WebRTC: Real-Time Communication in Browsers <https://www.w3.org/TR/webrtc/>`_
  - `Identifiers for WebRTC's Statistics API <https://www.w3.org/TR/webrtc-stats/>`_
  - `Scalable Video Coding (SVC) Extension for WebRTC <https://www.w3.org/TR/webrtc-svc/>`_
  - `WebRTC Encoded Transform <https://www.w3.org/TR/webrtc-encoded-transform/>`_
  - `WebRTC Extensions <https://w3c.github.io/webrtc-extensions/>`_
  - `WebRTC Priority Control API <https://www.w3.org/TR/webrtc-priority/>`_
  - `Media Capture and Streams <https://www.w3.org/TR/mediacapture-streams/>`_
  - `Audio Output Devices API <https://www.w3.org/TR/audio-output/>`_
  - `MediaStreamTrack Content Hints <https://www.w3.org/TR/mst-content-hint/>`_
  - `MediaStreamTrack Insertable Media Processing using Streams <https://www.w3.org/TR/mediacapture-transform/>`_
  - `Screen Capture <https://www.w3.org/TR/screen-capture/>`_
  - `WebRTC Extended Use Cases <https://www.w3.org/TR/webrtc-nv-use-cases/>`_
- `はじめに | 好奇心旺盛な人のためのWebRTC <https://webrtcforthecurious.com/ja/>`_
- @voluntas が書いた資料

  - `WebRTC を今から学ぶ人に向けて <https://zenn.dev/voluntas/scraps/82b9e111f43ab3>`_
  - `WebRTC コトハジメ <https://gist.github.com/voluntas/67e5a26915751226fdcf>`_
  - `WebRTC SFU コトハジメ <https://gist.github.com/voluntas/4d2bd3e878965bdd747a>`_
