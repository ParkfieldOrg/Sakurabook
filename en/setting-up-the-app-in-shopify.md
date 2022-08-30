# Setting Up the App in Shopify

This section will help you with the installation of the Sakurabook app into your Shopify store, setting it up, and adding it to your Shopify theme. Let's do it step by step.

## Contents

- [Installation](#installation)
- [Sakurabook Admin Setup](#sakurabook-admin-setup)
- [Sakurabook Booking Wizard Setup](#sakurabook-booking-wizard-setup)

## Installation

📌 This will be updated once the app is successfully reviewed and published in the Shopify app store.

1. Go to [Sakurabook page](https://apps.shopify.com/google?surface_detail=recommended-for-you&surface_inter_position=2&surface_intra_position=5&surface_type=home) in the Shopify app store.

   ![Alt text](../img/?raw=true "Sakurabook App Store")

2. Press the `Add app` button in the top left part of the page.

3. Check the scopes of the app to which you are giving us consent to, it's in the **This app needs to** section. If you agree with the required access scopes, click the `Install app` button.

4. After that, you will be redirected to the Sakurabook admin console and you will see the Sakurabook app in the **Apps** section of the left main menu of Shopify Admin.

5. You should find yourself on the **Welcome to Sakurabook app!** screen. This is the first screen of our onboarding guide.

   ![Alt text](../img/?raw=true "Welcome to Sakurabook app!")

💡 **Troubleshooting**: If anything goes wrong, get in touch with our [Support](https://sakurabook.app/pages/support), please. We are as available as possible and really keen to help.

## Sakurabook Admin Setup

Once you successfully installed the app into your Shopify store, you should be able to access the app in the main left menu of Shopify admin under the **Apps** section together with all the other apps you have installed.

The next step is to set up everything in Sakurabook Admin to be able to offer your products for reservation.

📌 There is a prerequisite of having your products already created in the Shopify Admin Products section (https://your-store-name.myshopify.com/admin/products). Please make sure you do this before you start with this guide.

1. Go to Shopify Admin Products (/admin/products) section and add appropriate tags to products you want to offer within the Sakurabook reservation system. See the table below.

   | Product Tag | Rental space reservations | Service reservations | Description                                                                                                                       |
   | ----------- | ------------------------- | -------------------- | --------------------------------------------------------------------------------------------------------------------------------- |
   | `Rental`    | x                         |                      | Add this tag to product if you want to import it into Sakurabook as Rental product.                                               |
   | `Service`   |                           | x                    | Add this tag to product if you want to import it into Sakurabook as Service product.                                              |
   | `AddOn`     | x                         | x                    | Add this tag to product together with Rental/Service tag if you want to offer it as add on for Rental space/Service reservations. |

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.44.52.png?raw=true "Shopify Product Tags")

2. Go back to the Sakurabook app (Apps on the left main menu in Shopify Admin).

3. Walk through the Onboarding guide. Make sure that you read everything properly. But no worries, if you miss something, you can trigger the Onboarding guide any time in the future (the link is in the footer).

   - Welcome to Sakurabook app!
   - Prerequisites
   - 2 reservation types
   - Dashboard view
   - Connect app to theme
   - Click the `Finish` button

   ![Alt text](../img/?raw=true "Sakurabook Onboarding Finish")

4. Now you appeared on the Use case selection screen. You can select either **Rental space reservation** or **Service reservation**. Make a wise choice, it has to suit your business. This cannot be changed in the future. After you select the right use case, click on `Import` button.

   📌 Yes, it cannot be change, but if you really need to change the use case, please get in touch with the support and we'll make a way to fix it for you.

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.36.48.png?raw=true "Sakurabook Use Case Selection ")

5. New modal window appeared. You can select products to be imported into the Sakurabook app. Select the products you want to see in the app by clicking the checkboxes on the left side. Once you are done, click the `Add` button.

   📌 If you select **Rental space reservation** use case, you should only see products with the `Rental` tag in the import selector. If you select **Service reservation**, you will see only products with the `Service` tag. AddOns can be imported later.

   📌 Have you selected **Rental space reservation**? Skip to step 8.

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.38.48.png?raw=true "Sakurabook Import Products")

6. Since you selected **Service reservation**, you have now the option to create your first staff member. Click on the `Add staff` button and find yourself on the Staff creation screen.

   ![Alt text](../img/Screenshot%202022-08-29%20at%2010.40.48.png?raw=true "Sakurabook Add Member")

7. Please check out the detailed [Create Staff]() guide, click **Save** in the top right corner. Congratulations. You have created your first staff. Then click on **Dashboard** in the top navigation menu.

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.56.35.png?raw=true "Sakurabook Edit Staff")

8. Welcome to Sakurabook Dashboard! This is where you can see and manage all your bookings. Check the [Manage Bookings]() guide for more details.

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.51.06.png?raw=true "Sakurabook Dashboard")

9. Now we refer to [Usage Guides](usage-guides.md) where you can find details about setting up prices for your products, managing bookings on the dashboard, setting up and changing options of your staff, rental spaces, and services, and changing the location of your business and all the other staff.

10. The very last step on our Sakurabook Admin Setup guide is a selection of your Billing plan. Navigate to Settings (top menu) and click on the `Manage plan` button under the Billing section. You've got several options, see details about [Billing plans](billing-plans.md).

    📌 Each of the billing plans is limited by the number of paid bookings you can create per month/year. For example, the **Standard plan** with a monthly subscription is only for **$19.90** and you can create **6.000** paid bookings. Moreover, when you subscribe for the first time, you'll get a **14 day** free trial. You can test everything and decide if Sakurabook is the right app for you.

    ![Alt text](../img/?raw=true "Sakurabook Billing")

## Sakurabook Booking Wizard Setup

Sakurabook app is installed in your Shopify store and you've successfully finished the previous [guide](#sakurabook-booking-wizard-setup). Now let's have a look at how to add the Sakurabook Booking Wizard into your customer-facing storefront, also called Shopify Theme.

📌 There is one prerequisite to be able to add Booking Wizard into your storefront. You need to have an Online Store sales channel installed in your store.

1. Go to **Online Store** in the left main menu under **Sales channels** section and click on **Theme**. It depends on what theme you have selected, but you should see the **Current theme** section. Click on the `Customize` button.

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.36.48.png?raw=true "Shopify Theme Customize")

2. Now you find yourself in the Shopify Theme customization tool where you can fully set up your online store. In the top middle selection box with Templates, search the Products section which is the place where **Sakurabook App block** (Booking Wizard) needs to be placed.

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.37.12.png?raw=true "Shopify Theme Products")

3. In the left main menu, you should now see the page sections. Drop down the **Product information** section and clock on the `Add block` button. A new window pops up and it contains two lists, THEME BLOCKS, and APPS. Under the APPS list, you should see **Booking Wizard** from **sakurabook** app. Click on it and it will be added to your theme. The app should load itself even in the customization tool. All is now set. Click on the three dots menu in the top left corner of the screen and go to **View** to check it out in your customer-facing storefront.

   ![Alt text](../img/Screenshot%202022-08-28%20at%2010.37.30.png?raw=true "Shopify Theme Sakurabook App Block")

---

➡ What's next? Move to [Usage Guides](./usage-guides.md).
