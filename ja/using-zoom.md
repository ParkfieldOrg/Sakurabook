# Zoom の活用

[Zoom との連携](./connect-zoom.md)に成功すると、オンラインサービスの予約が受付けられるようになります。このガイドでは、Zoom を活用するための流れや注意点をご説明します。

📌 また、2 つのビデオガイドを用意しましたので、Youtube の[Sakurabook チャンネル](https://www.youtube.com/channel/UCzs8kviSrLufN3ipRIeGc3Q/videos)から、お気軽にご覧ください。

## 目次

- [スタッフのテレビ会議](#スタッフのテレビ会議)
- [Zoom によるオンラインサービスの予約](#zoom-によるオンラインサービスの予約)
- [ダッシュボードからの手動予約](#ダッシュボードからの手動予約)
- [予約ウィザード](#予約ウィザード)

## スタッフのテレビ会議

[スタッフ作成](./create-staff.md#videoconferencing)では、お客様にオンライン Zoom 会議を提供するために、Zoom 接続の準備が必要であることを説明しました。ここでは、Zoom が正しく接続されている場合と、されていない場合の判別方法をご覧いただけます。

![Alt text](../img/Screenshot%202022-09-07%20at%2010.29.05.png?raw=true "Sakurabook Videoconferencing Zoom Connected")

![Alt text](../img/Screenshot%202022-08-30%20at%2013.28.16.png?raw=true "Sakurabook Videoconferencing Zoom Disconnected")

## Zoom によるオンラインサービスの予約

Zoom によるオンラインサービスの予約を作成する方法は 2 つあります。1 つ目はダッシュボードから手動で予約を作成する方法です。[予約の管理](./manage-bookings.md)ガイドを参照してください。もう一つは Shopify ストアと Sakurabook 予約ウィザードを使用する方法です。[予約ウィザード](./booking-wizard.md) ガイドを参照してください。

どちらの場合も、作成時にロケーションは Zoom を選択する必要があります。

💡 Zoom のオンラインミーティングを代理でスケジュールしたいですか？Zoom とさくら本を接続したアカウントに、スケジュール権限を設定してください。Zoom の公式ドキュメントの[Scheduling priviledge](https://support.zoom.us/hc/en-us/articles/201362803-Scheduling-privilege)を参照してください。例えば、スタッフのメールアドレスが staff@your-org.com で、Zoom と Sakurabook を admin@your-org.com で接続した場合、staff@your-org.com が admin@your-org.com にスケジュール権限を与えていないと、Zoom ミーティングが作成されませんので、ご確認ください。

## ダッシュボードからの手動予約

❗️ このマニュアルは、Shopify 管理サイトのコンソール内で Sakurabook 管理にアクセスできるマーチャントとそのスタッフ向けのものです。お客様はこの方法で予約を作成することはできません。

1. Sakurabook のダッシュボードサイトへ移動します。

   ![Alt text](../img/Screenshot%202022-08-31%20at%200.59.53.png?raw=true "Sakurabook Booking Dashboard")

2. 予約を作成したいカレンダーをクリックします。

3. 必要事項を入力し、「スタッフ」「サービスタイプ」が正しいことを確認します。オンラインで予約する場合は、**Zoom**の場所を選択してください。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.01.47.png?raw=true "Sakurabook Booking Create")

4. 「`作成`」ボタンをクリックすると、予約が作成され、ダッシュボードに表示されます。

   ![Alt text](../img/Screenshot%202022-08-31%20at%201.01.33.png?raw=true "Sakurabook Booking Created")

5. あなたの顧客は Shopify から請求書メールを受け取り、購入を完了します。その後、顧客はいくつかの簡単なステップで注文の支払いを行う必要があります。このフローは、いくつかのショップ用にカスタマイズすることができます。以下は通常のステップです。

   - メールに記載の「`購入を完了する`」ボタンをクリックします。
   - お客様の情報を入力して次のページに進みます。
   - 支払い情報を入力してダミー購入用のクレジットカード設定[Bogus Gateway](https://help.shopify.com/en/manual/checkout-settings/test-orders)を使用します。その後「`今払う`」ボタンをクリックして注文の支払いをします。
   - 確認ページが表示されます。

6. 予約のお支払い手続き完了後、顧客は Shopify から自動送信される注文確認メールを受け取ります。

7. Shopify から自動送信される注文確認メールとは別に、Sakurabook アプリからは予約内容の詳細が記載されている予約確認メールが自動配信されます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Zoom Confirmation")

8. Sakurabook ダッシュボードに戻り、最近作成した予約の詳細を開き、「`Zoom スタッフリンク`」と「`Zoom カスタマーリンク`」の両方が表示されていることを確認してください。「`Zoom スタッフリンク`」はオンラインイベントの開始 URL です。また、「`Zoom カスタマーリンク`」はオンラインイベントへの参加 URL です。スタッフが「`Zoom スタッフリンク`」を用意していることを確認してください。

   📌 これらのリンクは、あなたが顧客に代わって予約の詳細を変更するたびに更新されます。予約削除の場合も同様です。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2012.18.28.png?raw=true "Sakurabook Booking Detail Zoom")

9. 実はもう一つ詳細があります。[Google カレンダー](./connect-google-calendar.md)も接続している場合、Google カレンダーのイベントの場所にも`Zoom customer link`を見ることができます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.23.33.png?raw=true "Sakurabook Google Calendar event with Zoom link")

## 予約ウィザード

❗️ 本書は、主にお客様向けに作成したものです。

1. [予約ウィザード](./booking-wizard.md#service-reservation)内のサービス予約の手順に従ってください。オンライン予約の際は、Zoom Location を選択することを忘れないでください。

2. 予約が支払われた後、あなたの顧客は Shopify から予約が正常に支払われたという情報を含む注文確認メールを受け取ります。

3. 同時に、サクラブックのアプリから直接配信される予約確認メールももう 1 通あります。このメールには、場所欄にお客様の**Zoom join url**も記載されています。

   📌 予約更新のたびに**Zoom join url**が更新されます。その後、サクラブックの予約更新メールが顧客に配信されます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Zoom Confirmation")

4. もう一つ、詳細があります。[Google カレンダー](./connect-google-calendar.md)も接続している場合、Google カレンダーのイベントの場所にも`Zoom customer link`が表示されます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.23.33.png?raw=true "Sakurabook Google Calendar event with Zoom link")

---

➡ 次は何をする？[予約ウィザード](./booking-wizard.md)のガイドに進みます。
