# Shopify にアプリをセットアップする

このセクションでは、Sakurabook アプリの Shopify ストアへのインストール、設定、Shopify テーマへの追加について説明します。ステップバイステップで行っていきましょう。

## 目次

- [インストール](#インストール)
- [Sakurabook Admin セットアップ](#sakurabook-admin-セットアップ)
- [Sakurabook Booking Wizard セットアップ](#sakurabook-booking-wizard-セットアップ)

## インストール

📌 **TODO** アプリが正常に審査され、Shopify アプリストアで公開されると、この内容が更新される予定です。

1. Shopify アプリストアの[Sakurabook ページ](https://apps.shopify.com)にアクセスします。

   ![Alt text](../img/?raw=true "Sakurabook App Store")

2. ページ左上の`Add app`ボタンを押します。

3. 同意するアプリのスコープを確認します。それは **This app needs to** セクションにあります。必要なアクセススコープに同意する場合は、`Install app`ボタンをクリックします。

4. その後、Sakurabook の管理コンソールにリダイレクトされ、Shopify Admin の左メインメニューの**Apps**に Sakurabook アプリが表示されていることを確認してください。

5. **Welcome to Sakurabook app!**の画面が表示されるはずです。これは、オンボーディングガイドの最初の画面です。

   ![Alt text](../img/?raw=true "Welcome to Sakurabook app!")

💡 **Troubleshooting**: 何か問題が発生した場合は、私たちの[Support](https://app.sakurabook.app/pages/support)に連絡してください。私たちは可能な限り対応し、お手伝いします。

## Sakurabook Admin セットアップ

アプリを Shopify ストアに正常にインストールしたら、Shopify 管理画面の左メインメニューの**Apps**セクションから、インストールした他のアプリと一緒にアプリにアクセスできるようになるはずです。

次のステップでは、Sakurabook Admin で商品を予約提供できるようにすべてを設定します。

📌 Shopify Admin の商品セクション(https://your-store-name.myshopify.com/admin/products)に商品が既に作成されていることが前提条件となります。このガイドを始める前に、必ず行ってください。Shopifyのガイド[Adding and updating products](https://help.shopify.com/en/manual/products/add-update-products)も参照してください。

1. Shopify Admin products (/admin/products) セクションに移動し、Sakurabook 予約システム内で提供したい製品に適切なタグを追加します。下表をご参照ください。

   | 製品タグ  | レンタルスペースの予約 | サービス予約 | 商品説明                                                                                                                  |
   | --------- | ---------------------- | ------------ | ------------------------------------------------------------------------------------------------------------------------- |
   | `Rental`  | x                      |              | レンタル商品としてさくらブックに取り込む場合は、このタグを追加してください。                                              |
   | `Service` |                        | x            | サービス商品としてさくらブックに取り込む場合は、このタグを追加してください。                                              |
   | `AddOn`   | x                      | x            | レンタルスペース/サービス予約のアドオンとして提供する場合、このタグを Rental/Service タグと一緒に商品に追加してください。 |

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.44.52.png?raw=true "Shopify Product Tags")

2. Sakurabook アプリ（Shopify Admin の左メインメニューの Apps）に戻る。

3. オンボーディングガイドに目を通す。すべてきちんと読んだかどうか確認してください。もし何か見逃してしまっても、今後いつでもオンボーディングガイドを起動することができます（リンクはフッターにあります）ので、ご安心ください。

   - さくらブックアプリへようこそ
   - 前提条件
   - 2 種類の予約
   - ダッシュボード表示
   - テーマとアプリを接続する
   - `Finish`ボタンをクリック

   ![Alt text](../img/?raw=true "Sakurabook Onboarding Finish")

4. 使用用途の選択画面が表示されました。**レンタルスペース予約**と**サービス予約**のいずれかを選択できます。あなたのビジネスに合った、賢い選択をしてください。これは将来的に変更することはできません。正しいユースケースを選択したら、`Import`ボタンをクリックします。

   📌 はい、変更できませんが、どうしてもユースケースを変更したい場合は、サポートにご連絡いただければ、修正する方法をお作りします。

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.36.48.png?raw=true "Sakurabook Use Case Selection ")

5. 新しいモーダルウィンドウが表示されました。さくらブックアプリに取り込む商品を選択することができます。左側のチェックボックスをクリックして、アプリで表示したい商品を選択します。完了したら、`Add`ボタンをクリックします。

   追加する商品がない場合は、正しいタグを商品に追加する方法を説明したステップ 1.に戻ってください。

   📌 使用例として**レンタルスペース予約**を選択した場合、インポートセレクタには`Rental`タグの付いた商品のみが表示されます。**サービス予約**を選択した場合、`Service`タグを持つ商品のみが表示されます。AddOn は後からインポートすることができます。

   📌 **レンタルスペース予約**を選択しましたか？手順 8 へ進みます。

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.38.48.png?raw=true "Sakurabook Import Products")

6. **サービス予約**を選択したため、最初のスタッフを作成するオプションがあります。`Add staff`ボタンをクリックすると、スタッフ作成画面が表示されます。このステップを`Skip`することもできます。ステップ 8 へお進みください。

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.40.48.png?raw=true "Sakurabook Add Staff")

7. 詳細な[スタッフの作成](./create-staff.md)のガイドを確認し、右上の`Save`をクリックしてください。おめでとうございます。これで、最初のスタッフが作成されました。次に、上部ナビゲーションメニューの`Dashboard`をクリックします。

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.56.35.png?raw=true "Sakurabook Edit Staff")

8. サクラブック ダッシュボードへようこそ! ここでは、すべての予約を確認、管理することができます。詳しくは[予約の管理](./manage-bookings.md)のガイドをご確認ください。

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.51.06.png?raw=true "Sakurabook Dashboard")

9. ここで、商品の価格設定、ダッシュボードでの予約管理、スタッフ、レンタルスペース、サービスのオプション設定と変更、ビジネスと他のすべてのスタッフの所在地変更についての詳細が記載されている [使い方ガイド](usage-guides.md) を参照します。

10. Sakurabook AAdmin セットアップガイドの最後のステップは、課金プランの選択です。設定(トップメニュー)に移動し、課金セクションの下にある `Manage plan` ボタンをクリックします。いくつかのオプションがありますので、詳しくは[課金プラン](./billing-plans.md)をご覧ください。

    📌 各課金プランには、月/年に作成できる有料ブッキングの数が制限されています。例えば、**スタンダードプラン**の月額課金制は、**19.90 ドル**で、**6.000**件の有料予約を作成することができます。さらに、初回登録時には、**14 日間**の無料トライアルが提供されます。さくらブックがあなたにぴったりのアプリかどうか、すべてを試してみてください。

    ![Alt text](../img/?raw=true "Sakurabook Billing")

## Sakurabook Booking Wizard セットアップ

Shopify ストアに Sakurabook アプリがインストールされ、前回の[ガイド](#sakurabook-admin-セットアップ)が無事終了しましたね。それでは、Shopify Theme とも呼ばれる顧客向けストアに Sakurabook Booking Wizard を追加する方法を見てみましょう。

📌 ストアフロントにブッキングウィザードを追加できるようにするには、前提条件が 1 つあります。オンラインストアの販売チャンネルがあなたのストアにインストールされている必要があります。

📌 現在、以下のテーマをサポートしています。[Dawn](https://themes.shopify.com/themes/dawn/styles/default), [Sense](https://themes.shopify.com/themes/sense/styles/default), [Colorblock](https://themes.shopify.com/themes/colorblock/styles/default), [Refresh](https://themes.shopify.com/themes/refresh/styles/default), [Studio](https://themes.shopify.com/themes/studio/styles/default) と [Craft](https://themes.shopify.com/themes/craft/styles/default). 予約ウィザードは他の多くのテーマでも動作するはずですが、すべてのテーマがテストされたわけではないので、ここではすべてをリストアップしていません。いくつかのスタイルは、例えば、メインカラーやフォントなど、テーマ自体から継承されています。

📌 Sakurabook チームは、このアプリのために新しいテーマを提供する予定です。両方のユースケースに対応したものになる予定です。

💡 **Troubleshooting**: テーマの設定に何か問題がある場合は、私たちの[Support](app.https://sakurabook.app/pages/support)に連絡してください。

1. 左のメインメニューの **Sales channels** の下にある **Online Store** に行き、 **Theme** をクリックします。選択したテーマによって異なりますが、**現在のテーマ**セクションが表示されているはずです。カスタマイズ]ボタンをクリックします。

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.36.48.png?raw=true "Shopify Theme Customize")

2. Shopify のテーマカスタマイズツールでオンラインストアを設定することができます。テンプレート]の上部中央の選択ボックスで、**Sakurabook App block** (Booking Wizard)を配置する必要がある場所である[製品]セクションを検索します。

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.37.12.png?raw=true "Shopify Theme Products")

3. 左のメインメニューに、ページセクションが表示されているはずです。**Product information**セクションをドロップダウンし、`Add block`ボタンをクリックします。新しいウィンドウがポップアップし、THEME BLOCKS と APPS の 2 つのリストが表示されます。APPS リストの下に、**Sakurabook**アプリの**Booking Wizard**が表示されているはずです。これをクリックすると、テーマに追加されます。カスタマイズツールでも、アプリが勝手に読み込まれるはずです。これですべての設定は完了です。画面左上の 3 つの点のメニューをクリックし、**View**でお客様向けの店頭で確認してください。

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.37.30.png?raw=true "Shopify Theme Sakurabook App Block")

---

➡ 次はどうする？[使い方ガイド](./usage-guides.md)に移動します。
