includedir=$(prefix)/include/libk/linux/
lib_LTLIBRARIES=\
libk-linux.la 
include_HEADERS=
AM_CFLAGS=$(CODE_COVERAGE_CFLAGS) -std=gnu99 -Wall -Werror -Wno-format-y2k -W -Wstrict-prototypes -Wmissing-prototypes \
-Wpointer-arith -Wreturn-type -Wcast-qual -Wwrite-strings -Wswitch \
-Wshadow -Wcast-align -Wchar-subscripts -Winline \
-Wnested-externs -Wredundant-decls -Wmissing-field-initializers -Wextra \
-Wformat=2 -Wno-format-nonliteral -Wpointer-arith -Wno-missing-braces \
-Wno-unused-parameter -Wno-unused-variable -Wno-inline

#libk_arm32_la_SOURCES=arm_adc.c arm_dma.c arm_gpio.c arm_pwm.c arm_spi.c arm_time.c arm_twi.c arm_uart.c
#libk_arm32_la_CFLAGS=$(AM_CFLAGS)

libk_linux_la_SOURCES=\
linux_i2c.c\
linux_spi.c 
libk_linux_la_CFLAGS=$(AM_CFLAGS) -DF_CPU=16000000

