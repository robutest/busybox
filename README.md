Compiling
=========

Don't forget override "SKIP_STRIP = y" in <Makefile.flags> file for overcoming "stripping error".

make menuconfig
make install

All compiled files have been seen <_install> directory in the busybox.
Then execute "genromfs -v -V "ROM Disk" -f romfs.bin -d <your_compiled_busybox_files> 2> romfs.map". It produces your romfs.bin file.

