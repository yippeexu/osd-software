bin_PROGRAMS = osd-device-gateway

osd_device_gateway_LDADD = ../../libosd/libosd.la

AM_LDFLAGS += \
	${libczmq_LIBS} \
	${libglip_LIBS}

AM_CFLAGS += \
	-I$(top_srcdir)/src/libosd/include \
	-include $(top_builddir)/config.h \
	${libczmq_CFLAGS} \
	${libglip_CFLAGS}

osd_device_gateway_SOURCES = \
	../argtable3.c \
	../iniparser.c \
	../dictionary.c \
	osd-device-gateway.c 
