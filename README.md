# Game-Collection-Value-Widget
This is a iPhone widget that tracks your game collection value.
This method uses http://pricecharting.com/ to track your collection, without paying for their API.

In order to use this you will need Scriptable a completely app from the App Store, you will also need a blank Google Sheets.

The way this works is instead of contacting an API for information we rip it stright from the webpage,
using the IMPORTXML function on Google Sheets.
Below is a URL for the base document and steps to follow:
https://docs.google.com/spreadsheets/d/1zs__cZk5tq3Cc_be1Xbv9g8a0oPmTvETBtL5vJKU9lE/edit?usp=sharing

1. Make a copy of the document
2. Get the URL of your pricecharting account Collection page, click the "Account" dropdown menu then click "Collection"
3. Place the URL in A1, replacing <<your url>>
4. Click the File dropdown menu then click "Publish to the web" and click publish
5. Enter the spread sheet ID located in the URL and place it in this URL:
https://spreadsheets.google.com/feeds/cells/<<sheet id>>/1/public/full?alt=json
6. Download the code above and paste it into a new script in Scriptable
7. Replace the URL at the top of the script with the URL we made above
8. Save the script
9. On the iPhone home screen, hold down the home button if your phone has one or the screen for newer phones
10. Once the icons are wiggling press the "+" in the upper left corner
11. Scroll down to "Scriptable", tap it and press "Add Widget"
12. Tap the widget and select the script you made
