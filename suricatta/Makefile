# Copyright (C) 2014-2018 Stefano Babic <sbabic@denx.de>
#
# SPDX-License-Identifier:     GPL-2.0-or-later
lib-$(CONFIG_SURICATTA) += state.o suricatta.o
ifneq ($(CONFIG_SURICATTA_HAWKBIT),)
lib-$(CONFIG_SURICATTA) += server_hawkbit.o
endif
