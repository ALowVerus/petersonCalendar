# Lobster Calendar
A life planning Chrome Extension for aspiring lobsters.

Built as a Google Chrome Extension, this app interfaces with Google Calendar to allow users to easily plan out their life goals and see their progress towards their goals from within the Google Calendar interface.

Eventually, the app will have the same functionality as this Google Sheet:
<https://docs.google.com/spreadsheets/d/1u5jai7LVdzpqB-Rp6Ia44sGtLJ2a31-xC_6iwjhHbwQ/edit#gid=0>

The app can be manually uploaded to a user's Chrome Extension page by:
- downloading the package,
- unzipping it,
- navigating to <chrome://extensions/> in Google Chrome,
- switching on Developer Mode in the top right of the screen, and
- clicking "Load unpacked" and selecting the unzipped folder.

Since the app is not yet approved by the Chrome Store, using it will require setting up a person OAuth key. This can be accomplished by:
- navigating to <https://console.developers.google.com/apis/dashboard>,
- creating a new project using the drop-down menu at the top of the screen,
- clicking "Credentials" in the left sidebar,
- clicking "Create credentials" and selecting "OAuth client ID",
- selecting "Chrome App",
- inputting the Chrome Extension ID as your Store ID when prompted,
- following other prompts until returned to the "Credentials" page,
- copying the newly-created OAuth2 client ID,
- pasting it into the XXXXXXXX area of "manifest_example.json" in your downloaded copy of the app, and
- renaming "manifest_example.json" to "manifest.json".

Once this is all done, you should be able to see your Google Calendars' names and some of your primary calendar's events appear when you open the extension from the top right of your screen.
