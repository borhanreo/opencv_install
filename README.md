#OPENCV Install on ubuntu 18.04
##### Check Python Version
    $ python3 --version
    Python 3.6.5
##### Pakage update & upgrade 
    $ sudo apt-get update
    $ sudo apt-get upgrade
    $ sudo apt-get install build-essential cmake unzip pkg-config
    $ sudo apt-get install libjpeg-dev libpng-dev libtiff-dev
    $ sudo apt-get install libavcodec-dev libavformat-dev libswscale-dev libv4l-dev
    $ sudo apt-get install libxvidcore-dev libx264-dev 	
    $ sudo apt-get install libgtk-3-dev
    $ sudo apt-get install libatlas-base-dev gfortran
    $ sudo apt-get install python3-dev
##### Download the official OpenCV source
    $ cd ~
    $ wget -O opencv.zip https://github.com/opencv/opencv/archive/3.4.1.zip
    $ wget -O opencv_contrib.zip https://github.com/opencv/opencv_contrib/archive/3.4.1.zip    
##### Issue on update
    $ sudo rm -r /etc/apt/sources.list.d
    $ sudo apt-get update
    
            