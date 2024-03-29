![Image of Coinsnap for WooCommerce](https://coinsnap.io/wp-content/uploads/2023/11/Coinsnap-for-Woocommerce-2.png)

# Coinsnap for WooCommerce Payment Plugin

=== Coinsnap for WooCommerce 1.1.1 ===
Contributors: coinsnap
Tags: Lightning, Lightning Payment, SATS, Satoshi sats, bitcoin, Wordpress, WooCommerce, payment gateway, accept bitcoin, bitcoin plugin, bitcoin payment processor, bitcoin e-commerce, Lightning Network, cryptocurrency, lightning payment processor
Requires at least: 5.2
Tested up to: 6.4
Requires PHP: 7.4
Stable tag: 1.1.1
License: GPLv2
License URI: http://www.gnu.org/licenses/gpl-2.0.html

Coinsnap payment plug-in is intended for online stores based on WooCommerce to accept Bitcoin and Lightning payments via Coinsnap payment gateway https://app.coinsnap.io/.

== Description ==

[Coinsnap](https://coinsnap.io/en/) is a Lightning payment provider that allows to process Bitcoin and Lightning payments over Lightning network. A merchant only needs a Lightning wallet with a Lightning address to accept Bitcoin and Lightning payments on their website.


= Bitcoin and Lightning payments in your WooCommerce store with Coinsnap =

With Coinsnap payment processing, you can accept Bitcoin and Lightning payments on your website or online store. You don’t need your own Lightning Node or other technical requirements.

Bitcoin and Lightning payments from your customers will be credited directly to your own Lightning address.

With Coinsnap Payment Plugin you can integrate Bitcoin and Lightning payments into your website or online store without any technical effort.

Simply register in [Coinsnap](https://app.coinsnap.io/), enter your own Lightning address and your customers can pay you with Bitcoin and Lightning.


= Features: =

* **Only 1 % fees!**:
    * No basic fee, no transaction fee, only 1% on the invoice amount with referrer code.
    * Without referrer code the fee is 1.25%.
    * Get a referrer code from our partners and customers and save 0.25% fee.
* **All you need is a Lightning Wallet with a Lightning address. [Here you can find an overview of the matching Lightning Wallets](https://coinsnap.io/en/lightning-wallet-with-lightning-address/)**
* **Accept Bitcoin and Lightning payments in your online store without running your own technical infrastructure. You do not need your own server, nor do you need to run your own Lightning Node.**
* **Quick and easy registration**: you enter your email address and your Lightning address.
* **Absolutely protected privacy**:
    * We do not collect personal data.
    * For the registration you only need an e-mail address, which we will also use to inform you when we have received a payment.
    * No other personal information is required as long as you request a withdrawal to a Lightning address or Bitcoin address.
* **No KYC needed**:
    * Direct, P2P payments (instantly to your Lightning wallet)
    * No intermediaries and paperwork
    * Transaction information is only shared between you and your customer
* **A Bitcoin payment via Lightning offers significant advantages**:
    * Lightning payments are executed immediately.
    * Lightning payments are credited directly to the recipient.
    * Lightning payments are inexpensive.
    * Lightning payments are guaranteed. No chargeback risk for the merchant.
    * Lightning payments can be used worldwide.
    * Lightning payments are perfect for micropayments.
* **Multilingual interface and support**: We speak your language


= Documentation: =

* [Coinsnap API (1.0) documentation](https://docs.coinsnap.io/)
* [Frequently Asked Questions](https://coinsnap.io/en/faq/) 
* [Terms and Conditions](https://coinsnap.io/en/general-terms-and-conditions/)
* [Privacy Policy](https://coinsnap.io/en/privacy/)


== Installation ==

### 1.1 Install the Coinsnap WooCommerce plugin from the WordPress directory ###

The Coinsnap WooCommerce plugin can be searched and installed in the WordPress plugin directory.

![](https://coinsnap.io/wp-content/uploads/2023/09/Photo1.png)

In your WordPress instance, go to the Plugins > Add New section. In the search you enter Coinsnap and get as a result the Coinsnap WooCommerce plugin displayed.
After successful installation, click Activate and then you can start setting up the plugin.

### 1.2. Install the Coinsnap WooCommerce plugin from Github page ###

If you don’t want to install Coinsnap WooCommerce plugin directly via plugin, you can download Coinsnap WooCommerce plugin from Coinsnap Github page here.
Find the green button labeled Code. When you click on it, the menu opens and Download ZIP appears. Here you can download the latest version of the Coinsnap plugin to your computer.

![](https://coinsnap.io/wp-content/uploads/2023/11/github-coinsnap.jpg)

Then use the “Upload plugin” function to install it. Click on “Install now” and the Coinsnap for WooCommerce plugin will be added to your WordPress website. It can then be connected to the Coinsnap payment gateway.

![](https://coinsnap.io/wp-content/uploads/2023/08/Add-Coinsnap-Woocommerce-plugin.png)

As soon as the Coinsnap for WooCommerce plugin is installed and activated, a message will appear asking you to configure the plugin settings.

== Connect Coinsnap account with WooCommerce plugin ==

### 2.1. WooCommerce Coinsnap Settings ###

After you have installed and activated the Coinsnap for WooCommerce plugin, you need to make the Coinsnap settings. You can access this area via WooCommerce and Settings. On the far right you will find Coinsnap Settings.
![](https://coinsnap.io/wp-content/uploads/2023/09/Photo2-1.png)

After clicking on the link provided or going to the Coinsnap settings tab, a form will appear asking you for your Coinsnap Store ID and your Coinsnap API key.

![](https://coinsnap.io/wp-content/uploads/2023/09/Screenshot-2023-09-09-at-10.16.23.png)

These details are provided via your Coinsnap account in the store settings section. If you do not yet have a Coinsnap account, you can register under the following link: [Coinsnap registration](https://app.coinsnap.io/register).

### 2.1.1. Coinsnap Store Settings needed for configuration ###

![](https://coinsnap.io/wp-content/uploads/2023/09/Screenshot-2023-09-12-at-08.40.13-1-2.png)

Go to the Settings menu item in the Coinsnap backend. There you will find the Coinsnap Store ID and the Coinsnap API Key in the Store Settings section.

Click on the “Save changes” button at the bottom of the page to apply and save the settings.

== WooCommerce payment settings ==

### 3. WooCommerce payment settings ###

Navigate to the Payment tab under the WooCommerce settings to see a list of all available payment methods. Coinsnap is shown at the end of the list.

![](https://coinsnap.io/wp-content/uploads/2023/09/Photo4-1.png)

##### (1) Activate Coinsnap #####
You must activate Coinsnap as a payment option.

##### (2) Additional configurations #####
To do this, click on the “End setup” or “Manage” button.

--------------------------------------------------------------------------------------------------
Adjustments can be made here, which are displayed to the customer during the payment process.

![](https://coinsnap.io/wp-content/uploads/2023/11/Photo5-2-1.png)

##### (1) Title field #####
In the Title field, for example, you can specify that you accept “Bitcoin and Lightning”.

##### (2) Notes field #####
A note can also be entered in the Customer message field to inform the payer of the next steps.

![](https://coinsnap.io/wp-content/uploads/2023/11/Photo5-2-1-1.png)

##### (3) Gateway symbol #####
By selecting the “Upload or select icon” button, you have the option of adding a personalized icon or image that symbolizes a payment gateway or payment method for your online store. This image serves as a visual indicator for a specific payment option or gateway that is displayed to the customer at the time of checkout.

##### (4) Enforce payment coins #####
Enforce payment tokens refers to a system setting that ensures that only certain types of tokens are accepted for a specific payment method or gateway. This ensures that promotional tokens (which may represent discounts, special offers or other non-traditional forms of payment) are not mistakenly processed as regular payment tokens within this gateway.

== Test the payment in the WooCommerce store ==

### 4. Test the payment in the WooCommerce store ###

After all settings have been made, a test transaction should be carried out.

![](https://coinsnap.io/wp-content/uploads/2023/09/Photo7.png)

Place an order in your WooCommerce online store and search for Bitcoin and Lightning Payment among the available payment options. Choose this method and click on Pay with Bitcoin.
You will be redirected to the Bitcoin payment page to complete the purchase.

<p float="left">
  <img src="https://coinsnap.io/wp-content/uploads/2023/09/Photo9.59.png" width="350" height="500" />
  <img src="https://coinsnap.io/wp-content/uploads/2023/09/Photo9-1.png" width="380" height="500" /> 
</p>

The Bitcoin payment page is now displayed and offers the payer the option of paying with Bitcoin or Lightning. Both methods are integrated in the displayed QR code. After successful payment, the invoice can be viewed in detail.
