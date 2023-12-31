---
layout: essay
type: essay
title: "Assignment 3 Checkpoint"
# All dates must be YYYY-MM-DD format!
date: 2023-12-12
published: true
labels:
  - Checkpoint
---

*Assignment 3 Checkpoint*

[This](https://drive.google.com/file/d/1Hw1FKH61d05zUU_8XfXx7BtbIwQrCfB_/view?usp=sharing) is what the Website will look like:




**1. Describe your design for your site’s shopping cart. That is, will it be a separate page that the user can view and edit, or will it be integrated into the product pages? If so, describe in detail how this will work on your site. Provide several examples of using the cart.**

The shopping cart will be the invoice page that existed before and the new invoice page will now be a simpler page of simply thanking the customer for the order and displaying that the order receipt was emailed to (user) email. 

**2. Explain specifically how you will use sessions to manage your shopping cart. In particular, what shopping cart data will be stored in the session, what data format will be used (NOT what data type, but the format like with the data format used for your registration data). Use code examples showing what data structures (such as arrays and their objects) you will use to manage the shopping cart data and how they will be used in a session.**

In order to use sessions, we will add the quanitites selected to an array of quantities when the user presses add to cart. By doing so, we are able to save this information for use in the shopping cart as well as invoice.

**3. How will you avoid access to your application when the user has not logged in or registered? What are the particular security concerns you must address?**

To avoid unauthorized access, it is important to make use of validations which will look for cookies associated with logging in. If a user does not have a username cookie associated, they will not be able to access any shopping carts or invoices.

**4. Upon a successful login, how do you provide personalization in your UI? Explain how you did or will do this (paste code if necessary)**

To provide personalization upon login, the shopping cart as well as invoice will display the users name and email address. Along with this, when checking out, the user will input their shipping address to have a proper address displayed on the receipt e-mailed.
How are you approaching Assignment 3 differently than Assignment 2?
