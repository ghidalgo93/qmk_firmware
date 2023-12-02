# ghidalgo93 keymap for kinesis-advantage, using the kint4 base board

My advantage2 uses the [stapleberg kinT mod](https://github.com/kinx-project/kint), which uses the kintT keyboard controller as the replacement for the Kinesis.

I'm using the 4.x controller from [this compatabilty list](https://github.com/kinx-project/kint#compatibility-which-teensy-to-use).

Some more info on firmware installation for the particular board can be found [here](https://github.com/kinx-project/kint#installing-the-firmware)

## Compile keymap hex:
```
$ make kinesis/kint41:ghidalgo93
```

## Compile & flash keymap:
```
$ make kinesis/kint41:ghidalgo93:flash
```
