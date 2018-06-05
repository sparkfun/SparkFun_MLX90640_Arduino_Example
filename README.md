SparkFun MLX90640 Arduino Example
========================================

![SparkFun Qwiic IR Array - MLX90640](https://cdn.sparkfun.com//assets/parts/1/3/0/1/5/SparkFun-MLX90640-Waving.png)

[*SparkX Qwiic IR Array - MLX90640 (SPX-14769)*](https://www.sparkfun.com/products/14769)

This repo contains Arduino sketches that show how to output temperature data from the MLX90640 sensor. We've also included a Processing app in Example 2 to read in the values over the serial port and visualize them.

The MLX90640 contains a 32x28 array of thermopile sensors creating, in essence, a low resolution thermal imaging camera. As the images show you can detect surface temperatures from many feet away with an accuracy of ±1.5°C (best case). We’ve packaged the MLX90640 on an easy to use Qwiic board with mounting holes and a smattering of decoupling caps. We’ve written an example Arduino sketch and Processing app to get started with the sensor quickly!

The MLX90640 occupies a very interesting spot in the thermal imaging space. It is much higher resolution than the Panasonic Grid-EYE and much lower cost than the FLiR Lepton cameras. A very exciting advancement!

**Not Uno Compatible:** The MLX90640 requires complex calculations by the host platform. A regular Uno doesn't have enough RAM or flash to complete the complex computations required to turn the raw pixel data into temperature data. You will need a microcontroller with 20,000 bytes or more of RAM. We recommend a Teensy 3.1 or above.

SparkFun labored with love to create this code. Feel like supporting open source hardware? 
Buy a [breakout board](https://www.sparkfun.com/products/14769) from SparkFun!

Repository Contents
-------------------

* **/Documents** - Datasheets
* **/Firmware** - Contains the sketches that Processing app to implement the visualizer

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release any derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.