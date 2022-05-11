# PayPal Checkout (Client-Side REST API) Module for ProcessWire 3.x

ProcessWire payment method for PayPal Checkout using the Client-Side REST API with Smart Payment Buttons and PayPal JavaScript SDK.

## Install

1. Copy all files included in this module into new directory `/site/modules/PaymentPayPalExpressCheckout/`.
2. In the ProcessWire admin, go to Modules > Refresh.
3. Click install for the PayPal Checkout module.
4. Configure the required module fields.

## CSS Style on PayPal Button Container

To change the width of the container and/or if you're using dark theme on your website and you haven't disable the "Debit or Credit Cards" button you will definitely need to style the PayPal Button Container otherwise some elements (grey text & icon) might not be clearly visible.
~~~~~
#paypal-button-container {
  background: white;
  max-width: 500px;
  padding: 25px;
}
~~~~~

## Requirements

- ProcessWire 3.x
- [PaymentModule](https://github.com/apeisa/PaymentModule/tree/PW3) (PW3 branch) ProcessWire module

## Changelog

### 2.0.2 (11 May 2022)

- Improved payment validation

### 2.0.1 (10 November 2021)

- Added field for additional custom JavaScript (onApprove) on AJAX Checkout

### 2.0.0 (3 June 2021)

- Module upgraded with the current PayPal API
- Added Smart Payment Buttons and PayPal JavaScript SDK
- PayPal JavaScript SDK will automatically loaded even if AJAX enabled
IMPORTANT: If you were previously using AJAX, remove the old checkout.min.js from your templates

### 1.2.8 (19 March 2019)

- Fixed decimal point on javascript code to prevent broken PayPal popup on alternate languages

### 1.2.7 (17 January 2019)

- Fixed product titles with HTML entities on PayPal's item list

### 1.2.6 (16 January 2019)

- Removed fix from 1.2.5 version. Waiting for an official fix. More info [here](https://github.com/processwire/processwire-issues/issues/126).

### 1.2.5 (15 January 2019)

- Fixed some notes with HTML Entities to prevent breaking "Live Search" in Languages

### 1.2.4 (23 November 2018)

- Updated code syntax on hiding Funding Buttons

### 1.2.3 (4 November 2018)

- Added option to hide Funding Buttons (PayPal Credit, Credit/Debit Cards & ELV)

### 1.2.2 (24 October 2018)

- Added ability to display custom HTML above and below the PayPal buttons after they are fully rendered and ready to be clicked
- Changed title to PayPal Checkout
- Updated notes for AJAX Checkout

### 1.2.1 (15 April 2018)

- Added failure translatable text
- Remove form element when AJAX is enabled

### 1.2.0 (15 April 2018)

- Added AJAX support (Vanilla Javascript)
- Converted querySelector to getElementById to improve performance
- Added PayPal icon on Module info

### 1.1.0 (29 March 2018)

- Added an additional payment verification for preventing exploitation by manually accessing the process url from the source code and getting digital content without actually paying
- Easier switch between Sandbox & Live
- Display the PayPal buttons ONLY when they are fully rendered and ready to be clicked to prevent bad user experience
- Ability to display custom HTML while the PayPal buttons are fully rendered and ready to be clicked
- Switched to vertical layout
- Added Multi-Language support

### 1.0.0 (20 September 2017)

- Initial release

## License

GPL 2.0
