SparkFun MLX90640 Arduino Example
========================================

<table class="table table-hover table-striped table-bordered">
  <tr align="center">
   <td><a href="https://www.sparkfun.com/products/14843"><img src="https://cdn.sparkfun.com/r/500-500/assets/parts/1/3/1/1/3/14843-SparkFun_IR_Array_Breakout_-_110_Degree_FOV__MLX90640__Qwiic_-01.jpg" alt="Qwiic IR Array (MLX90640-110x75 FOV)"></a></td>
   <td><a href="https://www.sparkfun.com/products/14844"><img src="https://cdn.sparkfun.com/r/500-500/assets/parts/1/3/1/1/4/14844-SparkFun_IR_Array_Breakout_-_55_Degree_FOV__MLX90640__Qwiic_-01.jpg" alt="Qwiic IR Array (MLX90640-55x35 FOV)"></a></td>
  </tr>
  <tr align="center">
    <td>Qwiic IR Array (MLX90640-110x75 FOV) [<a href="https://www.sparkfun.com/products/14843">SEN-14843</a>]</td>
    <td>Qwiic IR Array (MLX90640-55x35 FOV) [<a href="https://www.sparkfun.com/products/14844">SEN-14844</a>]</td>
  </tr>
</table>

This repo contains Arduino sketches that show how to output temperature data from the MLX90640 sensor. We've also included a Processing app in Example 2 to read in the values over the serial port and visualize them.


<p align="center">
  <a href="https://cdn.sparkfun.com//assets/parts/1/3/0/1/5/SparkFun-MLX90640-Waving.png"><img src="https://cdn.sparkfun.com//assets/parts/1/3/0/1/5/SparkFun-MLX90640-Waving.png" alt="SparkFun Qwiic IR Array - MLX90640"></a>
</p>

The MLX90640 contains a 32x24 array of thermopile sensors creating, in essence, a low resolution thermal imaging camera. As the images show you can detect surface temperatures from many feet away with an accuracy of ±1.5°C (best case). We’ve packaged the MLX90640 on an easy to use Qwiic board with mounting holes and a smattering of decoupling caps. We’ve written an example Arduino sketch and Processing app to get started with the sensor quickly!

The MLX90640 occupies a very interesting spot in the thermal imaging space. It is much higher resolution than the Panasonic Grid-EYE and much lower cost than the FLiR Lepton cameras. A very exciting advancement!

**Not Uno Compatible:** The MLX90640 requires complex calculations by the host platform. A regular Uno doesn't have enough RAM or flash to complete the complex computations required to turn the raw pixel data into temperature data. You will need a microcontroller with 20,000 bytes or more of RAM. We recommend a Teensy 3.1 or above.

SparkFun labored with love to create this code. Feel like supporting open source hardware? 
Buy the Melexis MLX90640 breakout board ([110&deg;](https://www.sparkfun.com/products/14843) and [55&deg;](https://www.sparkfun.com/products/14844) FOV) from SparkFun!

Repository Contents
-------------------

* **/Documents** - Datasheets
* **/Firmware** - Contains the sketches that Processing app to implement the visualizer

Documentation
--------------
* **[Hookup Guide](https://learn.sparkfun.com/tutorials/qwiic-ir-array-mlx90640-hookup-guide)** - Basic hookup guide for the Qwiic IR Array.
* Product Repos
  * **[Qwiic IR Array (MLX90640-110x75 FOV)](https://github.com/sparkfun/Qwiic_IR_Array_MLX90640_110)**
  * **[Qwiic IR Array (MLX90640-55x35 FOV)](https://github.com/sparkfun/Qwiic_IR_Array_MLX90640_55)**

Products that use this Library
----------------
* [SEN-14843](https://www.sparkfun.com/products/14843)- SparkFun red version w/ 110&deg; FOV
* [SPX-14768](https://www.sparkfun.com/products/14768)- SparkX version w/ 110&deg; FOV
* [SEN-14844](https://www.sparkfun.com/products/14844)- SparkFun red version w/ 55&deg; FOV
* [SPX-14769](https://www.sparkfun.com/products/14769)- SparkX version w/ 55&deg; FOV

License Information
-------------------

This product is _**open source**_! 

Please review the LICENSE.md file for license information. 

If you have any questions or concerns on licensing, please contact techsupport@sparkfun.com.

Please use, reuse, and modify these files as you see fit. Please maintain attribution to SparkFun Electronics and release any derivative under the same license.

Distributed as-is; no warranty is given.

- Your friends at SparkFun.
