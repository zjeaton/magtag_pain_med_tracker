# Magtag Pain Med Tracker

After surgery I was having trouble keeping track of all of the meds I was supposed to take and when. I created this simple tracker that logs when pills were taken, and tells you when the next is due.

This app uses an AdaFruit Magtag, which is a Dev Board from Adafruit that consists of an esp32 and a 2.9" eInk screen. [It is available here.](https://www.adafruit.com/product/4800?gclid=CjwKCAjwhNWZBhB_EiwAPzlhNmbDg88xdk-QrwEHe_bG_2lAGDNgIxULrtgKL42mWiJ9sTUOjfVREBoCVLUQAvD_BwE) 

Code is written in the Arduino IDE and flashed to the magtag. AdaFruit has excellent tutorials on their site. To run this software, copy the .ino file into the Arduino IDE and flash.

### functions

Button presses create a time stamp for the labeled pill and update displayed last time the pill was taken with the timestamp. It then updates the next pill time to the correct interval.