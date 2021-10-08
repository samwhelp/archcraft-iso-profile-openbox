

## Original Source

*  GitHub / archcraft-os / [archcraft](https://github.com/archcraft-os/archcraft)


## Note

* use lightdm

## iso-profile

| iso-profile |
| --- |
| [adjustment-start-from-21.09](profile) |


## Config Path

| Path | Note |
| --- | --- |
| [packages.x86_64](adjustment-start/packages.x86_64) | add your favorite packages |
| [customize_airootfs.sh](adjustment-start/airootfs/root/customize_airootfs.sh) | custom your favorite action |


## Add Archcraft Adjustment Packages

| Package | Note |
| --- | --- |
| [archcraft-adjustment-mirrorlist](https://github.com/samwhelp/archcraft-adjustment-package/tree/main/base/archcraft-adjustment-mirrorlist) | [archcraft-adjustment-repository](https://github.com/samwhelp/archcraft-adjustment-repository) pacman.conf mirrorlist |
| [archcraft-adjustment-hello](https://github.com/samwhelp/archcraft-adjustment-package/tree/main/demo/archcraft-adjustment-hello) | install for test [archcraft-adjustment-mirrorlist](https://github.com/samwhelp/archcraft-adjustment-package/tree/main/base/archcraft-adjustment-mirrorlist) |
| [archcraft-modeling-fcitx-chewing](https://github.com/samwhelp/archcraft-adjustment-package/tree/main/core/im/archcraft-modeling-fcitx-chewing) | for input method fcitx-chewing skel config |


## Howto

### prepare

to install [archiso](https://archlinux.org/packages/extra/any/archiso/)

``` sh
make prepare
```


### build

to build iso

``` sh
make build
```


### run_iso

to test iso

```
make run_iso
```

### clean

to clean dir: [work, out]

``` sh
make clean
```


## Reference

* https://wiki.archlinux.org/title/archiso
