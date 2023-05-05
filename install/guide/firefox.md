# Firefox

### Using Dappnet with Firefox.

To use Dappnet with Firefox, we have to do one extra step.&#x20;

1. Download [dappnet-firefox](https://github.com/gliss-co/undisclosed/releases/download/extension-firefox-0.1.15/dappnet-extension\_firefox\_0.1.15.xpi).
2. Open about:addons
3. Click the cog, and click "Install addon from file".
4. Select the `dappnet-firefox.xpi` file.

Now we must install the Dappnet certificate authority. This has a few steps, but don't worry, we only have to do it once.

5. In Firefox, open Settings (⌘+,).
6. Search for "**certificates**" and click "**View Certificates**"

![](<../../.gitbook/assets/Screen Shot 2023-03-10 at 1.13.38 pm.png>)

You should see this dialog:

![](<../../.gitbook/assets/Screen Shot 2023-03-10 at 1.05.40 pm.png>)

7. Select the **"Authorities**" tab and click "Import"

![](<../../.gitbook/assets/Screen Shot 2023-03-10 at 1.05.50 pm.png>).

You should see a file picker popup. Now we have to find the file. To do this, we're going to find it in Finder first, and then drag it into this dialog.

8. Open Finder, hit Shift+Cmd+G and paste this:\
   `~/Library/Application Support/Dappnet/data/` and hit enter.\
   \
   You should be navigated to a folder like below. \
   ![](<../../.gitbook/assets/Screen Shot 2023-03-10 at 1.25.10 pm.png>)
9. Select "**ca.crt**" and **drag this into the Firefox file picker from before.** Click OK.\
   \
   The final step is configuring this certificate.\
   \- Enable "**Trust this CA to identify websites**".\
   \
   Click OK.\
   \
   ![](<../../.gitbook/assets/Screen Shot 2023-03-10 at 1.26.42 pm.png>)

You've now completed the setup process. Congratulations, that was painful.

\
\


