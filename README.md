SD card and fat file system example.

This example shows how to use the ESP-IDF SDMMC and SPI drivers to access
an SD card. It mounts the filesystem, creates a file, writes to it, renames
it, reads from it, and finally unmounts the filesystem.

To use this example, you need to connect an SD card module to your ESP32 board.
The example uses the following GPIO pins:
- MISO: 19
- MOSI: 23
- CLK:  18
- CS:   5

You can change these pin numbers in the code if needed.
