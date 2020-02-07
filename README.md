# Oracle Digital Assistant Sample Web App Readme (v. 19.1.5.0)

## Overview ##
The sample chat app that's included in the `bots-client-sdk-js-samples-19.1.5.0.zip` file is a mobile app that demonstrates communication with the Oracle Digital Assistant server. You can download this file from the [Oracle Technology Network’s ODA downloads page](https://www.oracle.com/technetwork/topics/cloud/downloads/amce-downloads-4478270.html).

## Usage ##
This sample app provides an end-to-end example that you can reference when building your own mobile app. It shows you how to initialize the Bots SDK using an App ID that's generated by Oracle Digital Assistant. It also shows you how to chat with other skills just by changing this App ID.
## Supported Browsers ##

The sample chat app supports all popular browsers.
### Desktop Versions ###
- Chrome: The latest release along with the previous major release.
- Edge: The latest release along with the previous major release.
- Firefox: The latest version along with the previous major release.
- Internet Explorer: Version 11 and higher.
- Safari: The latest release along with the previous major release.
### Mobile Versions ###
- Stock browser on Android 4.1 and higher
- Safari on iOS 8 and higher
### The JavaScript SDK
This sample app already has the Oracle Digital Assistant Client SDK for JavaScript included in the project. This SDK is compiled for the localhost environment only.
To use the SDK in another location, download it and follow the instructions in the README file.

## Generate the App ID ##
1. In your Oracle Digital Assistant instance, choose**Development** then **Channels** from the menu.
1. Choose **Users**.
1. Click **Add Channel** and then complete the dialog, choosing **Web** as the channel type. After you complete this dialog, Oracle Digital Assistant will generate the App Id that you need to initialize the SDK. Keep it close at hand.
1. Switch **Channel Enabled** to ON.
1. Route the channel to your skill or Digital Assistant.

## Installation and Runtime Setup ##
1. Navigate to the `chat-sample-web` directory.
1. Run `npm install`.
1. Run `node server.js`.
1. In your browser, open `http://150.136.216.174:3000`.
1. Enter the App ID that was generated by Oracle Digital Assistant in the field on the home page. (This embeds the APP ID in the sample app.) The chat window will be initialized and loaded.

## License ##
Copyright (c) 2018, 2019, Oracle Corporation and contributors

Permission is hereby granted, free of charge, to any person obtaining a copy of this software and associated documentation files (the "Software"), to deal in the Software without restriction, including without limitation the rights to use, copy, modify, merge, publish, distribute, sublicense, and/or sell copies of the Software, and to permit persons to whom the Software is furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY, FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM, OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE SOFTWARE.