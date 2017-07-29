### Procedure:
#### Download med-3.2.0
```
http://files.salome-platform.org/Salome/other/med-3.2.0.tar.gz
```
#### Patchs of https://aur.archlinux.org/packages/med/
#### Apply patch
```
patch -p0 < patch-include_2.3.6_med.h.in
patch -p0 < patch-include_med.h.in
patch -p0 < patch-src_2.3.6_ci_MEDequivInfo.c
patch -p0 < patch-int2long
```
