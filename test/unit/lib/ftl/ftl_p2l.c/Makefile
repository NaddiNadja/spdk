#  SPDX-License-Identifier: BSD-3-Clause
#  Copyright 2023 Solidigm All Rights Reserved
#  All rights reserved.
#

SPDK_ROOT_DIR := $(abspath $(CURDIR)/../../../../..)

TEST_FILE = ftl_p2l_ut.c

include $(SPDK_ROOT_DIR)/mk/spdk.unittest.mk

CFLAGS += -I$(SPDK_ROOT_DIR)/lib/ftl
