# test
it is a test project.

2017/12/22
作業内容：
１．APIマッピング記入完了
https://frit.rickcloud.jp/wiki/display/ACPF/Admin+Pages+API+Mapping
２．NTT西川さんの権限説明会
14:00～15:00

メイン
権限制御、登場人物、
https://frit.rickcloud.jp/wiki/display/ACPF/1.5+Display+Control

AWS ActiveDirector　　→　role　role　group
　　group：regionとrole　を管理
  　user　group：userの権限設定
AdminCore　　　　　　　→　個人情報
　　endpointとして権限の管理、Apiとgroup紐付
Composite API Layer　→API　gateway
Admin　　　　　　　　　→　Admin　画面　
Admin S3　　　　　　　　→


問題：
１．全ユーザが権限あるのは　groupの設定はどうなりますか？
２．権限の管理単位、メニュー、コンポーネント、ボタン、項目単位でしょうか。
３．


20171225
作業内容：
1．Sprint2.1　ステータス確認
story:
ACPF-1835	1.5設計完了　　→課題があり、CSVのアップロード先未定
ACPF-1953	1.5設計完了　　→課題があり、キャンセルできるかどうか
ACPF-1992	1.5設計完了
ACPF-1836	2.1設計中　　　→LINA
ACPF-504	ストーリ説明まだしていない　→設計未着手
ACPF-1536	メニュー権限
ACPF-1763	画面項目の表示権限、操作権限
task:
ACPF-1696	task→story	ACPF-1217
ACPF-1697	task→story	ACPF-1216 
ACPF-1701	task→story	ACPF-1218
ACPF-1704	task→story	ACPF-1352
ACPF-1706	task→story	ACPF-1015
ACPF-1695	task→story	ACPF-1217
ACPF-1699	task→story	ACPF-1216
ACPF-1702	task→story	ACPF-1218
ACPF-1705	task→story	ACPF-1352
ACPF-1707	task→story	ACPF-1015 

２．斉藤さんから下記ストーリ説明会
Ariake Commerce PlatformACPF-1927　説明

1]税種類[３種類]：州・連邦・HST
2]画面表示
　・frontとadmin：税の表示は、州と連邦税二つを表示する？
　・詳細画面で表示するのはストーリに明記された、どういう風に表示、表示項目？二種税率？三種税率？→斉藤さんは確認していく！
 　　
　代行注文時、減税できない→原住民には州税を減税、紙で証明で減税になり
　→減税は多分自分申告で行い、ユニクロは現在対象を確認したら、証明書を発行する。お客様はその証明書を持って、自分申告して行く。

問題：
１．減税をしたかどうか、どう確認→CSが電話などやり取り、返金の手続きはAdminシステムの返金ではない、別のルートで支払ます。
２．税金は他の画面に表示しますか？代行注文、返金画面　　　　→斉藤さんは不要と認識して、確認していく！
３．税金表示単位は商品単位で表示するか、合計で表示するか　　→frontに確認する要→確実になり

grooming meeting 連携
１．API　にはS2.1 実装できない。 
２．APIcomposite　情報、設計を聞きます
３．UI、cssデザインはS2.1 から展開
４．S2.1から結合テストの意識、テスト環境、DBレイアウト
５．税金の表示カナダ三種、今後考え、
６．アップロード、キャンセル、宮坂さんに確認、まだ未確認
７．システム外返金、一括返金なし、一つ一つ返金
８．単件の振出指示はなし、５０４は確認中

問題：
１．UI展開？
２．grooming　mtgに　設計できるストーリを確認、planning　mtgに　開発できるストーリを確認
