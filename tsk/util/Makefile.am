AM_CPPFLAGS = $(OPENSSL_INCLUDES) -I../.. -I$(srcdir)/../.. -Wall
AM_CXXFLAGS = -Wall -Wextra -Werror
EXTRA_DIST = .indent.pro 

noinst_LTLIBRARIES = libtskutil.la
libtskutil_la_SOURCES = crypto.cpp detect_encryption.c file_system_utils.c

indent:
	indent *.c *.cpp *.h *.hpp

clean-local:
	-rm -f *.c~ *.cpp~ *.h~ *.hpp~