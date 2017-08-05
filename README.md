VaLauncher
==========

A fast dmenu-like application launcher built upon gtk3
-------------------------------------------

Use `Tab` to move forward through the completion list and `Shift+Tab` to move backward.

*Features*:

 * dmenu-like autocompletion 
 * command history
 * lightweight and fast

### Dependencies:

* GTK+3
* Vala
* Libgee 0.10.x (for earlier versions simply revert 4ef8528abd6d5d9c971120b67abc9f37eef413cd)
* CMake

### Building:

#### For Maintainer

```bash
cmake -DCMAKE_INSTALL_PREFIX:PATH=/usr .
make
make install
```

#### For Developers

```bash
mkdir build
cmake .
make
./src/valauncher
```
