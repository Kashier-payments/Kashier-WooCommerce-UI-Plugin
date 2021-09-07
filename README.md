# Kashier-WooCommerce-UI-Plugin
### Wordpress Woocommerce  - Kashier plugin
Kashier WooCommerce Plugin

 * Version: 2.0.0
 * Requires at least: 4.4
 * Tested up to: 5.4.1
 * WC requires at least: 2.6
 * WC tested up to: 3.6.4

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/kashier-logo.png)
![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/woocommercew-logo.png)

### Features

- Fully PCI DSS compliant as a Level 1 Service for merchant operating in Egypt.

- I-frame integration.

- 3D secure cards authentication support.

- Support multiple payment method.

      1. Card Payments
      2. Wallet Payments 
      3. Bank Installments Payment    

- Support acquiring multiple currencies "EGP, USD, GBP, EUR".

- Plug and play.


### Installation

- Download [kashier.zip](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/Kashier-WooCommerce-UI-Plugin-master.zip) 

- Upload and activate the plugin on Woocommerce.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/kashier_upload.png)

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/kashier_activate.png)

### Obtain Test Credentials

- Login or Sign up on kashier.io https://merchant.kashier.io/

- Navigate to Integrate now section > payment api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

- Copy Merchant ID visible under your user name "MID-xx-xx".

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/apikeytest.png)

- Navigate to Woocommerce > settings > payments

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/woocommerce_payment_methods.png)

- there are three payment methods added to Woocommerce > settings > payments section

- choose payment methods which you would like to use to accept payment via kashier.

- Insert the MID and Test Api Key in the Configuration page of each payment method.

- Make sure the enable checkbox is checked.

- Make sure the test mode is on.

- Customize the title and description that will show up to your users.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/woocommerce_configurtion_payment.png)

### Enable Advanced Options 

- Enable Enforce EGP Payment checkbox to accept only EGP payment via kashier, Regardless what is the default currency displayed on your website.
- After enabling Enforce EGP Payment checkbox , you have to insert exchange rate from your default currency displayed on your website to EGP currency. the exchange rate must be greater than 1 .
- The next picture is example of advanced options configuration if you display USD currency by default on your website, but you want customers to only pay by EGP currency via kashier payment method. 

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/advanced_options.png)

### Test plugin 

- Proceed to make an order on your shop, a new payment method is added . it could be changed from module configuration.

- After proceeding you will find a Kashier Payment methods that you added it. choose one of them and proceed to make a payment.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/checkout_methods.png)


### Go live

- After activating your account.

- Make sure you are on live mode.

- Navigate to Integrate now section > payment api keys.

- Generate a new api key with your prefered name that describes your integration channel, there is 1 default api key you could use that is created when signing up.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/apikeylive.png)

- Insert Live Api Key in the Configuration page of each module.

- Remove the test mode check.

- Save configuration.

![](https://raw.githubusercontent.com/Kashier-payments/Kashier-WooCommerce-UI-Plugin/main/steps/woocommerce_configuration_live.png)


### Support

- Leave us an inquiry ticket on https://kashier.io for questions.


