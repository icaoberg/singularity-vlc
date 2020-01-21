Bootstrap: docker
From: debian:latest

IncludeCmd: yes

%labels
    MAINTAINER icaoberg@cmu.edu
    WEBSITE http://www.cbd.cmu.edu/icaoberg
    VERSION 1.0

%post
    apt-get update && apt-get install -y vlc

####################################################################################
%appenv vlc
    APP=/usr/bin/vlc
    export APP

%apphelp vlc
    For more information about goto visit https://www.videolan.org

%apprun vlc
    vlc "$@"
