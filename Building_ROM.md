# Building ProjectX

To get started with ProjectX, you'll need to get
familiar with [Git and Repo](http://source.android.com/source/version-control.html).

## Create the directories

You will need to set up some directories in your build environment.

* To create them run:

		mkdir -p ~/bin
		mkdir -p ~/px

## Downloading repo

    curl http://commondatastorage.googleapis.com/git-repo-downloads/repo > ~/bin/repo
    chmod a+x ~/bin/repo

## Initialising ProjectX

    cd ~/px
    repo init -u git://github.com/ProjectX-Android/manifest.git -b lollipop-5.1

## Syncing your Folder

    repo sync -j#
   
"#" is number of jobs you want to give for your downloading source. I use 2 to 4, Now it will download the Sources needed to build the Rom. Download will be huge 13GB to 14GB so be patient since it depends on your Internet Speed.

## Building

**build commands comming soon**

