# M5StickC - Amazon FreeRTOS project

## Installation

Start by getting the latest amazon-freertos source:
```bash
git clone https://github.com/aws/amazon-freertos
```

Then navigate to:
```bash
cd amazon-freertos/vendors/espressif/boards/
```

Then clone this repo:
```bash
git clone https://github.com/teuteuguy/m5stickc
```

To build:
```bash
cd amazon-freertos/vendors/espressif/boards/m5stickc/aws_demos
```
Then:
```bash
make all -j4
make flash
screen /dev/cu.xxxxxxxxxx 115200 -L
```
