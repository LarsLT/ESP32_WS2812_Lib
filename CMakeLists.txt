cmake_minimum_required(VERSION 3.5)
idf_component_register(SRCS "C:/Projects/s3-personal-LarsLT/Code/esp/cleanRTOS/components/ESP32_WS2812_Lib/src/ESP32_WS2812_Lib.cpp" # mian cpp file of library
                    INCLUDE_DIRS "src/." #include src folder, change to "." if no src
                    REQUIRES "arduino-esp32"
                    )
    
project(ESP32_WS2812_Lib) # (Name of the folder)