# SPDX-License-Identifier: (GPL-2.0 OR BSD-2-Clause)

XDP_TARGETS := xdp_monitor.bpf
BPF_SKEL_TARGETS := $(XDP_TARGETS)

TOOL_NAME := xdp-monitor
MAN_PAGE := xdp-monitor.8
TEST_FILE := tests/test-xdp-monitor.sh
USER_TARGETS := xdp-monitor
LIB_DIR       = ../lib
USER_LIBS     = -lm

include $(LIB_DIR)/common.mk

