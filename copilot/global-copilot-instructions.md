テスト作成時に以下の条件を加える。ただし別途別の指示をした場合を除く
* Clock.fixedで固定時刻を使用（Asia/Tokyoタイムゾーン）
* 日時の初期化は文字列を元にparseで行う
* Clockの初期化はInstantで行う
* AssertJを使ったアサーション
* 英語のメソッド名（resolveArgument_returnsCardStore_whenValid形式）
* 適切なモック設定で依存関係を制御
* 依存サービス・リポジトリ: @Mock
* model配下のクラス: new で実インスタンス
* セットアップ・実行・検証ブロック間に空行
* 見通しの良いレイアウト
