# Srouce Directory
ROOTDIR = ../../unit_test
SRCDIR = $(ROOTDIR)/src

CXXFLAGS += -std=c++11

INCLUDES = \
  -I../../include \
  -I$(ROOTDIR)/lib/include \
  -I$(SRCDIR)/gtest

LDADD = \
  -lpthread

bin_PROGRAMS = unit_test

unit_test_SOURCES = \
  $(SRCDIR)/gtest/gtest-all.cc \
  $(SRCDIR)/main.cpp \
  $(SRCDIR)/test-plusaes.cpp

