# singularity-vlc

## About
Singularity recipe for [VLC](https://www.videolan.org/vlc/index.html).

## Pre-requisites

* [Singularity v3.5.+](https://sylabs.io/docs/).

## Building the container
```
bash ./build.sh
```

## Get help!
```
singularity help --app vlc vlc.simg
    For more information about goto visit https://www.videolan.org
```

## Running the app
```
singularity run --app vlc singularity-vlc.simg tommy_torres-querido_tommy.mp4
```

![VLC](images/singularity-vlc.gif)

## Disclaimer

[![Wold you buy me some coffee?](https://www.buymeacoffee.com/assets/img/custom_images/orange_img.png)](https://www.buymeacoffee.com/icaoberg)

I am nothing but a humble programmer creating the container for this wonderful app. 

---
[![CBD](http://www.cbd.cmu.edu/wp-content/uploads/2017/07/wordpress-default.png)](http://www.cbd.cmu.edu)

Copyleft © 2019-2020 [icaoberg](http://www.andrew.cmu.edu/~icaoberg) at the [Computational Biology Department](http://www.cbd.cmu.edu) in [Carnegie Mellon University](http://www.cmu.edu)
