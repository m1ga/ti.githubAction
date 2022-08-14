# Github Action to build a Titanium app

Action is inside [.github/workflows/main.yml](.github/workflows/main.yml)

App is a default Alloy demo app.

## What it does
* Installs all needed tools (node, java, Android SDK)
* downloads latest Titanium SDK
* builds a debug app (`ti build -p android -b -l info`)
* attaches the APK as an action artifact
