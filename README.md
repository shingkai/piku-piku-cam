# piku-piku-cam
A digital stereoscopic camera system

## What is Piku-Piku Cam?
Piku-Piku Cam is a [stereoscopic camera](https://en.wikipedia.org/wiki/Wiggle_stereo) system. The name piku-piku comes from the Japanese word "piku" ("ピク") which means "wiggle".

Piku-Piku Cam uses multiple low-cost cameras to capture still images from varying perspectives. The stills are then sequenced into a "wigglegram" to create the illusion of depth due to the parallax effect.

## Architecture Overview


## Hardware
Piku-Piku Cam uses multiple Seeed Xiao ESP32-S3 Sense Camera boards to capture still images. The still frames are then sent via SPI to a controller board, which sequences the stills to create the "wigglegram". The preview is then sent to the display board.

| Component | Quantity | Hardware | Description |
| -- | -- | -- | -- |
| Camera Board | 4 | [Seeed Xiao ESP32-S3 Sense Camera](https://wiki.seeedstudio.com/xiao_esp32s3_getting_started/) | an ESPS32-S3 board with OV2640 camera sensor |
| Display Board | 1 | [LilyGo T-Display S3 Amoled](https://www.lilygo.cc/products/t-display-s3-amoled?variant=43506902335669) | an ESP32-S3 board with a 1.91" amoled display

