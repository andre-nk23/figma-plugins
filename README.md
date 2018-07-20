# Figma Plugins Panel — v.2.0
The unofficial plugins panel for Figma App.  

[Changelog](#new-in-this-version)  
[Installation](#installation)  
[How to use](#how-to-use-the-panel)    
[Faqs and Troubleshooting](#faqs-and-troubleshooting)  

![alt text](https://raw.githubusercontent.com/PaperTiger/figma-plugins/master/cover.jpg?token=AHoqgaAnAQoQtEygmvWrsvbW781LSID-ks5apoIFwA%3D%3D "Figma Plugin Panel Cover")

---

## New in this version
#### 2.0 

**General**
- [NEW] Completely revamped Plugin Panel now using React
- [NEW] Panel is now available natively on the Desktop Figma App on Mac. [Download the client below](#installation).
- [NEW] Added a new extension for Firefox. [Download the extension](#installation).
- [NEW] Added a PDF Export Plugin, Credits (https://figma-pdf.gweltaz-calori.com/)  

**The Dark UI Plugin**
- [NEW] Better and improved color palette  
- [NEW] Now the Canvas's Background color will change when the plugin is activated  
- [IMPROVEMENT] Better browser support  
- [FIX] A lot of bug fixes 

#### 1.0.5
- [IMPROVEMENT] Bug Fixes, Better browsers support

#### 1.0
- Initial Release

---

## Installation

### Figma Desktop App (Mac Only) - 'Download Required'
- Download and Install the Figma Desktop App Client below
[Figma Desktop App w/ Plugin Panel](figma-app-latest.zip)

[**How to solve 'Figma is Damaged can't be opened' alert on Mac.**](#faqs-and-troubleshooting)

### Install the plugin on Chrome 64+
- Download and Install the Chrome Extension here:
http://bit.ly/2FfdXUa

### Install the plugin on Firefox 61+
- Download and Install the Firefox Extension here:
https://mzl.la/2L6Kd2N

---

## How to Use the Panel
Look for the ```Plugin Panel Button``` on the toolbar.

![alt text](https://raw.githubusercontent.com/PaperTiger/figma-plugins/master/panel-preview.png "Figma Plugin Panel Preview")
---

## Faqs and Troubleshooting

### Desktop App
#### I'm getting the error 'Figma is damaged and can't be opened'.
The app is built on top of the Figma Beta Desktop App, which might require some quick configuration.

1. Launch this Terminal command: ```sudo spctl --master-disable```
2. Go to ```System Preferences > Security and Privacy```, then select ```Anywhere``` from the ```Allow apps downloaded from:``` section.

#### I can't find the plugin Icon on the Toolbar.
The Plugin Button is available on only the ```File Browser Tab and the Editor```. If the button doesn't show up, try to close and restart the app. 

#### Is there any Desktop App Client for Windows?
- We don't support a of the Plugins Panel on Windows at the moment. If you're developer interested in porting the panel on Win, feel free to get in touch with us at team@papertiger.com

--

### Dark Theme Plugin
#### The rulers' color is still white.
At the moment there's no way to change the colors / theme of the rulers on Figma. 

#### Some UI elements look unstyled.
We tried our best to make sure that any element get the correct styling, because of the complexilty of the app and all its possible scenarios, some components may needs some tweaks. If you spot something feel free to shot us a screenshot at team@papertiger.com

--

### Generate PDF Plugin
#### I'm getting the error 'The file key is invalid'
Make sure to turn on ```Public Access``` on your file by clicking on the ```Share Button``` then ```Enable link access```

---

## For any other issue or question send us a mail at team@papertiger.com
