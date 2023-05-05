# Install guide.

Welcome to a whole new world ;)

**Compatibility**: macOS with Chrome/Firefox.

### Install the app

1. Download the [package](https://dappnet-update-server-pi.vercel.app/latest/mac/pkg) for macOS.
2. Install.

### Now run it!

[![image](https://user-images.githubusercontent.com/584141/190632676-505da23b-138c-47cd-8316-ab4ff4638106.png)](https://user-images.githubusercontent.com/584141/190632676-505da23b-138c-47cd-8316-ab4ff4638106.png)

Launch "Dappnet", it'll be in your Applications. You should see this:

[![https://i.imgur.com/0uIHPZn.png](https://camo.githubusercontent.com/0e73211bb1b350e82f0ce67ee04be389e215e420a3be3f12a0dec15f6fdb779d/68747470733a2f2f692e696d6775722e636f6d2f30754948505a6e2e706e67)](https://camo.githubusercontent.com/0e73211bb1b350e82f0ce67ee04be389e215e420a3be3f12a0dec15f6fdb779d/68747470733a2f2f692e696d6775722e636f6d2f30754948505a6e2e706e67)

(If not, you can check the logs by running `/Applications/Dappnet.app/Contents/MacOS/Dappnet` in your Terminal. Send them to me.)

Now we need to upgrade your browser to work with Dappnet.

### Using Dappnet with Firefox.

Follow the [instructions here](firefox.md).

### Using Dappnet with Chrome.

Click the link below to install the Dappnet extension.

{% embed url="https://chrome.google.com/webstore/detail/dappnet/aaejjpmafbcbidcjmmkangcfcabiidlf" %}

And that's it!

.eth urls will load in your browser. **They need to end in a slash `/` when you type them in the URL bar, otherwise it goes to Google.**

[![image](https://user-images.githubusercontent.com/584141/190633788-3036d5a4-8c33-4c38-adb9-8c9e5c70c760.png)](https://user-images.githubusercontent.com/584141/190633788-3036d5a4-8c33-4c38-adb9-8c9e5c70c760.png)

[![image](https://user-images.githubusercontent.com/584141/190633252-98c76b5c-0688-4887-a563-c0d8836712ed.png)](https://user-images.githubusercontent.com/584141/190633252-98c76b5c-0688-4887-a563-c0d8836712ed.png)

The **first time** you visit a dapp, it might download a bit slowly (\~10s or so). But after that - the app is downloaded to your device. It loads **instantly**.

How is that possible? What is going on in the background?

Dappnet is running a local IPFS node on your computer, and torrenting directly from a P2P network. You haven't just visited a website, you've downloaded a dapp. It's yours to keep.

