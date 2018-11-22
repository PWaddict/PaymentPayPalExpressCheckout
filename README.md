# PayPal Checkout (Client-Side REST API) Module for ProcessWire 3.x

ProcessWire payment method for PayPal Checkout using the Client-Side REST API.

## Requirements

- ProcessWire 3.x
- [PaymentModule](https://github.com/apeisa/PaymentModule/tree/PW3) (PW3 branch) ProcessWire module

## Changelog

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
