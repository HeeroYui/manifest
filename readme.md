Manifest section for ewol framework:
====================================

Install Island:
---------

```{.sh}
pip install island --user
```

Create the tree:
----------------
```{.sh}
mkdir framework
cd framework
island init https://git.heeroyui.org/atria-soft/manifest.git
repo sync
cd ..
```

With ssh keys:
```{.sh}
mkdir framework
cd framework
island init git@git.heeroyui.org:atria-soft/manifest.git
repo sync
cd ..
```

Now all is done ...
