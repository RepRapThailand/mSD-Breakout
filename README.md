# mSD-Breakout
Breakout with microSD socket and level shifter.

![mSD-Breakout](https://github.com/watterott/mSD-Breakout/raw/master/hardware/mSD-Breakout_v10.jpg)

* microSD socket (SPI) support SD and SDHC cards (up to 32GB)
* 5V tolerant inputs (on-board level shifter)
* on-board 3.3V voltage regulator


## Shop
* [mSD-Breakout](http://www.watterott.com/en/mSD-Breakout)


## Hardware and Software
* [Schematics + Layout](https://github.com/watterott/mSD-Breakout/tree/master/hardware)

* Arduino Connection (IDE Example Sketches: ```File->Examples->SD```):
    ```
    Uno -> Breakout
    ---------------
    5V  -> 5V
    GND -> GND
    13  -> CLK
    12  -> DO (MISO)
    11  -> DI (MOSI)
     4  -> CS
    
    Mega -> Breakout
    ----------------
    5V   -> 5V
    GND  -> GND
    52   -> CLK
    50   -> DO (MISO)
    51   -> DI (MOSI)
     4   -> CS
    ```
