# SPDX-License-Identifier: BSD-3-Clause
# Copyright 2015-2023, Intel Corporation

#
# src/test/out_err_mt/Makefile -- build unit test for error messages
#
TARGET = out_err_mt
OBJS = out_err_mt.o

LIBPMEMCOMMON=y
LIBPMEM=y
LIBPMEMLOG=y
LIBPMEMBLK=y
LIBPMEMOBJ=y
LIBPMEMPOOL=y

include ../Makefile.inc

# Libpmemblk and libpmemlog are deprecated.
# This flag allows to build tests, examples and benchmarks
# using pmemblk/pmemlog despite the deprecated state.
CFLAGS += -Wno-deprecated-declarations
