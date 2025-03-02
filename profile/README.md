# eMedia

We have built an  all-in-one solution for media management to help people create digital value with our AI-driven media library. A fully Integrated, unified, secure application with a built in artificial intelligence powered search engine that organizes all media files into one place.

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

https://emedialibrary.com/knowledge/11/ubuntu-docker-deployments.html
https://emedialibrary.com/knowledge/11/docker-deployment-mac.html

How to build

git clone -b em11 --single-branch git://github.com/entermedia-community/entermedia-core.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/entermedia-server.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/demoall.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/app-emshare.git 
git clone -b em11 --single-branch git://github.com/entermedia-community/extension-openedit.git 
git clone -b master --single-branch git://github.com/entermedia-community/tomcat9.git

Eclipse File | Import | Existing Projects into Workspace Choose each of the main projects and import them, Do not check "Copy projects into workspace"

4.) Install OS Dependencies

 sudo apt-get install --no-install-recommends -y ffmpeg automake libogg0 libogg-dev libvorbis0a libvorbisenc2 x264  lame libimage-exiftool-perl libreoffice unzip git libltdl-dev librsvg2-2 libwmf-bin libxt6 libgomp1 libtiff5-dev libtiff5 libfaac-dev lame imagemagick ghostscript

Install libx264-normal.ffpreset into: /home/USERNAME/.ffmpeg/ *(Skip if already installed.)

5.) Import the EnterMedia Code Style guide

Find the style guide here: entermedia-server/etc/EnterMedia.format

6.) Run your application server

Right click on demoall/etc/demoall Tomcat.launch | Debug As You should now be able to connect to the webapp by going to http://localhost:8080/ *(Must be launched again everytime eclipsed is closed.)


# License
This project is licensed under the LGPL

Acknowledgements
This project is sponsored by eMediaLibrary.com 
