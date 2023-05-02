# OpenIPC Wiki
[Table of Content](../README.md)

A collection of practical networking perversions
------------------------------------------------


### XiongMai, HI3518EV100

```
For U-boot network
    setenv phyaddru 1
    setenv phyaddrd 2
    setenv mdio_intf rmii
    saveenv

For Linux network
    setenv extras 'hieth.phyaddru=1 hieth.phyaddrd=2'; saveenv
```

### CamHi/HiChip/Xin, HI3518EV200

```
For U-boot network
    setenv phyaddru 0
    setenv phyaddrd 1
    saveenv
```
### HiWatch DS-I120/DS-I122, HI3518CV100

```
For U-boot network
    setenv phyaddru 3
    saveenv

For Linux network
    setenv extras 'hieth.phyaddru=3 hieth.mdioifu=0'
    saveenv
```
