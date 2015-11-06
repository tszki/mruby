## How to build

    $ CFLAGS="-fPIC" ruby ./minirake

If building failed with following message,

    Don't know how to rake /home/tsuzuki/workspace/mlzbx-mruby/_for_upload/mruby/build/host/mrbgems/mruby-polarssl/polarssl/library/aes.o

followings are needed.

    $ cd build/mrbgems/mruby-polarssl/polarssl/
    $ git submodule init
    $ git submodule update

