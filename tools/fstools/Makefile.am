AM_CPPFLAGS = -I../.. -I$(srcdir)/../.. -Wall 
LDADD = ../../tsk3/libtsk3.la
LDFLAGS += -static
EXTRA_DIST = .indent.pro fscheck.cpp

bin_PROGRAMS = blkcalc blkcat blkls blkstat ffind fls fsstat icat ifind ils \
    istat jcat jls
blkcalc_SOURCES = blkcalc.cpp
blkcat_SOURCES = blkcat.cpp
blkls_SOURCES = blkls.cpp
blkstat_SOURCES = blkstat.cpp
ffind_SOURCES = ffind.cpp
fls_SOURCES = fls.cpp
fsstat_SOURCES = fsstat.cpp
icat_SOURCES = icat.cpp
ifind_SOURCES = ifind.cpp
ils_SOURCES = ils.cpp
istat_SOURCES = istat.cpp
jcat_SOURCES = jcat.cpp
jls_SOURCES = jls.cpp

indent:
	indent *.cpp 

clean-local:
	-rm -f *.cpp~ 
