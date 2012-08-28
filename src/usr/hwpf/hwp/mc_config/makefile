#   IBM_PROLOG_BEGIN_TAG
#  This is an automatically generated prolog.
#
#  $Source: src/usr/hwpf/hwp/mc_config/makefile $
#
#  IBM CONFIDENTIAL
#
#  COPYRIGHT International Business Machines Corp. 2012
#
#  p1
#
#  Object Code Only (OCO) source materials
#  Licensed Internal Code Source Materials
#  IBM HostBoot Licensed Internal Code
#
#  The source code for this program is not published or other-
#  wise divested of its trade secrets, irrespective of what has
#  been deposited with the U.S. Copyright Office.
#
#  Origin: 30
#
#  IBM_PROLOG_END_TAG
ROOTPATH = ../../../../..

MODULE = mc_config

##      support for Targeting and fapi
EXTRAINCDIR += ${ROOTPATH}/src/include/usr/ecmddatabuffer
EXTRAINCDIR += ${ROOTPATH}/src/include/usr/hwpf/fapi
EXTRAINCDIR += ${ROOTPATH}/src/include/usr/hwpf/plat
EXTRAINCDIR += ${ROOTPATH}/src/include/usr/hwpf/hwp

## pointer to common HWP files
EXTRAINCDIR += ${ROOTPATH}/src/usr/hwpf/hwp/include

##  Include sub dirs
##  NOTE: add a new EXTRAINCDIR when you add a new HWP
##@ EXTRAINCDIR += ${ROOTPATH}/src/usr/hwpf/hwp/???
EXTRAINCDIR += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_eff_config
EXTRAINCDIR += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_volt
EXTRAINCDIR += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_freq

OBJS =  mc_config.o			\
        mss_volt.o 			\
        mss_freq.o 			\
        mss_eff_config.o                \
        mss_eff_config_thermal.o        \
        mss_eff_config_termination.o    \
        mss_eff_config_rank_group.o
	
##  NOTE: add a new directory onto the vpaths when you add a new HWP
##@ VPATH += ${ROOTPATH}/src/usr/hwpf/hwp/???
VPATH += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_eff_config
VPATH += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_volt
VPATH += ${ROOTPATH}/src/usr/hwpf/hwp/mc_config/mss_freq


include ${ROOTPATH}/config.mk