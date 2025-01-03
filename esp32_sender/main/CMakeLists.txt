idf_component_register(SRCS "main.c" "camera.c"
                    INCLUDE_DIRS "." REQUIRES mdns nvs_flash esp_wifi esp_timer esp32-camera)