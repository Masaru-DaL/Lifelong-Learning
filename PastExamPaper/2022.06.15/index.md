# セキュリティ
直近3年分過去問

- point 55

## 電子メールをドメインAの送信者がドメインBの宛先に送信するとき，送信者をドメインAのメールサーバで認証するためのものはどれか。
- 電子メールの送信プロトコル
  - SMTP
    - メールの投稿者の認証をする仕組みがない
  - SMTP-AUTH
    - SMTPを拡張し、ユーザ認証機能を追加した仕様


## OSI基本参照モデルのネットワーク層で動作し，"認証ヘッダ(AH)"と"暗号ペイロード(ESP)"の二つのプロトコルを含むものはどれか。
- IPsec(IP Security)
  - IP(Internet Protocol)を拡張してセキュリティを高めたプロトコル
  - 改ざんの検知、通信データの暗号化、送信元の認証などの機能を**ネットワーク層**レベルで提供する


## セキュアブートの説明はどれか。
- ブート
  - 起動
- セキュアブート
  - コンピュータの起動時にOS起動ファイルやドライバのディジタル署名を検証し、起動プロセスを認証することで、不正なプログラムの実行を未然に防止する仕組み


## WPA3はどれか。
- WPA3
  - Wi-Fi Protected Access 3
  - 無線LANのセキュリティプロトコル


## 組織的なインシデント対応体制の構築や運用を支援する目的でJPCERT/CCが作成したものはどれか。
- CSIRTマテリアル
  - 組織的なインシデント対応体制である「組織内CSIRT」の構築を支援する目的で作成されたガイドライン


## 楕円曲線暗号の特徴はどれか。
- 楕円曲線暗号
  - 楕円曲線の点の演算を用いた公開鍵暗号方式
  - 計算量の多さを安全性の根拠とし、同じ強度を想定した場合、RSAより鍵長を短くできる利点がある


## 1台のファイアウォールによって，外部セグメント，DMZ，内部セグメントの三つのセグメントに分割されたネットワークがあり，このネットワークにおいて，Webサーバと，重要なデータをもつデータベースサーバから成るシステムを使って，利用者向けのWebサービスをインターネットに公開する。インターネットからの不正アクセスから重要なデータを保護するためのサーバの設置方法のうち，最も適切なものはどれか。ここで，Webサーバでは，データベースサーバのフロントエンド処理を行い，ファイアウォールでは，外部セグメントとDMZとの間，及びDMZと内部セグメントとの間の通信は特定のプロトコルだけを許可し，外部セグメントと内部セグメントとの間の直接の通信は許可しないものとする。
- Webサーバは外部セグメントからアクセスを受け付ける。
  - 被害発生時の影響範囲を最小限に抑えるためにはDMZに設置すべき。
- DBサーバはWebサーバを介してアクセスされるため、外部セグメントから直接アクセスさせる必要がない
  - 内部セグメントに設置する


## 不正が発生する際には"不正のトライアングル"の3要素全てが存在すると考えられている。"不正のトライアングル"の構成要素の説明として，適切なものはどれか。
- 不正のトライアングル
  - 動機・プレッシャー
    - 自己の欲求の達成や問題を解決するためには不正を行うしかないという考えに至った心情のこと
  - 機会
    - 不正を行おうと思えばいつでもできるような職場環境のこと
  - 正当化
    - 自分に都合の良い理由をこじつけて、不正を行う時に感じる「良心の呵責」を乗り越えてしまうこと


## マルウェアの動的解析に該当するものはどれか。
- 動的解析
  - サンドボックス上でプログラムを実際に動作させてその挙動を監視し、その動作を解析すること
- 静的解析
  - 逆アセンブルしたプログラムの命令列を直接読んで、どのような動作をするか解析すること


## メッセージにRSA方式のディジタル署名を付与して2者間で送受信する。そのときのディジタル署名の検証鍵と使用方法はどれか。
ディジタル署名の検証鍵は「送信者の公開鍵」であり、その使用方法は「受信者がディジタル署名からメッセージダイジェストを算出する」ことです。


## JIS Q 27000:2014(情報セキュリティマネジメントシステム－用語)における真正性及び信頼性に対する定義a～dの組みのうち，適切なものはどれか。
- 真正性
  - 利用者、プロセス、システム、情報などが**主張通り**であることを確実する特性のこと
- 信頼性
  - 情報システムによる処理に欠陥や不具合がなく、期待した処理が**確実に行われている**特性のこと


## JIS Q 27000:2014(情報セキュリティマネジメントシステム－用語)における"リスクレベル"の定義はどれか。
- リスクレベル
  - リスクごとのリスクレベルは、リスク分析で決定される
  - 結果とその起こりやすさの組み合わせとして表現されるリスクの大きさ


## IDSの機能はどれか。
- IDS
  - Intrusion Detection System
  - 侵入検知システム


## リスク対応のうち，リスクファイナンシングに該当するものはどれか。
- リスクファイナンス
  - リスクが顕在化した場合に備えて、損失の補填や対応のための資金確保策を講じること
  - 想定する


## メッセージ認証符号の利用目的に該当するものはどれか。
- メッセージ認証符号
  - 通信コードの改ざん有無を検知し、安全性を保証するために通信データから生成する固定長のコード
  - 目的は**改ざんの検知**


## CAPTCHAの目的はどれか。
- CAPTCHA
  - 人間によるアクセスかコンピュータによるアクセスかを判別する目的でWebサイトなどに組み込まれる仕組み


## パスワードリスト攻撃の手口に該当するものはどれか。
- パスワードリスト攻撃
  - 複数サイトで同一のID・パスワードの組み合わせを使用している利用者が多いという傾向を悪用し、あるサイトに対する攻撃などによって得られたIDとパスワードのリストを用いて別のサイトへの不正ログインを試みる攻撃


## 自社の中継用メールサーバで，接続元IPアドレス，電子メールの送信者のメールアドレスのドメイン名，及び電子メールの受信者のメールアドレスのドメイン名から成るログを取得するとき，外部ネットワークからの第三者中継と判断できるログはどれか。ここで，AAA.168.1.5 と AAA.168.1.10 は自社のグローバルIPアドレスとし，BBB.45.67.89 と BBB.45.67.90 は社外のグローバルIPアドレスとする。a.b.c は自社のドメイン名とし，a.b.d と a.b.e は他社のドメイン名とする。また，IPアドレスとドメイン名は詐称されていないものとする。
接続元IPアドレス，電子メールの送信者のドメイン名及び電子メールの受信者のドメイン名のすべて自社と関係ないログが第三者中継であると判断できます。


## ファジングで得られるセキュリティ上の効果はどれか。
ファジング(fuzzing)とは、検査対象のソフトウェア製品に「ファズ（英名：fuzz）」と呼ばれる問題を引き起こしそうなデータを大量に送り込み、その応答や挙動を監視することで(未知の)脆弱性を検出する検査手法です。


## SIEM(Security Information and Event Management)の機能はどれか。
SIEM(シーム)は、OS、データベース、アプリケーション、ネットワーク機器など多様なソフトウェアや機器が出力する大量のログデータを分析し、異常があった場合に管理者に通知したり対策を知らせたりする仕組みです。日本語ではセキュリティ情報およびイベント管理と訳されます。


## ファイルの提供者は，ファイルの作成者が作成したファイルAを受け取り，ファイルAと，ファイルAにSHA-256を適用して算出した値Bとを利用者に送信する。そのとき，利用者が情報セキュリティ上実現できることはどれか。ここで，利用者が受信した値Bはファイルの提供者から事前に電話で直接伝えられた値と同じであり，改ざんされていないことが確認できているものとする。
本問で登場する「SHA-256」は入力値から256ビットの文字列を生成するハッシュ関数です。


## 公衆無線LANのアクセスポイントを設置するときのセキュリティ対策と効果の組みのうち，適切なものはどれか。
本肢は無線LANのプライバシセパレータ機能とその効果についての組みです。
**プライバシーセパレータは、同一の無線LANに接続された子機同士の通信を禁止する機能です**。店舗内Wi-fiや公衆無線LANサービスのように見知らぬ他人同士が同じ無線LANに接続する場面で、利用者のセキュリティ保護のために設定されます。