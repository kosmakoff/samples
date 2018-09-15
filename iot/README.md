# Using .NET Core for IoT Scenarios

.NET Core can be used to build applications for [IoT](https://en.wikipedia.org/wiki/Internet_of_things) devices and scenarios. For the purposes of this discussion, we will consider IoT applications to be an application that runs on a device that can interact with sensors or displays that require the use of [GPIO pins](https://en.wikipedia.org/wiki/General-purpose_input/output), serial ports or similar hardware.

The following samples demonstrate how to use .NET Core for IoT applications. You need to use at least [.NET Core 2.1](https://www.microsoft.com/net/download/archives) if you are using an ARM32 device. You need to use [.NET Core 3.0 for ARM64](https://github.com/dotnet/announcements/issues/82).

* [Blinking LED](led-blink/README.md)
* [Trimpot (potentiometer)](trimpot/README.md)

Each example includes sample code and a diagram of the required wiring. The wiring diagrams use [Fritzing](http://fritzing.org/home/), like the following example.

![Rasperry Pi Breadboard diagram](led-blink/rpi-led_bb.png)

Many of these samples use the [Raspberry Pi](https://www.raspberrypi.org/), however, .NET Core can be used for other devices. A [Raspberry Pi Starter Pack](https://www.adafruit.com/product/3058) contains enough electronics to get started on many projects.

You will need a basic understanding of using breadboards. [How to Use a Breadboard](https://www.youtube.com/watch?v=6WReFkfrUIk) and [Collin's Lab: Breadboards & Perfboards](https://www.youtube.com/watch?v=w0c3t0fJhXU) are good videos that will help you learn what you need to know in a few minutes.