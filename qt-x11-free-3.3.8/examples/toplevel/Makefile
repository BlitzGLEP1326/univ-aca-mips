#############################################################################
# Makefile for building: toplevel
# Generated by qmake (1.07a) (Qt 3.3.8) on: Wed Oct  9 10:41:24 2013
# Project:  toplevel.pro
# Template: app
# Command: $(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile toplevel.pro
#############################################################################

####### Compiler, tools and options

CC       = gcc
CXX      = g++
LEX      = flex
YACC     = yacc
CFLAGS   = -pipe -Wall -W -O2  -DQT_NO_DEBUG -DQT_SHARED
CXXFLAGS = -pipe -Wall -W -O2  -DQT_NO_DEBUG -DQT_SHARED
LEXFLAGS = 
YACCFLAGS= -d
INCPATH  = -I/home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -I. -I../../include -I.ui/ -I. -I.moc/
LINK     = g++
LFLAGS   =  -Wl,-rpath,/home/smrcascao/Transferências/qt-x11-free-3.3.8/lib
LIBS     = $(SUBLIBS) -L/home/smrcascao/Transferências/qt-x11-free-3.3.8/lib -L/usr/X11R6/lib -lqt -lXext -lX11 -lm -lSM -lICE -ldl
AR       = ar cqs
RANLIB   = 
MOC      = /home/smrcascao/Transferências/qt-x11-free-3.3.8/bin/moc
UIC      = /home/smrcascao/Transferências/qt-x11-free-3.3.8/bin/uic -L /home/smrcascao/Transferências/qt-x11-free-3.3.8/plugins
QMAKE    = /home/smrcascao/Transferências/qt-x11-free-3.3.8/bin/qmake
TAR      = tar -cf
GZIP     = gzip -9f
COPY     = cp -f
COPY_FILE= $(COPY)
COPY_DIR = $(COPY) -r
INSTALL_FILE= $(COPY_FILE)
INSTALL_DIR = $(COPY_DIR)
DEL_FILE = rm -f
SYMLINK  = ln -sf
DEL_DIR  = rmdir
MOVE     = mv -f
CHK_DIR_EXISTS= test -d
MKDIR    = mkdir -p

####### Output directory

OBJECTS_DIR = .obj/

####### Files

HEADERS = 
SOURCES = main.cpp
OBJECTS = .obj/main.o \
		.obj/options.o
FORMS = options.ui
UICDECLS = .ui/options.h
UICIMPLS = .ui/options.cpp
SRCMOC   = .moc/moc_options.cpp
OBJMOC = .obj/moc_options.o
DIST	   = toplevel.pro
QMAKE_TARGET = toplevel
DESTDIR  = 
TARGET   = toplevel

first: all
####### Implicit rules

.SUFFIXES: .c .o .cpp .cc .cxx .C

.cpp.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cc.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.cxx.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.C.o:
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o $@ $<

.c.o:
	$(CC) -c $(CFLAGS) $(INCPATH) -o $@ $<

####### Build rules

all: Makefile $(TARGET)

$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC)  
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJMOC) $(OBJCOMP) $(LIBS)

mocables: $(SRCMOC)
uicables: $(UICDECLS) $(UICIMPLS)

$(MOC): 
	( cd /home/smrcascao/Transferências/qt-x11-free-3.3.8/src/moc && $(MAKE) )

Makefile: toplevel.pro ../../.qmake.cache /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++/qmake.conf ../../lib/libqt.prl
	$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile toplevel.pro
qmake: 
	@$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile toplevel.pro

dist: 
	@mkdir -p .obj/toplevel && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .obj/toplevel/ && $(COPY_FILE) --parents options.ui.h .obj/toplevel/ && ( cd `dirname .obj/toplevel` && $(TAR) toplevel.tar toplevel && $(GZIP) toplevel.tar ) && $(MOVE) `dirname .obj/toplevel`/toplevel.tar.gz . && $(DEL_FILE) -r .obj/toplevel

mocclean:
	-$(DEL_FILE) $(OBJMOC)
	-$(DEL_FILE) $(SRCMOC)

uiclean:
	-$(DEL_FILE) $(UICIMPLS) $(UICDECLS)

yaccclean:
lexclean:
clean: mocclean uiclean
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) $(TARGET)


FORCE:

####### Compile

.obj/main.o: main.cpp .ui/options.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/main.o main.cpp

.ui/options.h: options.ui 
	$(UIC) options.ui -o .ui/options.h

.ui/options.cpp: .ui/options.h options.ui options.ui.h 
	$(UIC) options.ui -i options.h -o .ui/options.cpp

.obj/options.o: .ui/options.cpp .ui/options.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/options.o .ui/options.cpp

.obj/moc_options.o: .moc/moc_options.cpp  .ui/options.h 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/moc_options.o .moc/moc_options.cpp

.moc/moc_options.cpp: $(MOC) .ui/options.h
	$(MOC) .ui/options.h -o .moc/moc_options.cpp

####### Install

install:  

uninstall:  

