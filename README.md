# ESP32-CAM-teachable-machines
### Machine learning using ESP32 cam module and teachable machine by Google


## [Teachable Machine link](https://teachablemachine.withgoogle.com/)
1. Get started
2. Image project / Pose project
3. Standard model
4. Create and rename classes
5. upload dataset
6. Train model
7. Export model
8. Select tensorflow.js and click "upload my model"
9. Copy your sharable link

## modify the code
1. Chnage SSID and passwd in lines 1 and 2 to your network's SSID and passwd
2. To select pose instead of image just replace pose and image in the lines 635 and 636
3. Paste the sharable link in line 642. REPLACE ONLY THE LINK

## Common error: (fd_forward.h)

ERROR:
Compilation error: fd_forward.h: No such file or directory

SOLUTION:
Go to boards manager and downgrade esp32 by Espressif Systems to version "1.0.6"
