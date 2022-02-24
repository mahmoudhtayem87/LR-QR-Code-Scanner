# Commerce QR Code Scanner

Simple QR Scanner which reads the QR Code, The QR Code should be SKU ID for a product which need to be added to the cart.

This feature has been developed using simple fragment as an example of how we can use commerce headless.

The fragment has been developed with configuration which will allow you to specify the channel id and the currency code, the fragment will start by querying the available accounts for the signed in user, once the account is selected a list of open cart will be available to select from, if there is no open cart, the fragment will create one on the fly.
