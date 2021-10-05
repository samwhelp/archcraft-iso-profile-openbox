

## Original Source

*  GitHub / archcraft-os / [archcraft](https://github.com/archcraft-os/archcraft)


## iso-profile

| iso-profile |
| --- |
| [adjustment-start-from-21.09](profile) |


## Config Path

* [packages.x86_64](adjustment-start/packages.x86_64)
* [customize_airootfs.sh](adjustment-start/airootfs/root/customize_airootfs.sh)

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
