Amazon FreeRTOS project.

Start by:
# git clone https://github.com/aws/amazon-freertos

Then navigate to:
amazon-freertos/vendors/espressif/boards/

Then clone this repo:
# git clone https://github.com/teuteuguy/m5stickc

To build:
navigate to: amazon-freertos/vendors/espressif/boards/m5stickc/aws_demos

# make all -j4
# make flash
# screen /dev/cu.xxxxxxxxxx 115200 -L


