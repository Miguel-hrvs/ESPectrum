idf_component_register(SRC_DIRS src
                                src/comdrivers
                                src/devdrivers
                                src/dispdrivers
                                src/emudevs
                                src/network
                       INCLUDE_DIRS src
                                src/fonts
                                src/images
                                src/comdrivers
                                src/devdrivers
                                src/dispdrivers
                                src/emudevs
                                src/network
                       REQUIRES fatfs
                                spiffs
                                esp_adc
                                esp_wifi
                                esp_timer
                                ulp
                                nvs_flash
                                soc)
