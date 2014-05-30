**Plex Home Theater profile for Savant**

This profile requires that you are running Plex Home Theater 1.0 or above.

You need to enable TCP control of Plex Home Theater by modifying the GUIsettings.xml file, This must be done while PHT is not running:

 - Quit Plex Home Theater 
 - Open ~/Library/Application Support/Plex Home Theater/userdata/guisettings.xml
 - Locate "esallinterfaces" and change this setting to "true"
 - Start Plex Home Theater


Please note that you will need to be running RacePoint Media version 5.2.2 or above in order to inject the custom screen correctly.

!!*** Some thumbnails may not work if you have scanned your media using an older version of Plex Media Server.

!!*** This profile has been tested with a NEW library using Plex Home Thearer v1.0.13.222 and Plex Media Server v0.9.9.7


!!*** **Please read "How To - Injecting Screen.pdf" for install instructions**

** Donations are always welcome! :**
<form action="https://www.paypal.com/cgi-bin/webscr" method="post" target="_top">
<input type="hidden" name="cmd" value="_s-xclick">
<input type="hidden" name="encrypted" value="-----BEGIN PKCS7-----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-----END PKCS7-----
">
<input type="image" src="https://www.paypalobjects.com/en_US/i/btn/btn_donate_LG.gif" border="0" name="submit" alt="PayPal - The safer, easier way to pay online!">
<img alt="" border="0" src="https://www.paypalobjects.com/en_US/i/scr/pixel.gif" width="1" height="1">
</form>

Here is a preview of the updated Retina screen that includes thumbnails:
![movies](https://copy.com/fWsLoII7mHoOh436)
![tv shows](https://copy.com/4k9Jq1QCPIhgckB3)
![nothing](https://copy.com/mzk96MzcKtEJLtIQ)
