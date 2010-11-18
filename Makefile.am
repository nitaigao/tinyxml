AUTOMAKE_OPTIONS = foreign

# what flags you want to pass to the C compiler & linker
CFLAGS = --pedantic -Wall -std=c99 -O2
LDFLAGS =

# this lists the binaries to produce, the (non-PHONY, binary) targets in
# the previous manual Makefile
# bin_PROGRAMS = xmltest
# xmltest_SOURCES = tinyxml.cpp tinyxmlparser.cpp xmltest.cpp tinyxmlerror.cpp tinystr.cpp

lib_LTLIBRARIES = libtinyxml.la
libtinyxml_la_SOURCES = tinyxml.cpp tinyxmlparser.cpp tinyxmlerror.cpp tinystr.cpp
include_HEADERS = tinyxml.h tinystr.h