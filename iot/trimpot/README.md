# Reading Analog Input from a Potentiometer

You can use .NET Core to read analog values from a [potentiometer](https://www.adafruit.com/product/356), like a [volume control](https://en.wikipedia.org/wiki/Trimmer_(electronics)).

This [sample](Program.cs) is based on [Analog Inputs for Raspberry Pi Using the MCP3008](https://learn.adafruit.com/reading-a-analog-in-and-controlling-audio-volume-with-the-raspberry-pi), a direct port of [Python implementation](https://learn.adafruit.com/reading-a-analog-in-and-controlling-audio-volume-with-the-raspberry-pi/script). The sample uses [bit-banging](https://en.wikipedia.org/wiki/Serial_Peripheral_Interface#Example_of_bit-banging_the_master_protocol) to interact with the [MCP3008 ADC](https://www.adafruit.com/product/856).

The following [fritzing diagram](rpi-trimpot.fzz) demonstrates how you should wire your device in order to run the [sample C# code](Program.cs) for this sample. It uses the 3.3v, GND and GPIO 18, 23, 24 and 25 pins.

![Rasperry Pi Breadboard diagram](rpi-trimpot_bb.png)

See [Using .NET Core for IoT Scenarios](../README.md) for more samples.