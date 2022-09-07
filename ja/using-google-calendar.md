# Google カレンダーの活用

[Google カレンダーの接続](./connect-google-calendar.md)統合に成功すると、SSakurabook で Google カレンダーの機能を利用することができるようになります。本ガイドでは、その流れや期待することをご紹介しています。

📌 Youtube の[Sakurabook チャンネル](https://www.youtube.com/channel/UCzs8kviSrLufN3ipRIeGc3Q/videos)にて、2 つのビデオガイドも用意していますので、ぜひご覧ください。

予約を作成し、Google カレンダーの中でそれを見つけるには 2 つの方法があります。1 つ目はダッシュボードから手動で予約を作成する方法です。[予約の管理](./manage-bookings.md) ガイドを参照してください。もう一つは Shopify ストアと Sakurabook 予約ウィザードを使用する方法です。[Booking Wizard](./booking-wizard.md) ガイドを参照してください。

## 目次

- [ダッシュボードからの手動予約](#ダッシュボードからの手動予約)
- [Booking Wizard](#booking-wizard)

## ダッシュボードからの手動予約

❗️ このマニュアルは、Shopify Admin コンソール内で Sakurabook Admin にアクセスできるマーチャントとそのスタッフ向けのものです。お客様はこの方法で予約を作成することはできません。

1. Sakurabook のダッシュボードサイトにアクセスします。

   ![Alt text](../img/Screenshot%202022-08-31%20at%200.59.53.png?raw=true "Sakurabook Booking Dashboard")

2. 予約を作成したいカレンダーをクリックします。

3. 必要事項を入力し、「スタッフ」「サービスタイプ」が正しいことを確認します。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.01.47.png?raw=true "Sakurabook Booking Create")

4. `Create`ボタンをクリックすると、予約が作成され、ダッシュボードに表示されます。

   ![Alt text](../img/Screenshot%202022-08-31%20at%201.01.33.png?raw=true "Sakurabook Booking Created")

5. あなたの顧客は Shopify から請求書メールを受け取り、購入を完了します。その後、顧客はいくつかの簡単なステップで注文の支払いを行う必要があります。このフローは、いくつかのショップ用にカスタマイズすることができます。以下は通常のステップです。

   - メールに記載されている`Complete your purchase`ボタンをクリックします。
   - お客様の情報を入力し、次のページに進みます。
   - 支払い情報を入力し、テスト注文のため[Bogus Gateway](https://help.shopify.com/en/manual/checkout-settings/test-orders)を使用します。その後、`Pay now`ボタンをクリックして注文の支払いをします。
   - 確認ページが表示されます。

6. 予約が支払われた後、あなたの顧客は Shopify から予約が正常に支払われたという情報を含む注文確認メールを受け取ります。

7. 同時に、Sakurabook アプリから直接配信される予約確認メールももう 1 通あります。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Confirmation Email")

8. 最後に、Sakurabook アプリに接続した[Google カレンダー](https://calendar.google.com/)を確認します。スタッフまたはスペースの最初の予約であれば、左側のメニューに新しく作成されたカレンダーが表示されているはずです。スタッフやスペースはそれぞれカレンダーを持っています。これらのカレンダーは、Sakurabook dashboard と同期しています。

   📌 現在、私たちの側では Google カレンダーの変更を反映していません。今後の開発予定です。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2015.49.46.png?raw=true "Sakurabook Google Calendar event")

## Booking Wizard

❗️ 本書は、主にお客様向けに作成したものです。

1. [Booking Wizard](./booking-wizard.md#service-reservation)の手順に従って、予約を行ってください。

2. 予約が支払われた後、あなたの顧客は Shopify から予約が正常に支払われたという情報を含む注文確認メールを受け取ります。

3. 同時に、サクラブックのアプリから直接配信される予約確認メールももう 1 通あります。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2011.17.13.png?raw=true "Sakurabook Email Confirmation")

4. 最後に、お客様は[Google カレンダー](https://calendar.google.com/)をチェックし、時間、場所、スタッフまたはスペースの詳細が記載された招待状を見ることになります（予約内容による）。

   📌 現在、弊社側で Google カレンダーの変更を反映させていません。今後の開発予定です。

   ![Alt text](../img/Screenshot%202022-09-07%20at%2015.54.53.png?raw=true "Sakurabook Google Calendar event")

---

➡ 次は何をする？[Zoom を接続する](./connect-zoom.md)ガイドへ移動します。
