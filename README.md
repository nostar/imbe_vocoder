# imbe_vocoder
imbe_vocoder library from osmocom OP25

# Building
for all linux flavors and MacOS:
```
git clone https://github.com/nostar/imbe_vocoder
cd imbe_vocoder
make
sudo make install
sudo ldconfig
```
There are example makefiles for andoird and windows.  Variables like compilers and paths to sdk/ndk may need to be modified for your environment.  On windows and andoird, make install is not used.  Instead, manually place the libmbe_vocoder.a library in the correct location manually, and add a -L flag to your compiler flags if necessary.
