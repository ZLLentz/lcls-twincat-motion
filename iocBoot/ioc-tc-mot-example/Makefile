IOC_TOP = /reg/neh/home/mcbrowne/trunk2/ioc/common/ads-ioc
IOC_INSTANCE_PATH := $(shell pwd)

# Set PRODUCTION_IOC to 1 to move from a testing to a production IOC:
PRODUCTION_IOC := 1

PROJECT_NAME = lcls-twincat-motion
PROJECT_PATH := ../../lcls-twincat-motion/lcls-twincat-motion.tsproj
PLC = Example

PYTMC_OPTS :=
PREFIX = PLC:TST:MOT

include $(IOC_TOP)/iocBoot/templates/Makefile.base
