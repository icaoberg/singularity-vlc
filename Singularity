Bootstrap: docker
From: ubuntu:16.04

IncludeCmd: yes

%labels
    MAINTAINER icaoberg@cmu.edu
    WEBSITE http://www.cbd.cmu.edu/icaoberg
    VERSION 1.0

%runscript
    exec /bin/bash "$@"

%post
    echo "Install VLC"
    apt-get update && apt-get install -y vlc

    if [ ! -d /images ]; then mkdir /images; fi
    if [ ! -d /projects ]; then mkdir /containers; fi
    if [ ! -d /containers ]; then mkdir /containers; fi
    if [ ! -d /share ]; then mkdir /share; fi
    if [ ! -d /scratch ]; then mkdir /scratch; fi

####################################################################################
%appenv vlc
    APP=/usr/bin/vlc
    export APP

%apphelp vlc
    For more information about goto visit https://www.videolan.org

%apprun vlc
    vlc "$@"
