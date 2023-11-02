cmake_minimum_required(VERSION 3.13)


include(pico_sdk_import.cmake)

project(nombredelacarpetadelproyecto)

pico_sdk_init()


add_executable(nombredelacarpetadelproyecto main.c timer.c nombre.c)

target_link_libraries(nombredelacarpetadelproyecto pico_stdlib)

pico_enable_stdio_usb(nombredelacarpetadelproyecto 1)
pico_enable_stdio_uart(nombredelacarpetadelproyecto 0)

pico_add_extra_outputs(nombredelacarpetadelproyecto)




