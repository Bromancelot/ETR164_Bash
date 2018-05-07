# **Boredom Blocker**:  Installing RecalBox and Kodi
## This is a **How-To guide** on how to turn your **Raspberry Pi** into a classic game emulator, and Media server for your home network. This is a project that I worked on for one of my college classes in the spring semester of 2018. I decided to call it Boredom Blocker, just for aesthetic purposes. 



### What you will need:

- **Raspberry Pi 3**
- **Router and/or Modem**
- **Micro SD Card**
- **(Optional) Portable USB Drive** 
- **RecalBox OS**
- **Ethernet Cords**
- **HDMI Cable**
- **External Harddrive (or knownledge of Network Sharing protocols)**
- **PC Gaming Controller**
- **Host Computer**



##### **Step 1:** Download Recalbox
The first thing you’ll need to do is to download the [Recalbox OS](https://www.recalbox.com/) from their website. This will take a couple minutes depending on your PC specs and/or home internet connection.![Imgur](https://i.imgur.com/xGfr1R1.png)

**Be sure to choose the correct OS when downloading.** ![Imgur](https://i.imgur.com/X75WdK7.png)

##### **Step 2:** Converting your USB Drive into a Bootable drive

There are many options for this step when it comes to the bootable drive programs. I personally used [Etcher](https://etcher.io/) for this step. It was simple and the process was relatively quick.
(Another good boot drive converter is [Rufus](https://rufus.akeo.ie). There are plenty out there, just use whichever one strikes your fancy.)
![Imgur](https://i.imgur.com/n4DnIk7.png)

 
- After the download has finished, plug your SD or USB drive into your computer.
- Launch Etcher and follow the instructions it provides. Select the RecalBox **.img file** -> Select your **SD Card** -> "Flash"

This may take a few minutes to do.

- Then simply insert the micro SD into your Raspberry Pi, plug in the HDMI, the keyboard and the power cable. Your Raspberry Pi boots and the installer does the rest! ![Imgur](https://i.imgur.com/6DVczTG.jpg)



Once your Raspberry Pi boots up, you will be greeted with a new menu screen to navigate. From here you can select any of the included classic gaming consoles, and games to play. There are a few that come pre-installed on RecalBox, but the majority of these you will need to provide yourself. We will get to that later. ![Imgur](https://i.imgur.com/lELjTwo.jpg)


##### **Step 3:** Setting up your Raspberry Pi as a Media Center
Now that you have everything installed, you need to navigate to the main menu and select "Kodi". ![Imgur](https://i.imgur.com/iCXakkg.png)From here you will be greeted by Kodi's menu interface. You can Set up your Movies, TV shows, Music, and Photos. Once you have fiddled with files and set everything to your liking, it's time to move on to the network settings.  
- Click on the gear icon at the top of your menu bar, and navigate to **Service Settings**.
- Scroll down to **UPnP / DLNA** and turn on **Share my libraries**

Doing this will enable your **host device** to share it's media library with another other device on your network that has Kodi installed.

![Imgur](https://i.imgur.com/DR7x9J0.jpg)


Don't worry, this is easier than it seems. Goto [Kodi's Website](https://kodi.tv/download) and download the software from there. Select whatever OS you are using, and install it. ![Imgur](https://i.imgur.com/KDnaNGV.png)

Now that you have Kodi installed on your other device, goto the option to expand/populate your video library. Select the share from your host device, and the program will do the rest. ![Imgur](https://i.imgur.com/XHoN4ty.jpg)

Profit.
![Imgur](https://i.imgur.com/tb8iD6J.jpg)

