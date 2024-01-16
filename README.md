# Quatt-dashboard
![Example screenshot](https://github.com/jee67/Quatt-dashboard/blob/main/example.png)

Custom Quatt Dashboard where you can read the several (clickable) sensors with the actual realtime data. Also the image changes on behalve of the active working mode.

Since the 28th of November i own a [Quatt Heatpump](https://referral.quatt.io/l/EDGARVEEN29/) (get a €100 discount through this link). As a Home Assistant user i could not wait to start playing with it. 
Marco Boers has created a beatifull Quatt integration (https://github.com/marcoboers/home-assistant-quatt) so that all available sensors are available inside your Home Assistant. So be sure to take a look into that addon. Without that addon, this dashboard won't work.

I really liked the official Quatt app and i like Home Assistant. So i made a first attempt to create a little dashboard inspired by the dashboard from the Quatt app. I am not a novice programmer, and this is my first Github project (i thought it would be the best place to keep all together). This is also my first picture entity i build inside Home Assistant. The chances are that the configuration i used is not correct or there is a better way to config it. So please let me know.

I have tried to make it as easy as possible to add this to your home assistant configuration.

- **Step 1:** Make sure you have add the Marco Boers Quatt Integration (link above). Without this configuration, you did not have the sensors.
- **Step 2:** Download all the images from the folder quatt from this repository and upload them in your Home Assistant configuration in:
Config\www\images
- **Step 3:** add the configuration as shown in configuration.yaml inside your own configuration.yaml file. Make sure you add them in the right section. If you have a Rest: or a -Platform: template section, place the configuration within theme.
- **Step 4:** Edit your dashboard, create a new page if you want to and Add a Card, choose the Picture elements card.
- **Step 5:** Copy the code from the Picture-Entity.yaml file into your picture-element, if every previous steps are correct you would see the example on the right sight of the screen, click save.

You are done and have a custom quatt dashboard like above screenshot.
