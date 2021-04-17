# AirQuality From AirNow.org

If you don't already have one, get an <a href="https://docs.airnowapi.org/account/request/">API key for AirNow.</a>

<UL><li>Request a free AirNow API key</li>
<li>Log in to the AirNow API website.</li></UL>

Visit any of the Web Services documentation pages (e.g. Forecast by Zip Code) and look for Your API Key: in the top right of the page.

It should be a string of hexadecimal characters in the format XXXXXXXX-XXXX-XXXX-XXXX-XXXXXXXXXXXX. If you see your API key simply listed as GUEST, that's not it. The main AirNow Web Services index page currently has a bug that shows this as the key even when logged in. Try one of the subpages.

Save your key somewhere - you will need it in the Driver.

Install this Driver and create a New Virtual Device. 
<UL><li>Give your virtual Device a name, AirNow AQI perhaps.</li>
<li>Drom the Type dropdown, scroll to the end and pick "Air Quality from AirNow"</li>
<li>Click Save and your new device is ready to configure.</li>
<li>Copy / Paste your AirNow API Key and choose a Poll interval and which AQI reading you would like.</li></UL>

Note that AQI is an index, a number between 1 and 6. Each Index has been assigned a Color and Health rating and that is displayed too.

