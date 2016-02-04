# Arduino-Tropo-Home-Control

[![Join the chat at https://gitter.im/tchatow/Arduino-Tropo-Home-Control](https://badges.gitter.im/tchatow/Arduino-Tropo-Home-Control.svg)](https://gitter.im/tchatow/Arduino-Tropo-Home-Control?utm_source=badge&utm_medium=badge&utm_campaign=pr-badge&utm_content=badge)
My project that will allow devices to be remotly control through Tropo

The way this program works is that the Tropo application will contact AWS IOT with new states of devices. Then, the Arduino will check for updates to devices every so often and apply those states.
