# SPDX-License-Identifier: GPL-2.0-only
ccflags-y += -I$(src)			# needed for trace events

obj-$(CONFIG_ANDROID_BINDER_IPC)		+= binder.o
binder-$(CONFIG_ANDROID_BINDER_IPC)		+= binder_alloc.o

binder-$(CONFIG_ANDROID_BINDER_IPC_SELFTEST)	+= binder_alloc_selftest.o
binder-$(CONFIG_ANDROID_BINDERFS)		+= binderfs.o
