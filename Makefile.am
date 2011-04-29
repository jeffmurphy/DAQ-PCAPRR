AUTOMAKE_OPTIONS = foreign

ACLOCAL_AMFLAGS = -I m4

pkglib_LTLIBRARIES = daq_pcaprr.la
daq_pcaprr_la_SOURCES = daq_pcaprr.c
daq_pcaprr_la_CFLAGS = -DBUILDING_SO
daq_pcaprr_la_LDFLAGS = -module -export-dynamic -avoid-version -shared
