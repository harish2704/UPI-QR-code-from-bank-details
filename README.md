# UPI-QR-code-from-bank-details
Generate shareable QR code, link from bank details to use with UPI payment apps

## [Try it now](https://harish2704.github.io/UPI-qr-gen/)

It first generate a [UPI](https://www.npci.org.in/what-we-do/upi/product-overview) id from bank details and then generates following items for end users.

1. QR code image
2. Sharable URL
    - Shareable URLs **do not send any banking data to any third party servers**. The data is stored in "hashbang" which is only accessible to web browsers and not sent to servers
4. Mobile friendly link which will invoke the installed UPI application in any device

### Powered by

1. https://github.com/soldair/node-qrcode
2. https://milligram.io/
3. https://unpkg.com/
4. Github pages
