# gamen-fumin-info
# 画面不眠 (GamenFumin)

[![GitHub Release](https://img.shields.io/github/v/release/jie-arue/gamen-fumin-info?style=for-the-badge&color=blue)](https://github.com/jie-arue/gamen-fumin-info/releases)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/jie-arue/gamen-fumin-info/total?style=for-the-badge&color=brightgreen)](https://github.com/jie-arue/gamen-fumin-info/releases)
[![Language-Kotlin](https://img.shields.io/badge/Language-Kotlin-orange?style=for-the-badge&logo=kotlin)](https://kotlinlang.org/)
[![Platform-Android](https://img.shields.io/badge/Platform-Android-3DDC84?style=for-the-badge&logo=android&logoColor=white)](https://www.android.com/)

指定した時間、画面を消灯させずに点灯状態を維持する Android 用ツールです。

読書中、料理のレシピ確認中、デバッグ作業中など、「勝手に画面が消えてほしくない」シーンで活躍します。

シンプルな操作で、必要な時だけ画面を明るく保ちます。



■ 主な機能


スリープ防止機能: 指定した時間（0〜180分）、画面を点灯したまま維持します 。

画面暗転モード: 点灯状態を維持したまま画面を暗くし、バッテリー消費を抑えます（20%〜100%で調整可能） 。

ワンタップ復元: 画面が暗くなっている時にタップするだけで、即座に元の明るさに戻ります 。

安全装置（バッテリー監視）: 指定したバッテリー残量（15%〜40%）を下回ると、自動的にモードを終了し、スマホの電池切れを防ぎます 。

タイマー通知: 終了の3分前にフローティング通知でお知らせします 。



■ インストール方法


本リポジトリの Releases ページから最新の APK ファイルをダウンロードします。

ダウンロードしたファイルを開き、インストールを開始します。

Androidの警告（不明なアプリのインストール）が表示された場合は、一時的に許可設定を行ってください。



■ 使い方（基本の流れ）


初回起動: 以下の3つの権限設定を行ってください 。

バッテリー制限なし: バックグラウンドでの強制終了を防ぎます 。

他のアプリに重ねて表示: 画面維持フィルターの配置に必要です 。

通知許可: 動作状況の確認や停止操作に必要です 。

設定: 明るさ、タイマー、安全装置（バッテリー残量）を調整して「開始」を押します 。

終了: 通知パネルの「停止」をタップ、または「一時停止」ボタンでコントロールできます 。



■ 更新履歴


v1.0.4 (2026.03.21) 

タップして暗画面から復帰した時に再暗転する時間を１～３分の間で選べるようにしました。

無操作終了のタイマーが、操作してもリセットされない不具合を解消しました。


v1.0.3 (2026.03.16)

バッテリー残量による自動停止機能を追加しました 。

15%〜40%の間でしきい値を設定可能 。

自動終了時にはフローティング通知でお知らせします。

節電機能と連動できるよう、Androidの設定画面へのリンクを設けました 。


v1.0.2 (2026.03.15)

画面を暗くする処理中に Google Play ストア等のセキュリティが厳しいアプリで操作不能になる問題を修正しました（タップでの明るさ復元機能による回避） 。

v1.0.1 (2026.03.15)

画面を暗くしてバッテリーを節約する機能を追加しました 。

v1.0.0 (2026.03.10)

初版リリース 。


■ 著作権および免責事項

Copyright © 2026 jiearue（じえあるえ）. All Rights Reserved. 

本アプリに関する著作権は、jiearue（じえあるえ）に帰属します 。

無断での複製、改変、再配布、販売等を禁止します 。

【免責事項】

本アプリの利用により生じた、いかなるトラブル、損失、損害（バッテリーの消耗、機器の不具合等を含む）についても、開発者は一切の責任を負いません。ご自身の責任においてご利用ください 。
