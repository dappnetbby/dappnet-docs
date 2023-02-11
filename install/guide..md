# Guide.

Welcome to a whole new world ;)

**Compatibility**: macOS with Chrome.

### Install the app

1. Download the [package](https://github.com/liamzebedee/test1717/releases/download/v1.4.1/Dappnet-1.4.1.pkg) for macOS.
2. Install.

### Now run it!

[![image](https://user-images.githubusercontent.com/584141/190632676-505da23b-138c-47cd-8316-ab4ff4638106.png)](https://user-images.githubusercontent.com/584141/190632676-505da23b-138c-47cd-8316-ab4ff4638106.png)

Launch "Dappnet", it'll be in your Applications. You should see this:

[![https://i.imgur.com/0uIHPZn.png](https://camo.githubusercontent.com/0e73211bb1b350e82f0ce67ee04be389e215e420a3be3f12a0dec15f6fdb779d/68747470733a2f2f692e696d6775722e636f6d2f30754948505a6e2e706e67)](https://camo.githubusercontent.com/0e73211bb1b350e82f0ce67ee04be389e215e420a3be3f12a0dec15f6fdb779d/68747470733a2f2f692e696d6775722e636f6d2f30754948505a6e2e706e67)

(If not, you can check the logs by running `/Applications/Dappnet.app/Contents/MacOS/Dappnet` in your Terminal. Send them to me.)

Click any of the dapps and they will open in a new window. Each dapp is loaded trustlessly from IPFS.



### Using Dappnet with Chrome.

1. Download [dappnet-chrome](https://github.com/gliss-co/undisclosed/releases/download/extension-chrome-1.5/dappnet-extension\_chrome\_0.2.0.zip).
2. Unzip.
3. Open chrome://extensions/\
   ![](<../.gitbook/assets/Screen Shot 2022-09-16 at 9.57.25 pm.png>)
4. Enable developer mode.
5. Click "Load unpacked extension"
6. Select the `dappnet-extension_chrome_0.2.0` folder.

And that's it!

.eth urls will load in your browser. They need to end in a slash `/` when you type them in the URL bar, otherwise it goes to Google.

[![image](https://user-images.githubusercontent.com/584141/190633788-3036d5a4-8c33-4c38-adb9-8c9e5c70c760.png)](https://user-images.githubusercontent.com/584141/190633788-3036d5a4-8c33-4c38-adb9-8c9e5c70c760.png)

[![image](https://user-images.githubusercontent.com/584141/190633252-98c76b5c-0688-4887-a563-c0d8836712ed.png)](https://user-images.githubusercontent.com/584141/190633252-98c76b5c-0688-4887-a563-c0d8836712ed.png)

The **first time** you visit a dapp, it might download a bit slowly (\~10s or so). But after that - the app is downloaded to your device. It loads **instantly**.

How is that possible? What is going on in the background?

Dappnet is running a local IPFS node on your computer, and torrenting directly from a P2P network. You haven't just visited a website, you've downloaded a dapp. It's yours to keep.

