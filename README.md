SparkFun GPS Dead Reckoning Breakout - NEO-M8U (Qwiic)
========================================

[![SparkFun GPS Dead Reckoning Breakout - NEO-M8U (Qwiic)](https://cdn.sparkfun.com/r/600-600//assets/parts/1/5/0/3/7/16329-SparkFun_GPS_Dead_Reckoning_Breakout_-_NEO-M8U__Qwiic_-01.jpg)](https://www.sparkfun.com/products/16329)

[SparkFun GPS Dead Reckoning Breakout - NEO-M8U (Qwiic) [GPS-16329]](https://www.sparkfun.com/products/16329)

The SparkFun NEO-M8U GPS Breakout is a high quality, GPS board with equally impressive configuration options. The NEO-M8U takes advantage of u-blox's Untethered Dead Reckoning (UDR) technology. The module provides continuous navigation without needing to make any electrical connection to a vehicle, thus reducing cost of installation for after-market dead reckoning applications. 

The NEO-M8U module is a 72-channel u-blox M8 engine GNSS receiver, meaning it can receive signals from the GPS, GLONASS, Galileo, and BeiDou constellations with ~2.5 meter accuracy. The module supports concurrent reception of three GNSS systems. The combination of GNSS and integrated 3D sensor measurements on the NEO-M8U provide accurate, real-time positioning rates of up to 30Hz. 

Compared to other GPS modules, this breakout maximizes position accuracy in dense cities or covered areas. Even under poor signal conditions, continuous positioning is provided in urban environments and is also available during complete signal loss (e.g. short tunnels and parking garages). With UDR, position begins as soon as power is applied to the board even before the first GNSS fix is available! Lock time is further reduced with on-board rechargeable battery; you'll have backup power enabling the GPS to get a hot lock within seconds!

Additionally, this u-blox receiver supports I<sup>2</sup>C (u-blox calls this Display Data Channel) which made it perfect for the Qwiic compatibility so we don't have to use up our precious UART ports. Utilizing our handy Qwiic system, no soldering is required to connect it to the rest of your system. However, we still have broken out 0.1"-spaced pins in case you prefer to use a breadboard. 

U-blox based GPS products are configurable using the popular, but dense, windows program called u-center. Plenty of different functions can be configured on the NEO-M8U: baud rates, update rates, geofencing, spoofing detection, external interrupts, SBAS/D-GPS, etc. All of this can be done within the SparkFun Arduino Library!

The SparkFun NEO-M8U GPS Breakout is also equipped with an on-board rechargeable battery that provides power to the RTC on the NEO-M8U.  This reduces the time-to-first fix from a cold start (~26s) to a hot start (~1.5s). The battery will maintain RTC and GNSS orbit data without being connected to power for plenty of time.


Repository Contents
-------------------

* **/Documentation** - Data sheets for the NEO-M8U
* **/Hardware** - Eagle design files (.brd, .sch)
* **/Production** - Production panel files (.brd)

Documentation
--------------
* **[Library](https://github.com/sparkfun/SparkFun_u-blox_GNSS_Arduino_Library)** - Arduino Library the SparkFun GPS ublox products.
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/1166)** - Basic hookup guide for the SparkFun GPS NEO-M8U

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact technical support on our [SparkFun forums](https://forum.sparkfun.com/viewforum.php?f=152).

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
