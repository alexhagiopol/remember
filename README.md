# remember
Collection of useful commands I always forget.

##### Resize all images in a folder with Image Magick
  
    for i in *.jpg; do convert $i -resize 500x $i; done

##### Install Terminator on Ubuntu

    sudo add-apt-repository ppa:gnome-terminator
    sudo apt-get update
    sudo apt-get install terminator

##### Install NVidia Drivers on Ubuntu

    sudo add-apt-repository ppa:xorg-edgers/ppa
    sudo apt-get update
    sudo apt-get install nvidia-367
