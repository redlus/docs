### How does auto-update work?
The auto update (   )feature in testfairy is designed to make it easy for your team to receive builds and ensure they are testing on the latest build of your app.
How to enable auto-update?
First of all, in order for the auto update feature to work, you must have the TestFairy SDK installed in your application.

There are 3 ways of defining auto update for a specific build:
On the build settings screen (for a loaded build):


When you upload a new build via our online upload button :


When you upload a new build via our upload api:
When you load via API set the auto-update parameter to yes when loading the build.

Please note: Auto-Update will upgrade all the previous installations of this app to the current version. When your app starts, the SDK will check if a new version is available and is marked for auto update.
If so, the user will see a message telling him that a new version is ready and if asking him if he wants to updated.
If the user agrees, the new version will download and install on his device. 