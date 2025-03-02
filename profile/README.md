# Quick Start

All-in-one solution for media management to help people create their digital value. A fully Integrated, unified, secure application with a built in artificial intelligence powered search engine that organizes all media files into one place.

eMediaLibrary is 100% Open Source forever, free from censorship, fully independent with no third party dependencies. 

All your cloud storage into one, interconnected and secure interface.

More details on our web site https://emedialibrary.com

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)
- [License](#license)
- [Acknowledgements](#acknowledgements)

## Installation

Instructions on how to install and run the project.

Run with Docker on Unbuntu: 
https://emedialibrary.com/knowledge/11/ubuntu-docker-deployments.html

Run with Docker on MacOS: 
https://emedialibrary.com/knowledge/11/docker-deployment-mac.html

# Build Your Own Version

1.) How to build and run locally:
```
git clone -b em11 --single-branch git://github.com/entermedia-community/entermedia-core.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/entermedia-server.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/demoall.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/app-emshare.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/extension-openedit.git 
git clone -b master --single-branch git://github.com/entermedia-community/tomcat9.git
```
Eclipse File | Import | Existing Projects into Workspace Choose each of the main projects and import them, Do not check "Copy projects into workspace"

2.) Install OS Dependencies
```
 sudo apt-get install --no-install-recommends -y ffmpeg automake libogg0 libogg-dev libvorbis0a libvorbisenc2 x264  lame libimage-exiftool-perl libreoffice unzip git libltdl-dev librsvg2-2 libwmf-bin libxt6 libgomp1 libtiff5-dev libtiff5 libfaac-dev lame imagemagick ghostscript
```
Copy [libx264-normal.ffpreset](https://github.com/entermedia-community/entermediadb-docker/blob/master/ubuntu/conf/libx264-normal.ffpreset) into: /home/USERNAME/.ffmpeg/ *(Skip if already installed.)

3.) Import the EnterMedia Code Style guide

Find the style guide here: entermedia-server/etc/EnterMedia.format

4.) Run your application server

Right click on demoall/etc/demoall Tomcat.launch | Debug As You should now be able to connect to the webapp by going to http://localhost:8080/ *(Must be launched again everytime eclipsed is closed.)

# Contributing

Reach out to us on Reddit https://Reddit.com/user/digital_legacy or send us a pull request or email us: tech @ eMediaLibrary.com team. 

We will need a open source contributor license signed to accept your contributions. 

# License
This project is licensed under the LGPL

# Acknowledgements
This project is sponsored by eMediaLibrary.com 
