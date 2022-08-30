# Price for Bookings

Let's have a look into some specific cases for bookings. As you already know, all imported products, Rental spaces, Services, or AddOns, have several price variants that were created by the Sakurabook app immediately after import and their prices were amended by you, merchants.

📌 Have you forgotten to amend the `Price` of your Product Variants? Go to https://your-store-name.myshopify.com/admin/products and do it now.

There are overall nine variants for each product you are selling with Sakurabook. The names of the variants are self-explanatory.

- WORKING DAY - Price per minute
- WEEKEND - Price per minute
- WORKING DAY - Price per hour
- WEEKEND - Price per hour
- WORKING DAY - Price per day
- WEEKEND - Price per day
- WORKING DAY - Price per week
- WORKING DAY - Price per month
- WORKING DAY - Price per year

We calculate the final price using these price variants. There are no additional fees or extras for your customers.

📌 Sakurabook counts week as 7 days, month as 30 days, and year as 12 months (360 days).

Let's have a look at a couple of examples. We will use undefined currency in the examples.

# Examples

1. Booking is for 45 minutes on a working day.

   **Start**: 2022-07-18, 21:00

   **End**: 2022-07-18, 21:45

   | Variant                        | Amount | Price   |
   | ------------------------------ | ------ | ------- |
   | WORKING DAY - Price per minute | 45     | 10      |
   | **Total**                      |        | **450** |

1. Booking is for 45 minutes on a working day and there's one AddOn in the order.

   **Start**: 2022-07-18, 21:00

   **End**: 2022-07-18, 21:45

   | Variant                                | Amount | Price   |
   | -------------------------------------- | ------ | ------- |
   | WORKING DAY - Price per minute         | 45     | 10      |
   | WORKING DAY - Price per minute (AddOn) | 45     | 1       |
   | **Total**                              |        | **495** |

1. Booking is for a couple of hours on the same weekend.

   **Start**: 2022-07-23, 08:30

   **End**: 2022-07-23, 17:30

   | Variant                  | Amount | Price     |
   | ------------------------ | ------ | --------- |
   | WEEKEND - Price per hour | 9      | 200       |
   | **Total**                |        | **1,800** |

1. Booking starts on a weekday and ends on a weekend.

   **Start**: 2022-07-22, 23:00

   **End**: 2022-08-22, 01:00

   | Variant                      | Amount | Price   |
   | ---------------------------- | ------ | ------- |
   | WEEKEND - Price per hour     | 1      | 200     |
   | WORKING DAY - Price per hour | 1      | 100     |
   | **Total**                    |        | **300** |

1. Booking is from Monday 12:00 to next Monday 12:00.

   **Start**: 2022-01-03, 12:00

   **End**: 2022-01-10, 12:00

   | Variant                      | Amount | Price      |
   | ---------------------------- | ------ | ---------- |
   | WORKING DAY - Price per week | 1      | 10,000     |
   | **Total**                    |        | **10,000** |

1. Booking is from Monday 12:00 to next Monday 14:00.

   **Start**: 2022-01-03, 12:00

   **End**: 2022-01-10, 14:00

   | Variant                      | Amount | Price      |
   | ---------------------------- | ------ | ---------- |
   | WORKING DAY - Price per week | 1      | 10,000     |
   | WORKING DAY - Price per hour | 2      | 100        |
   | **Total**                    |        | **10,200** |

1. Booking is from Monday 12:00 to Sunday 12:00.

   **Start**: 2022-01-03, 12:00

   **End**: 2022-01-09, 12:00

   | Variant                      | Amount | Price     |
   | ---------------------------- | ------ | --------- |
   | WEEKEND - Price per day      | 1      | 2,000     |
   | WORKING DAY - Price per day  | 4      | 1,000     |
   | WEEKEND - Price per hour     | 12     | 200       |
   | WORKING DAY - Price per hour | 12     | 100       |
   | **Total**                    |        | **9,600** |

1. Booking is from Monday 12:00 to Sunday 16:30.

   **Start**: 2022-01-03, 12:00

   **End**: 2022-01-09, 16:30

   | Variant                      | Amount | Price      |
   | ---------------------------- | ------ | ---------- |
   | WEEKEND - Price per day      | 1      | 2,000      |
   | WORKING DAY - Price per day  | 4      | 1,000      |
   | WEEKEND - Price per hour     | 16     | 200        |
   | WORKING DAY - Price per hour | 12     | 100        |
   | WEEKEND - Price per minute   | 30     | 20         |
   | **Total**                    |        | **11,000** |

1. Booking is from Thursday 6.1.2022 12:00 to Tuesday 11.1.2022 12:00

   **Start**: 2022-01-06, 12:00

   **End**: 2022-01-11, 12:00

   | Variant                     | Amount | Price     |
   | --------------------------- | ------ | --------- |
   | WEEKEND - Price per day     | 2      | 2,000     |
   | WORKING DAY - Price per day | 3      | 1,000     |
   | **Total**                   |        | **7,000** |

1. Booking is from Sunday 9.1.2022 12:00 to Sunday 16.1.2022 12:00.

   **Start**: 2022-01-09, 12:00

   **End**: 2022-01-16, 12:00

   | Variant                      | Amount | Price      |
   | ---------------------------- | ------ | ---------- |
   | WORKING DAY - Price per week | 1      | 10,000     |
   | **Total**                    |        | **10,000** |

1. Booking is from Sunday 9.1.2022 12:00 to Sunday 16.1.2022 10:00.

   **Start**: 2022-01-09, 12:00

   **End**: 2022-01-16, 10:00

   | Variant                     | Amount | Price      |
   | --------------------------- | ------ | ---------- |
   | WEEKEND - Price per day     | 1      | 2,000      |
   | WORKING DAY - Price per day | 5      | 1,000      |
   | WEEKEND - Price per hour    | 22     | 200        |
   | **Total**                   |        | **11,400** |

1. Booking is from Monday 3.1.2022 12:00 to Friday 3.2.2023 16:30.

   **Start**: 2022-01-03, 12:00

   **End**: 2023-02-03, 16:30

   | Variant                        | Amount | Price         |
   | ------------------------------ | ------ | ------------- |
   | WORKING DAY - Price per year   | 1      | 1,000,000     |
   | WORKING DAY - Price per month  | 1      | 100,000       |
   | WEEKEND - Price per day        | 1      | 2,000         |
   | WORKING DAY - Price per day    | 4      | 1,000         |
   | WEEKEND - Price per hour       | 12     | 200           |
   | WORKING DAY - Price per hour   | 16     | 100           |
   | WORKING DAY - Price per minute | 30     | 10            |
   | **Total**                      |        | **1,110,300** |

1. Booking is from Monday 3.1.2022 12:00 to Sunday 5.2.2023 16:30.

   **Start**: 2022-01-03, 12:00

   **End**: 2023-02-05, 16:30

   | Variant                       | Amount | Price         |
   | ----------------------------- | ------ | ------------- |
   | WORKING DAY - Price per year  | 1      | 1,000,000     |
   | WORKING DAY - Price per month | 1      | 100,000       |
   | WORKING DAY - Price per week  | 1      | 10,000        |
   | WEEKEND - Price per day       | 1      | 2,000         |
   | WEEKEND - Price per hour      | 4      | 200           |
   | WEEKEND - Price per minute    | 30     | 20            |
   | **Total**                     |        | **1,113,400** |

1. Booking is from Monday 3.1.2022 12:00 to Tuesday 7.2.2023 16:30.

   **Start**: 2022-01-03, 12:00

   **End**: 2023-02-07, 16:30

   | Variant                        | Amount | Price         |
   | ------------------------------ | ------ | ------------- |
   | WORKING DAY - Price per year   | 1      | 1,000,000     |
   | WORKING DAY - Price per month  | 1      | 100,000       |
   | WORKING DAY - Price per week   | 1      | 10,000        |
   | WEEKEND - Price per day        | 1      | 2,000         |
   | WORKING DAY - Price per day    | 1      | 1,000         |
   | WEEKEND - Price per hour       | 12     | 200           |
   | WORKING DAY - Price per hour   | 16     | 100           |
   | WORKING DAY - Price per minute | 30     | 10            |
   | **Total**                      |        | **1,117,300** |

---

➡ What's next? Go to the [Settings](./settings.md) guide.
