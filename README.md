# 9/18(キックオフ)
## やったこと
Recursion運営との就活に関してのMTG

内容は下記に列記する。
* 自分のスキルセットの共有
  * Recursionの進捗(上級/OOP/デザインパターン/React/Project5/上級開発)修了
  * TypeScript
  * React
* 就職目標の共有
  * 冬までにフロントエンドエンジニアとして就職する
  * 就職条件はゆるめ（今後詰める）
* 就活に関してRecursion運営から提供できることの共有
  * レジュメ
  * スキル評価
  * 1on1でのMTG等
* これからすることの共有
  1. 一般向けのポートフォリオ作成(1カ月)
       * フレームワークを使用
       * WebAPIを使用
       * 正規表現を使用したバリデーション
       * OAuth2を使用
       * データベースを使用したもの（できればGraphQLを利用する）
  2. レジュメ作成
  3. 職探し

## 決定事項
* 引き継ぎ終了後、活動予定(9/20~)
* 1カ月で一般向けのポートフォリオ作成
* ポートフォリオ作成と並行して就活事情等をリサーチする

# 9/20 - 9/23
## 目的
Webアプリの全体像を把握する

## やったこと
- 記録用[リポジトリ](https://github.com/motsu8/recode_employment)作成
- [ロードマップ](#ロードマップ)作成
- [要件定義](https://github.com/motsu8/youtube_note/wiki/%E8%A6%81%E4%BB%B6%E5%AE%9A%E7%BE%A9)の設定
- [ワイヤフレーム](https://www.figma.com/file/4D9cXazTk4tETLAgHa1N0w/YouTube_Note?type=design&node-id=0%3A1&mode=design&t=szcxuvwjjXmHRGyn-1)作成
- [アクティビティ図](https://github.com/motsu8/youtube_note/wiki/%E8%A8%AD%E8%A8%88#%E3%82%A2%E3%82%AF%E3%83%86%E3%82%A3%E3%83%93%E3%83%86%E3%82%A3%E5%9B%B3)作成
- [クラス図](https://github.com/motsu8/youtube_note/wiki/%E8%A8%AD%E8%A8%88#%E3%82%AF%E3%83%A9%E3%82%B9%E5%9B%B3)作成
- Webアプリを開発する際の必要な調査
  - 外部APIの把握

## ロードマップ
アジャイル開発に則ってスケージュールを組む。
スプリントを1週間に設定して、1カ月後の10/18を最終期限とする(4週間)

| sprint |タスク|
|:---------:|:---:|
|sprint1(9/20 ~ 9/27)|要件定義・ワイヤフレーム・環境構築・技術スタック図・クラス図・アクティビティ図|
|sprint2(9/28 ~ 10/4)|開発|
|sprint3(10/5 ~ 10/11)|開発|
|sprint4(10/12 ~ 10/18)|調整・リリース|

### sprint1 タスク
- [x] 要件定義
- [x] ワイヤフレーム
- [ ] コンポーネントの把握
  - [参考](https://zenn.dev/overflow_offers/articles/20220523-component-design-best-practice)サイト
- [x] アクティビティ図
- [x] クラス図
  - [ ] YouTube Data APIクラス追加
- [ ] ER図
- [ ] 技術スタック
- [ ] 環境構築

## 調査項目
- [x] emailでの登録だとYouTubeプレイリストは使用できなさそう

YouTube Data APIでの認証では、APIキーでの認証とOAuth2での認証がある。
- APIキー認証
  - 公開されているデータを取得することができる
- OAuth2認証
  - ユーザーのYouTubeアカウントに関連付けされたデータを取得することができる

YouTube Dataを取得するクラスを検討する

- [ ] 要約で使用予定の生成AIの比較
- [ ] 技術スタック

## マイルストーン
ポートフォリオ作成