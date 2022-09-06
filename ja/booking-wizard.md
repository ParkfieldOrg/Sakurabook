# Booking Wizard

このガイドは顧客のための予約フローに焦点をあてています。予約が作成され、カートに入れられるまでにいくつかのステップがあります。

![Alt text](../img/Screenshot%202022-09-01%20at%2011.28.15.png?raw=true "Sakurabook Wizard in Store")

## 内容

- [サービス予約](#サービス予約)
- [レンタルスペース予約](#レンタルスペース予約)
- [予約の状態](#予約の状態)

## サービス予約

1. Shopify ストアのサービス商品ページが表示されたら、右側に Sakurabook Booking Wizard が表示されます。**サービス予約**のユースケースなので、一番最初のステップはスタッフを選択することです。各スタッフのプロフィール写真、名前、経歴が表示されるはずです。右側の矢印でスタッフを切り替えたり、プロフィール写真をクリックしたりすることができます。スタッフが選択されたら、`Next`ボタンをクリックしてください。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.07.16.png?raw=true "Sakurabook Wizard Staff Selection")

2. スタッフを選択したら、次は日付と場所を選択します。具体的な日を選択します。1 回目のクリックで開始日、2 回目のクリックで終了日です。数時間のような短期間の予約の場合は当日をクリックしてください。次に、場所のドロップダウンを使用して場所を選択します。また、下に詳細な料金情報が表示されています。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.07.44.png?raw=true "Sakurabook Wizard Location and Date Selection")

3. 曜日と場所を選択すると、このようになります。`Next`ボタンをクリックします。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.04.png?raw=true "Sakurabook Wizard Location and Date Selected")

4. 次に、時間を指定します。ドロップダウンで開始時刻と終了時刻を選択します。また、下には事前に計算された価格が表示されています。準備ができたら`Next`ボタンをクリックしてください。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.24.png?raw=true "Sakurabook Wizard Time Selection")

5. これが概要画面です。お客様はここで、サービスのいくつかの AddOn をカートに追加することもできます。AddOn を追加すると、サマリー価格が自動的に更新されます。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.42.png?raw=true "Sakurabook Wizard Summary")

6. AddOn が選択された後の更新されたビュー。すべてが完了したら、`Checkout`ボタンをクリックしてください。このボタンはカートにつながります。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.48.png?raw=true "Sakurabook Wizard Summary With AddOn")

7. 次は、カートからのチェックアウト、注文の確認、支払いです。これは通常の Shopify のフローです。

## レンタルスペース予約

1. **レンタルスペース予約**のユースケースは、まず宿泊日を選択します。特定の日を選択し、最初のクリックは開始日、2 回目のクリックは終了日です。数時間のような短期間のオンライン予約の場合は、同じ日をクリックします。その後、場所のドロップダウンを使用して場所を選択します。また、下に詳細な料金情報が表示されています。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.00.35.png?raw=true "Sakurabook Wizard Date Selection")

2. 曜日と場所を選択すると、このようになります。`Next`ボタンをクリックします。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.01.21.png?raw=true "Sakurabook Wizard Date Selected")

3. 次に、時間を指定します。ドロップダウンで開始時刻と終了時刻を選択します。また、下には事前に計算された価格が表示されています。準備ができたら`Next`ボタンをクリックしてください。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.02.10.png?raw=true "Sakurabook Wizard Time Selection")

4. これが概要画面です。お客様は、レンタル用のいくつかの AddOn をカートに追加することもできます。AddOn を追加すると、サマリー価格が自動的に更新されます。この例では、レンタルスペースに利用可能な AddOn はありません。

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.03.12.png?raw=true "Sakurabook Wizard Summary")

## 予約の状態

各予約には全体で 4 つの可能な状態があります。それは、顧客が上記のプロセスを終了したステップによって異なります。

予約の`PENDING`状態は、顧客がカートに予約を残すときに発生します。彼らはまだ予約のために支払っていません。これは予約された日/時間を 1 時間ブロックする状態です。

予約の`ABBANDONED`状態は、顧客がカートに予約を残したときに発生します。彼らはまだ予約のために支払っていません。これは 1 時間以上経過しているため、予約された曜日/時間をブロックしない状態です。

`REJECTED`ステートは、予約が正常に支払われたが、他の競合する予約があるときに発生します。その場合、予約は拒否されます。この場合、私たちはマーチャントと顧客の両方に通知メールを送信し、マーチャントのサポートは、この状況を整理するために顧客に到達する必要があります。

`CONFIRMED`ステートは、予約が正常に支払われたときに発生します。ここでは、マーチャントが何らかの変更を行うまで、例えば顧客とサポートチームとのコミュニケーションの後、最終的に予約された曜日/時間をブロックします。

---

➡ 次はどうする？詳しくは[課金プラン](./billing-plans.md)をご覧ください。