# PayPal Express Checkout (Client-Side REST API) Module for ProcessWire 3.x

ProcessWire payment method for PayPal Express Checkout using the Client-Side REST API.

## Requirements

- ProcessWire 3.x
- [PaymentModule](https://github.com/apeisa/PaymentModule/tree/PW3) (PW3 branch) ProcessWire module

## Changelog

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
