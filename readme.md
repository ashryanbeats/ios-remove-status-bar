# Removing Status Bar from iOS

All this repo does is show how to remove the Status Bar from an iOS app.

## Remove from Interface Builder
In the storyboard:

1. Click the View Controller Icon
1. Set "Status Bar" to "None"

## Remove from the app
In `info.plist`:

1. Add "View controller-based status bar appearance" and set to "NO"
1. Add "Status bar is initially hidden" and set to "YES"