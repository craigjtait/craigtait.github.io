## craigjtait.github.io

# Cisco Devices Web Engine Examples

This project contains examples of some ways to demo the web engine on Cisco RoomOS devices.

## File descriptions

* **NameThatSound.html**: A simple game to show the ability of the web engine to play media. The QR code redirects to a [Google Form](https://forms.gle/1zhA6rtuVJaSgcQ78) for the game. Add this via a UI Extension on a Desk or Board series endpoint (touch screen enabled)
* **helpVideo.html**: Similar to the above, an example showing embedded video media as an example library of help videos. Best on a touch-enabled device. The video has no sound.
* **helpWidget.html**: a webWidget example. Deploy on any endpoint as a UI Extension. The widget will display a QR code (directs to the [web widgets help article](https://help.webex.com/en-us/article/nrsrs8f/Set-up-web-widgets-on-Board,-Desk,-and-Room-Series-devices) on help.webex.com). The widget refreshes with two sets of example text.
* **rotateImages.html**: best deployed as a [persistent web app](https://help.webex.com/en-us/article/ohq3u6/Configure-persistent-web-apps-on-a-Room-Navigator) on a Navigator or [digital signage](https://help.webex.com/en-us/article/nmd8log/Enable-digital-signage-on-Board,-Desk,-and-Room-Series-devices) on a desk, room, or board series. The page will rotate through several stock photographs every few seconds.

## Using the pages

Currently index.html, if called without parameters, will display a basic 'Project Selector' page, with a simple reminder to use dest=[destination HTML page] as a URL parameter.

For example:
https://craigjtait.github.io/index.html?dest=NameThatSound.html

Requesting the html page directly will also work.

For example:
https://craigjtait.github.io/NameThatSound.html