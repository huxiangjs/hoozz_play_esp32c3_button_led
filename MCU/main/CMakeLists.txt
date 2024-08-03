idf_component_register(
	SRCS
		"esp32-common/led_strip_encoder.c"
		"esp32-common/ws2812b.c"
		"esp32-common/wifi.c"
		"esp32-common/event_bus.c"
		"esp32-common/simple_ctrl.c"
		"esp32-common/crypto.c"
		"esp32-common/spiffs.c"
		"esp32-common/keyboard.c"
		"tiny-AES-c/aes.c"
		"main.cpp"
		"led_effects.c"

        INCLUDE_DIRS
		"."
		"esp32-common"
		"tiny-AES-c"
)

add_definitions(
	-fno-exceptions
	-Wno-deprecated-declarations
	-fno-unwind-tables
	-ffunction-sections
	-fdata-sections
	-fmessage-length=0
)
