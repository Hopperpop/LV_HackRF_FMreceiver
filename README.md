# LV_HackRF_FMreceiver
![GitHub top language](https://img.shields.io/github/languages/top/Hopperpop/LV_HackRF_FMreceiver) ![GitHub](https://img.shields.io/github/license/Hopperpop/LV_HackRF_FMreceiver)

Multi FM station receiver using a hackRF and LabView.

This repositiory contains an example/learning exercise on how to use hackRF with LabView (2020-community edition). It demonstrates how to demodulate multiple FM station in parallel and mix them in real-time.

Some work has been done to optimize the code and let it make use of multi-core processors to increase performance.
Jitterless audio was possible for demodulating 6 FM stations at a samplerate of 4.5MHz on a Intel(R) Core(TM) i5-6600K @4.67GHz.

The project is build on top of following .net wrapper for hackrf.dll: [makar853/nethackrf](https://github.com/makar853/nethackrf)


![image](https://user-images.githubusercontent.com/11853634/139941657-9c5482ac-c672-41a3-9d03-83f7fc05fb3b.png)

# About
This project contains and uses precompiled dynamic link libraries which have been released under different licenses:<br>
* ![GitHub](https://img.shields.io/github/license/makar853/nethackrf) [NetHackrf-v1.1](https://github.com/makar853/nethackrf)  <br>
  * ![GitHub](https://img.shields.io/github/license/libusb/libusb) [libusb-1.0.dll](https://github.com/libusb/libusb)  <br>
  * ![GitHub](https://img.shields.io/github/license/greatscottgadgets/hackrf) [hackrf.dll](https://github.com/mossmann/hackrf/tree/master/host/libhackrf)
