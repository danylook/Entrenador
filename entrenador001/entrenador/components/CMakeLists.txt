
set(COMPONENT_SRCS "mqtt_example.c")


set(COMPONENT_ADD_INCLUDEDIRS "include")

# requirements can't depend on config
set(COMPONENT_REQUIRES mcommon mconfig mwifi mlink mqtt gpiodisplay ssd1306)

register_component()
