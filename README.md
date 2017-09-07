# sleep_timer
Sleep timer service for macOS.

## Installation
Just download Sleep Timer.workflow and double-click it. Automator will launch and the Service Installer will ask if you want to install the service or open with Automator. Choose 'Install.'

## Usage
You can either invoke the service by clicking on the name of the currently focussed application (i.e. Finder), navigating to the 'Services' menu, and clicking 'Sleep Timer' or by binding a keyboard shortcut to the service (recommended) by going to System Preferences > Keyboard > Shortcuts > Services (from the left menu) > Scroll to the bottom of the right menu and under 'General' you'll find the 'Sleep Timer' service. Just double-click where it says 'None' and set the desired keyboard shortcut.

When invoked, the service will present a dialogue and ask how many minutes you'd like the computer to wait before sleeping. Once set, the service will wait the desired amount of time and then tell Finder to put the machine to sleep.

## Notes
* It sometimes takes a couple seconds for the service to run, you can tell it's working if a little gear appears in the menu bar.
* Some applications can override the shortcut you set, which will cause it to be non-functional.