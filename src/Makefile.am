AM_CPPFLAGS = -I@top_srcdir@/include
AM_CXXFLAGS = -DSYSCONF_PATH=\"$(datadir)\" -std=c++11 -W -Wall -pedantic -O3 -g

bin_PROGRAMS = main fork

main_SOURCES = main.cxx
fork_SOURCES = fork.cxx

check_PROGRAMS = main fork

TESTS = tst.sh
EXTRA_DIST = tst.sh
