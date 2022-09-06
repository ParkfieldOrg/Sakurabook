# Booking Wizard

This guide is focused on the booking flow for your customers. There are several steps to be done before the booking is created and put into the cart.

![Alt text](../img/Screenshot%202022-09-01%20at%2011.28.15.png?raw=true "Sakurabook Wizard in Store")

## Contents

- [Service reservation](#service-reservation)
- [Rental space reservation](#rental-space-reservation)
- [Booking states](#booking-states)

## Service reservation

1. After you get to the service product page in the Shopify store, you will see the Sakurabook Booking Wizard on the right side. Since it is a **Service reservation** use case, the very first step is to select staff. You should see a profile photo, name, and some bio for each of the staff. You can use the arrows on the right for switching between staff or simply clicking on the profile photos. Click on the `Next` button when the staff is selected.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.07.16.png?raw=true "Sakurabook Wizard Staff Selection")

2. After you selected your staff, the next step is to select the date and location. Select the specific day, the first click is for the start day and the second click is for the end day. Click on the same day if it is for a short-term reservation like a couple of hours. Then select the location using the location dropdown. You can also see the detailed price information below.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.07.44.png?raw=true "Sakurabook Wizard Location and Date Selection")

3. It looks like this when the day and location are selected. Click on the `Next` button.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.04.png?raw=true "Sakurabook Wizard Location and Date Selected")

4. Next step is to select a specific time. Select start time and end time using the dropdowns. You also see the precalculated price below. Click on the `Next` button when you are ready.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.24.png?raw=true "Sakurabook Wizard Time Selection")

5. This is the summary screen. Customers can also add to their cart some AddOns for the service here. The summary price is automatically updated after you add the AddOn.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.42.png?raw=true "Sakurabook Wizard Summary")

6. Updated view after AddOn is selected. Click on the `Checkout` button after everything is done. This button leads to the cart.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.08.48.png?raw=true "Sakurabook Wizard Summary With AddOn")

7. Next step is to check out from the cart, confirm the order and pay for it. This is a usual Shopify flow.

## Rental space reservation

1. For the **Rental space reservation** use case, the first step is to select the date of stay. Select the specific day, the first click is for the start day, the second click is for the end day. Click on the same day if it is online for a short-term reservation like a couple of hours. Then select the location using the location dropdown. You can also see the detailed price information below.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.00.35.png?raw=true "Sakurabook Wizard Date Selection")

2. It looks like this when the day and location are selected. Click on the `Next` button.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.01.21.png?raw=true "Sakurabook Wizard Date Selected")

3. Next step is to select a specific time. Select start time and end time using the dropdowns. You also see the precalculated price below. Click on the `Next` button when you are ready.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.02.10.png?raw=true "Sakurabook Wizard Time Selection")

4. This is the summary screen. Customers can also add to their cart some AddOns for the rental. The summary price is automatically updated after you add the AddOn. In this example, there are no AddOns available for the rental space.

   ![Alt text](../img/Screenshot%202022-09-01%20at%2011.03.12.png?raw=true "Sakurabook Wizard Summary")

## Booking states

There are overall four possible states for each booking. It differs according to the step in which the customer ended the process above.

The `PENDING` state of the booking happens when customers leave the booking in their cart. They do not pay for the reservation yet. This is a state where we block the reserved day/time for **1 hour**.

The `ABBANDONED` state of the booking happens when customer leave the booking in their cart. They do not pay for the reservation yet. This is a state where we **do not** block the reserved day/time because it's been more than 1 hour.

The `REJECTED` state happens when the booking is successfully paid, but there is another conflicting booking. The booking is then rejected. If this happens, we send to both merchant and customer a notification email and merchant's support needs to reach to customer to sort out this situation.

The `CONFIRMED` state happens when the booking is successfully paid. Here we block the booked day/time ultimately until the merchant makes some changes, e.g. after the customer's communication with the support team.

---

➡ What's next? Go to the [Billing Plans](./billing-plans.md) for more.
