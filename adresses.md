# MSI Bravo 15 B5DD ( 158KEMS1.104 ) EC

## Charge Threadshold

```
address: 0xEF
possible values: 0xE4 ( 100% all the time ), 0xD0 ( under 70%, stop at 80% ), 0xBC ( under 50%, stop at 60% )
```

## Web Cam Control

```
address: 0x2E
possible values: 0x4B ( on ), 0x49 ( off )
```

## Mic Mute

```
address: 0x2B
possible values: 0x00 ( on ), 0x02 ( off )
```

## Speaker Mute

```
address: 0x2B
possible values: 0x80 ( on ), 0x84 ( off )
```

## User Scenario ( Performance Mode )

```
address: 0xF2
possible values: 0xC4 ( Extreme ), 0xC1 ( Balanced ), 0xC2 ( Super Battery )
```

## Fan Control

Cooler Boost

```
address: 0x98
possible values: 0x02 ( Off ), 0x82 ( On )
```

## Keyboard Backlight

```
address: 0xF3
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
