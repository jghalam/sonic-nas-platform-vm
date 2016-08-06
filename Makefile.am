cfgdir = $(sysconfdir)/sonic
cfg_SCRIPTS = cfg/*.xml

lib_LTLIBRARIES=libsonic_nas_platform.la

libsonic_nas_platform_la_SOURCES= src/hal_npu_platform_init.c

libsonic_nas_platform_la_LDFLAGS=-shared -version-info 1:1:0

libsonic_nas_platform_la_CPPFLAGS=-D_FILE_OFFSET_BITS=64 -I$(includedir)/sonic

libsonic_nas_platform_la_CXXFLAGS=-std=c++11
