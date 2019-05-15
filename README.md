# Node Red UI Alarm Panel - By Manzn

## Disclaimer
The repo is built on the code from Manzn. I have only made very minor changes and converted code to English.
Feel free to create a new issue or pull request here **if you downloaded code from my repo**.
The corresponding HA thread https://community.home-assistant.io/t/node-red-ui-alarm-panel-for-yet-another-take-on-an-alarm-system

## Installation
TO allow Node Red UI alarm to talk to Yet another Alarm Panel you will need to turn on MQTT in YAAP and turn on Override Code.

1.  Install Node Red then under the addon add port 1880 to the Network section. Press save.
2.  Open Node Red then from the hamburger menu goto manage palette then click install tab then type node-red-dashboard.
    Click install on node-red-dashboard.
3.  Then from the hamburger menu click import then clipboard copy then paste the code from alarmpanel.json into the box.
4.  From there you will need to make a couple of changes which I have added notes to in the flow.
5.  Last thing to do is copy the images to /config/www/images/
