# Uncoment and fix MODULE_TOPDIR line OR provide MODULE_TOPDIR variable for make
# fix this relative to include/
# or use absolute path to the GRASS source code
# MODULE_TOPDIR = ../../..

PGM = v.profile

LIBES = $(VECTLIB) $(GISLIB)
DEPENDENCIES= $(VECTDEP) $(GISDEP)
EXTRA_INC = $(VECT_INC)
EXTRA_CFLAGS = $(VECT_CFLAGS)

include $(MODULE_TOPDIR)/include/Make/Module.make

default: cmd
