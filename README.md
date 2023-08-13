# object-detection-using-Edge-impulse
- Using ESP32-CAM (Ai Thinker) and AI on edge (refer to [DroneBot Workshop](https://dronebotworkshop.com/esp32-object-detect/) and EloquentArduino library) to identify different mouse from Logitech.
- There are 2 optical mouse to identify from the dataset, which are K850 mouse and M221 mouse respectively.The images are captured using ESP32-CAM from different angles and has total of 449 images. Image is resized into _48px_ height and width, color depth changed to _Grayscale_ .

   - K850 mouse

   ![Logitech K850 mouse_1691398855315](https://github.com/TuckWai97/object-detection-using-Edge-impulse/assets/47237045/e5e9bf5b-fdb1-4147-a540-975b4fa6b475)

   - M221 mouse

   ![Logitech M221 mouse_1691399153115](https://github.com/TuckWai97/object-detection-using-Edge-impulse/assets/47237045/0a3c730c-ae41-43a8-9d73-c03ec2244b7f)


    esp23cam_webserver_capture is from EloquentArduino library to capture images using Webserver using ESP32-CAM AI Thinker.
    Object_detection_inferencing folder is downloaded from Edge Impulse to run in Arduino IDE. You can go to the project that I published in Edge Impulse and download the folder as zip.

    To use it, simply choose _Sketch_ from the top of Arduino IDE and navigate to _Include library_ and go _Add .ZIP Library ..._.
[Link to clone my public project in Edge impulse](https://studio.edgeimpulse.com/studio/267944/versions)


