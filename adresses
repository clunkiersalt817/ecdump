# MSI CYBORG 12 A12VF-010TH ( 15K1IMS1.110 ) EC

I'm was figuring out the values of EC memory based on MSI Center setting. Thanks to [RW-Everything](http://rweverything.com/) for the amazing tool.

## Charge Threadshold

```
address: 0xD7
possible values: 0xE4 ( stop 100% ), 0xD0 ( under 70%, stop at 80% ), 0xBC ( under 50%, stop at 60% )
```

## Web Cam Control

```
address: 0x2E
possible values: 0x0B ( on ), 0x09 ( off )
```

## Mic Mute

```
address: 0x2C
possible values: 0x00 ( on ), 0x02 ( off )
```

## Speaker Mute

```
address: 0x2D
possible values: 0x00 ( on ), 0x02 ( off )
```

## User Scenario ( Performance Mode )

```
address: 0xD2
possible values: 0xC4 ( Extreme ), 0xC1 ( Balanced ), 0xC2 ( Super Battery )
```

Notes:

* to toggle `Super Battery`, we'll also need to write `0x0F` ( on ) or `0x00` ( off ) to address `0xEB`.
* Silent mode in MSI Center is equivalent to `Balanced` mode with `Silent` fan mode.

## Fan Control

Fan mode

```
address: 0xD4
possible values: 0x0D ( Auto ), 0x1D ( Silent ), 0x8D ( Advanced )
```

Cooler Boost

```
address: 0x98
possible values: 0x06 ( Off ), 0x86 ( On )
```

This laptop has just 1 fan setting.

```
number of sub-fan setting: 6
starting address: 0x72
end address: 0x77 (0x72 + 5)
```

## Keyboard Backlight

```
address: 0xD3
possible values: 0x80 ( off ), 0x81 ( low ), 0x82 ( mid ), 0x83 ( high )
```

## Win - Fn Swap

```
address: 0xE8
possible values: 0x01 ( win - fn ), 0x11 ( fn - win )
```

## USB Power Share

```
address: 0xBF
possible values: 0x08 ( off ), 0x28 ( on )
```

## Sensors

```
CPU temperature address: 0x68
GPU temperature address: 0x80
Battery charge address: 0x42
Battery charging status address: 0x31
Fan 1 speed address: 0xC9 ( B5 - 2651, B1 - 2711, CD - 2400, C8 - 2341, etc. but not sure? How they store that value into 1 byte )
```
