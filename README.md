# ESP8266-base-platformio-project
A starting point for ESP8266 and Platformio

### This is a [Platformio](http://platformio.org/) project:

to build...

    platformio run
    
to upload...

    platformio run --target upload

to start a serial monitor...

    platformio serialports monitor -b 115200
    
update the ota IP address - use your router to set a static IP based on MAC - in platformio.ini

    # for over the air - set port to ip address of module...
    upload_port = 10.0.2.240