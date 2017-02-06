## Description
This Google Chrome extension converts the URL of the current tab of the Chrome browser into a QR-code. To convert the URL the extension uses the [Google Charts API](https://developers.google.com/chart/interactive/docs/reference).

This project was chosen as an introduction to the development of extensions for Google Chrome. The code is based on the [Getting Started](https://developer.chrome.com/extensions/getstarted) tutorial from Google.

## ToDo
- ~~create a better icon~~
- ~~show text that has been converted~~
- check if permissions are all necessary or if "activeTab" would be sufficient (https://developer.chrome.com/extensions/activeTab)
- tidy up code
- check URLs/text from the URL-field for special characters and encode them correctly
- use an internal QR-code generator for real offline functionality / may be used behind restricted company proxies.
- display a textfield for custom text-to-QR
