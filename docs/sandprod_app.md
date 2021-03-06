---
layout: default
---

## Verification in SandBox

In order to test your integration you may use the MobilePay Vendor App which is targeted towards MobilePay SandBox environment. Products purchased through this app will also hit the Sellers SandBox environment.

### Step 1: Download MobilePay Vendor App
First you must download the MobilePay Vendor App for your desired `Market` and Mobile OS.

|Market       | Mobile OS     | Url                                       |
|-------------|---------------|-------------------------------------------|
|`DK`         |Android        | [Link](https://dbg.tpa.io/p/KnSXxG8NQ8Mv0yhct5iC) |
|`DK`         |iOS            | [Link](https://dbg.tpa.io/p/h-XHpPXMT3PgvNiKtalW) |
|`FI`         |Android        | [Link](https://dbg.tpa.io/p/K3WYrFuT_pHYEWoRYhtH) |
|`FI`         |iOS            | [Link](https://dbg.tpa.io/p/nAJ3Sjmr6plQqOKl1vyR) |

### Step 2: Sign in
Use the following login details to sign in to MobilePay Vendor app

|Market       | Phone number  | Verification code (OTP) | Pin | SSN
|-------------|---------------|-------------------------------------------|
|`DK`         |      +4550000004        | 123456 | 1234 | 000000-0000               |
|`DK`         |      +4550000005        | 123456 | 1234 | 000000-0000               |
|`FI`         |      ?        | 123456 | 1234 | ?                         |
|`FI`         |      ?        | 123456 | 1234 | ?                         |

If your User stops working please let your contact at MobilePay know.

### Step 3: Use Marketplace
Access the Marketplace through the tab in MobilePay to browse your added products. Remember that products must be manually approved by someone from MobilePay before they will show up on the Marketplace, for now this is also the procedure in SandBox.

After the products have been added please verify that they behave as expected regarding texts, how they can be configured, their prices and also VAT.

Test integration by purchasing one of your products using one User and giving it to the other User in the same `Market`. While delivering the product to the recipient, your endpoints will be called.