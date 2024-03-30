# CamPhish

<img width="647" alt="image" src="https://github.com/LakshyaSharma207/CamPhish/assets/124886897/85946c32-a5b1-4396-8581-9fd6c3f3460f">

This is a tool originaly created by thelinuxchoice and TechChip, but has experienced changes throughout the years. Here I simple offer my own little changes like a believable zoom template and a changed bash script. The script now also generates a scannable QR code in the root folder along with the link and serves files with serveo by default. It also sends data asynchronously now making it more unnoticeable.

# What is CamPhish

CAMPHISH is a technique to take cam shots of a target's phone front camera or PC webcam. CAMPHISH Hosts a fake website on a PHP server and uses Cloudflare & serveo to generate a link that we will forward to the target, which can be used over the internet. the website asks for camera permission and if the target allows it, this tool grabs cam shots of the target's device.

# Features

In this tool, there are three automatic webpage templates for engaged targets on the webpage to get more pictures of the cam

- Festival Wishing
- Live YouTube TV
- Online Zoom Meeting 
simply enter the festival name or youtube's video ID when prompted

# Installing and requirements

This tool require PHP for webserver, SSH or serveo link. First run following command on your terminal

## For Kali Linux

`apt-get -y install php openssh wget qrencode`

## For MACOS

Have homebrew installed then execute the following -

`brew install php openssh wget qrencode`

## For Windows 

A windows remake of the tool is also available at - [https://github.com/Arnob231/CAMPHISH]

### After executing the above commands, to run the script navigate to the directory and - 

`bash camphish.sh`

### Original Source Code can be found in this repo - https://github.com/techchipnet/CamPhish
