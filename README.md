#BarcodeScannerForPhoneGap

The BarcodeScanner widget enables PhoneGap native barcode scanning functionality within your Mendix mobile application. This is a widget that will be functional from Mendix 7.13.1.

## Contributing

For more information on contributing to this repository visit [Contributing to a GitHub repository](https://world.mendix.com/display/howto50/Contributing+to+a+GitHub+repository)!

## Configuration

Place the widget in a dataview where you want the button to be placed. Make sure this form is reachable from a mobile application.

### Button
#### Label
The label text that is shown on the button.

#### Class
An optional class to be placed directly on the button dom node.

### Data source
#### Attribute
The attribute on the dataview object where the resulting string should be set to.

### Events
#### On change microflow
An optional microflow that will be triggered once the location has been retrieved.
#### On change nanoflow
An optional nanoflow that will be triggered once the location has been retrieved.