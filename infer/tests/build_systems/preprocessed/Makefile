# Copyright (c) 2016-present, Facebook, Inc.
#
# This source code is licensed under the MIT license found in the
# LICENSE file in the root directory of this source tree.

TESTS_DIR = ../..

CLANG_OPTIONS = -c
INFER_OPTIONS = --report-custom-error --developer-mode --headers --project-root ../codetoanalyze
INFERPRINT_OPTIONS = --issues-tests

SOURCES = \
  ../codetoanalyze/preprocessed.c

include $(TESTS_DIR)/clang.make
