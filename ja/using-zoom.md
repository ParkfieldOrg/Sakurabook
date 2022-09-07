# Zoom を使用する

[Zoom 連携](./connect-zoom.md)連携に成功すると、オンラインサービスや予約の利用ができるようになります。このガイドでは、Zoom 統合を利用するための流れや注意点を説明します。

📌 また、2 つのビデオガイドを用意しましたので、Youtube の[Sakurabook チャンネル](https://www.youtube.com/channel/UCzs8kviSrLufN3ipRIeGc3Q/videos)から、お気軽にご覧ください。

## 目次

- [スタッフのテレビ会議](#スタッフのテレビ会議)
- [オンライン Zoom 予約](#オンライン-zoom-予約)
- [ダッシュボードからの手動予約](#ダッシュボードからの手動予約)
- [Booking Wizard](#booking-wizard)

## スタッフのテレビ会議

[スタッフ作成](./create-staff.md#videoconferencing)では、お客様にオンライン Zoom 会議を提供するために、Zoom 接続の準備が必要であることを説明しました。ここでは、Zoom が正しく接続されているときとされていないときの様子をご覧いただけます。

![Alt text](../img/Screenshot%202022-09-07%20at%2010.29.05.png?raw=true "Sakurabook Videoconferencing Zoom Connected")

![Alt text](../img/Screenshot%202022-08-30%20at%2013.28.16.png?raw=true "Sakurabook Videoconferencing Zoom Disconnected")

## オンライン Zoom 予約

オンライン Zoom 予約を作成するには、2 つの方法があります。1 つ目はダッシュボードから手動で予約を作成する方法です。[予約の管理](./manage-booking.md)ガイドを参照してください。もう一つは Shopify ストアと Sakurabook 予約ウィザードを使用する方法です。[Bbooking Wizard](./booking-wizard.md) ガイドを参照してください。

どちらの場合も、作成時にオンラインズームロケーションを選択する必要があります。

## ダッシュボードからの手動予約

❗️ このマニュアルは、Shopify Admin コンソール内で Sakurabook Admin にアクセスできるマーチャントとそのスタッフ向けのものです。お客様はこの方法で予約を作成することはできません。

1. Sakurabook のダッシュボードサイトへ移動します。

   ![Alt text](../img/Screenshot%202022-08-31%20at%200.59.53.png?raw=true "Sakurabook Booking Dashboard")

2. 予約を作成したいカレンダーをクリックします。

3. 必要事項を入力し、「スタッフ」「サービスタイプ」が正しいことを確認します。オンラインで予約する場合は、**Zoom**の場所を選択してください。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.01.47.png?raw=true "Sakurabook Booking Create")

4. `Create`ボタンをクリックすると、予約が作成され、ダッシュボードに表示されます。

   ![Alt text](../img/Screenshot%202022-08-31%20at%201.01.33.png?raw=true "Sakurabook Booking Created")

5. あなたの顧客は Shopify から請求書メールを受け取り、購入を完了します。その後、顧客はいくつかの簡単なステップで注文の支払いを行う必要があります。このフローは、いくつかのショップ用にカスタマイズすることができます。以下は通常のステップです。

   - メールに記載されている`Complete your purchase`ボタンをクリックします。
   - お客様の情報を入力し、次のページに進みます。
   - 支払い情報を入力し、テスト注文のため[Bogus Gateway](https://help.shopify.com/en/manual/checkout-settings/test-orders)を使用します。次に、`Pay now`ボタンをクリックして注文の代金を支払います。
   - 確認ページが表示されます。

6. 予約が支払われた後、あなたの顧客は Shopify から予約が正常に支払われたという情報を含む注文確認メールを受け取ります。

7. 同時に、サクラブックのアプリから直接配信される予約確認メールももう 1 通あります。このメールには、場所欄にお客様の**Zoom join url**も記載されています。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Zoom Confirmation")

8. 最後のステップは、Sakurabook ダッシュボードに戻り、最近作成した予約の詳細を開き、`Zoom staff link`と`Zoom customer link`の両方が存在することを確認することです。`Zoom staff link`はオンラインイベントの開始 URL で、後者はオンラインイベントへの参加 URL です。スタッフが`Zoom staff link`を用意していることを確認してください。

   📌 これらのリンクは、あなたが顧客に代わって予約の詳細を変更するたびに更新されます。予約削除の場合も同様です。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2012.18.28.png?raw=true "Sakurabook Booking Detail Zoom")

9. 実はもう一つ詳細があります。[Google カレンダー](./connect-google-calendar.md)も接続している場合、Google カレンダーのイベントの場所にも`Zoom customer link`を見ることができます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.23.33.png?raw=true "Sakurabook Google Calendar event with Zoom link")

## Booking Wizard

❗️ 本書は、主にお客様向けに作成したものです。

1. [Booking Wizard](./booking-wizard.md#service-reservation)内のサービス予約の手順に従ってください。オンライン予約の際は、Zoom Location を選択することを忘れないでください。

2. 予約が支払われた後、あなたの顧客は Shopify から予約が正常に支払われたという情報を含む注文確認メールを受け取ります。

3. 同時に、サクラブックのアプリから直接配信される予約確認メールももう 1 通あります。このメールには、場所欄にお客様の**Zoom join url**も記載されています。

   📌 予約更新のたびに**Zoom join url**が更新されます。その後、サクラブックの予約更新メールが顧客に配信されます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Zoom Confirmation")

4. もう一つ、詳細があります。[Google カレンダー](./connect-google-calendar.md)も接続している場合、Google カレンダーのイベントの場所にも`Zoom customer link`が表示されます。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.23.33.png?raw=true "Sakurabook Google Calendar event with Zoom link")

---

➡ 次は何をする？[Booking Wizard](./booking-wizard.md)のガイドに進みます。
