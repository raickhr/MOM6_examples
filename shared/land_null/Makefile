# Configuration
BUILD ?= build
FMS_BUILD ?= ../fms/build

TARGET = libland_null.a
CODEBASE = ../../src/land_null
CONFIGURE_AC = ../config/configure.land_null.ac

FCFLAGS += -I$(abspath $(FMS_BUILD))
LDFLAGS += -L$(abspath $(FMS_BUILD))

include ../config/Libs.mk
