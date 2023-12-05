## How to test

- Download the custom Metamask-Flask extension build which already includes the NuFi Cardano snap
- For [Chrome](https://github.com/nufi-official/metamask-snap-demo/releases/download/0.0.1/nufi-snap-metamask-build-chrome-0.0.1.zip) or [Firefox](https://github.com/nufi-official/metamask-snap-demo/releases/download/0.0.1/nufi-snap-metamask-build-firefox-0.0.1.zip)
- Unzip
- [Add custom extension](https://github.com/nufi-official/metamask-snap-demo/edit/main/README.md#add-custom-extension) according to the section below
- Open the custom Metamask-Flask extension and log in.
- Navigate to **TODO**(url of the test dapp) and click "**TODO**(name of the button)"
- **TODO(other steps for testing)**


## Add custom extension  

### Chrome

* Open `Settings` > `Extensions`.
  * Or go straight to [chrome://extensions](chrome://extensions).
* Check "Developer mode".
* At the top, click `Load Unpacked Extension`.
* Navigate to your unzipped Chrome extension folder.
* Click `Select`.



### Firefox

* Go to the url `about:debugging#addons`.
* Click the button `Load Temporary Add-On`.
* Navigate to your unzipped Firefox extension folder. Select the file `manifest.json`.
