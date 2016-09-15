Manifest section for ewol framework:
====================================

Get repo:
---------

see: http://source.android.com/source/downloading.html#installing-repo
Generic
```{.sh}
mkdir ~/.bin
PATH=~/.bin:$PATH
curl https://storage.googleapis.com/git-repo-downloads/repo > ~/.bin/repo
chmod a+x ~/.bin/repo
```
on archlinux:
```{.sh}
pacman -S repo
```

On ubuntu/debian
```{.sh}
sudo apt-get install repo
```


Create the tree:
----------------
```{.sh}
mkdir framework
cd framework
repo init -u https://github.com/atria-soft/manifest.git
repo sync -j8
cd ..
```

Now all is done ...
