CONTIKI_PROJECT=bviot-device
all: $(CONTIKI_PROJECT)

APPS=servreg-hack

CONTIKI=../..

#linker optimizations
SMALL=1

CONTIKI_WITH_IPV6 = 1
include $(CONTIKI)/Makefile.include

CFLAGS += -DPROJECT_CONF_H=\"project-conf.h\"
#PROJECT_SOURCEFILES += slip-bridge.c

CONTIKI_WITH_IPV6 = 1
include $(CONTIKI)/Makefile.include
