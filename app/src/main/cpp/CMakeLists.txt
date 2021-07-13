cmake_minimum_required(VERSION 3.6.4111459)



add_library(
        serial_port
        SHARED
        SerialPort.c)

target_link_libraries(
        serial_port # 总库libnative-lib.so

        log # 日志库，打印日志用的

)