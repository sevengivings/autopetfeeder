# autopetfeeder
Automated pet feeder made with ESPHome 

## [Introduction] 

The sparrows occasionally come in for a seasonal binge of puppy food, and it makes a mess when the small-mouthed birds dig it up instead of taking a bite out of each one. So, I bought an auto-open feeder from Aliexpress with a proximity sensor, used it for a while, and became dissatisfied with the function (it closed in the middle of eating, startling my dog). 

Traditional passive infrared (PIR) sensors have the problem of opening the lid when sparrows come. For the first time, I used an ultrasonic distance sensor as a baseline for opening and closing. But the trouble with the malfunction of the ultrasonic distance sensor(occasionally happened after waking up from deep sleep of ESP32-C3), I chose the infrared thermal sensor(8x8 pixels AMG8833-based sensor). 

## [1st version - Ultrasonic sensor HC-SR04] 

![20231011_112720-horz](https://github.com/sevengivings/autopetfeeder/assets/2328500/d991ff60-f46b-4c16-9cdc-63db017f3231)

![123206](https://github.com/sevengivings/autopetfeeder/assets/2328500/49d82c50-fd5c-4085-898e-c82643fa850d)

![스크린샷 2023-10-11 123147](https://github.com/sevengivings/autopetfeeder/assets/2328500/9d5f902b-f0c7-4e54-8d24-afc0eedc4316)

![172301](https://github.com/sevengivings/autopetfeeder/assets/2328500/b003151e-9193-48b4-8353-d4b195360504)

## [2nd version - 8x8 thermal sensor MCU8833] 

![165230](https://github.com/sevengivings/autopetfeeder/assets/2328500/ed004c01-10b7-4d8b-a099-c494bfea1283)

![134759](https://github.com/sevengivings/autopetfeeder/assets/2328500/7e662bf1-d4e7-47f0-9aee-442b1c3a69e7)

![163358](https://github.com/sevengivings/autopetfeeder/assets/2328500/a262c3d5-37a3-4c62-8f47-96697ee1c642)

More stories can be found at https://imky.tistory.com/86 (in Korean)
AMG8833-related codes are originated from https://github.com/TheRealWaldo/AMG8833-ESPHOME
