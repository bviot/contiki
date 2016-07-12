CONTIKI_PROJECT = bviot-device-lwm2m

CONTIKI_SOURCEFILES += serial-protocol.c example-ipso-temperature.c

all: $(CONTIKI_PROJECT)

CFLAGS += -DPROJECT_CONF_H=\"project-conf.h\"

APPS += servreg-hack
APPS += rest-engine
APPS += er-coap
APPS += oma-lwm2m
APPS += ipso-objects

CONTIKI=../..

#linker optimizations
SMALL=1

CONTIKI_WITH_IPV6 = 1
include $(CONTIKI)/Makefile.include
