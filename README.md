$ curl https://storage.googleapis.com/git-repo-downloads/repo > repo
$ chmod a+x repo
$ sudo mv repo /usr/local/bin/
$ repo --help
$ XILINX_SOURCES=/path/to/xilinx/sources
$ mkdir -p $XILINX_SOURCES
$ cd $XILINX_SOURCES
$ repo init -u git://github.com/Xilinx/yocto-manifests.git -b rel-v2017.3
$ repo sync
