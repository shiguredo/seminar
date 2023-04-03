#######################################################
時雨堂 WebRTC 不定期オンライン雑談配信 (SHIGURADIO)
#######################################################

:日時: どこかの火曜日 19:00 ~ 20:00 あたりから
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

2023 年 4 月 18 日 (火) のイベントへの参加申込方法
=====================================================

まず ``時雨堂コミュニティ`` の Discord のサーバに参加している必要があります。

Discord サーバには以下から参加可能です。

- https://discord.gg/shiguredo

電話番号認証と **アイコンの設定** をお願いします。

``時雨堂コミュニュティ`` サーバの ``#event`` チャンネルで、
イベントの投稿に **参加します** とメッセージを残してください。

アイコンが設定済みであれば、 
ロールが管理者のアカウントから参加宣言にリアクションが付き、
その後イベント用のロールを付与されます。

今回は ``2023-04-18`` というロールが付与されます。

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

2023 年 4 月 18 日 19:00-20:30
---------------------------------------

今回は 19:00 スタート 20:30 終了の 90 分バージョンです。

- 雑談

  - 
- WebRTC SFU Sora

  - Sora 2023.1.0 リリースに向けて

    - 転送フィルター機能

      - https://develop.shiguredo-sora-doc.pages.dev/FORWARDING_FILTER
    - OBS (WHIP) 対応

      - https://develop.shiguredo-sora-doc.pages.dev/OBS_WHIP
    - サイマルキャスト VP9/AV1 対応
    - Lyra 録音

      - そのままでは再生できないので Hisui を使って変換して
    - OpenSSL 3.1.0

      - AVX512 対応
      - 1024 バイト以上での暗号処理が 2 倍以上性能向上
  - 次のリリースに向けて

    - **ノード間転送機能**

      - https://develop.shiguredo-sora-doc.pages.dev/INTER_NODE_TRANSFER
    - 接続時にストリーム受信しない機能
- Sora Cloud

  - https://sora-cloud.shiguredo.jp/
  - https://doc.sora-cloud.shiguredo.app/
  - 次のリリースに向けて

    - 録画合成機能
    - 文字起こし機能
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
- Sora Unity SDK

  - https://github.com/shiguredo/sora-unity-sdk
- Sora Python SDK

  - https://github.com/shiguredo/sora-python-sdk/
- Sora Flutter SDK

  - https://github.com/shiguredo/sora-flutter-sdk/
- MediaProcessors

  - https://github.com/shiguredo/media-processors
  - 光量が不足している映像保管
  
    - https://github.com/shiguredo/media-processors/tree/develop/packages/light-adjustment
- Audio Stremaing Gateway Suzu

   - https://github.com/shiguredo/suzu
   - AWS / GCP に対応
   - 無限リトライ対応
- Recording Composition Tool Hisui

   - https://github.com/shiguredo/hisui
   - いくつかのバグ対応
   - Ubuntu 22.04 対応
   - ARM64 対応
   - MP4 (VP9/AAC) が Safari や Win アプリで再生可能に
- WebRTC Signaling Server Ayame

   - https://github.com/OpenAyame/ayame


過去
================


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


