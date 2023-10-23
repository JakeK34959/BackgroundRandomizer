# Background Randomizer
Theme background randomizer for clearvision themes

## Setup

### Step 1: Install Clearvision
Download and install the latest version of ClearVision from (here)[https://betterdiscord.app/theme/ClearVision] 
Note: This plugin will most likely not work with anything other than ClearVision

### Step 2: Install the plugin
Install the BackgroundRandomizer.plugin.js file into your plugin folder.

### Step 3: Configure
Open the BackgroundRandomizer.plugin.js file through the edit button on the plugins page on discord or through your IDE

### Step 4: Add your backgrounds
Go to line 16 ```this.bgurls = [];``` and add in your images like this ```this.bgurls = ["imglink.com/img.jpg", "imglink.com/img2.jpg", "imglink.com/img3.jpg"]``` make sure each link is in quotes and separated with a comma, the last one does not need a comma after it so make sure you don't add one.
Note: ClearVision by default doesn't work with local images so you have to upload them to a site like Imgur or Flickr and get the image links, they need to end in .jpg 

### Step 5: Link your ClearVision theme file
First find and copy the full file path to the ClearVision theme file it should be something like ClearVision_v6.theme.css the easiest way is to go to your themes tab in your better discord settings and click go to themes folder. Take the full file path and paste it in line 11 like this ```const cssFilePath = 'file/path/BetterDiscord/themes/ClearVision_v6.theme.css';```

### Step 6: Set delay (Optional)
By default this plugin uses a delay of 30 minutes if you'd like to change this delay to a different amount of time go to line 9 ```const delay_min = 30``` and change the 30 to another mount and keep in mind that it must be in minutes. 
