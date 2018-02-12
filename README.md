# ConfigurableFirmata with NeoPixel

StandardFirmata does not support NeoPixel.
And this ConfigurableFirmata support NeoPixel.

If you want to use Arduino uno, Gobot(branch : feature/neopixels), and NeoPixel,
your install This ConfigurableFirmata to Arduino uno.

## Prepare

```
$ pio lib install ConfigurableFirmata
$ cd lib
$ git clone git@github.com:hybridgroup/FirmataNeopixels.git
```

## Build

```
$ pio run
```

## Upload

```
$ pio run --target upload
```

## Link

- [Gobot](http://gobot.io)
  branch : feature/neopixels
- [ConfigurableFirmata](https://github.com/firmata/ConfigurableFirmata)
- [FirmataNeopixels](https://github.com/hybridgroup/FirmataNeopixels)
