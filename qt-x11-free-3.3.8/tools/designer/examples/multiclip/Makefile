#############################################################################
# Makefile for building: multiclip
# Generated by qmake (1.07a) (Qt 3.3.8) on: Wed Oct  9 10:41:28 2013
# Project:  multiclip.pro
# Template: app
# Command: $(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile multiclip.pro
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
INCPATH  = -I/home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -I. -I../../../../include -I.moc/release-shared/
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

OBJECTS_DIR = .obj/release-shared/

####### Files

HEADERS = 
SOURCES = main.cpp
OBJECTS = .obj/release-shared/main.o \
		.obj/release-shared/multiclip.o
FORMS = multiclip.ui
UICDECLS = multiclip.h
UICIMPLS = multiclip.cpp
SRCMOC   = .moc/release-shared/moc_multiclip.cpp
OBJMOC = .obj/release-shared/moc_multiclip.o
DIST	   = multiclip.pro
QMAKE_TARGET = multiclip
DESTDIR  = 
TARGET   = multiclip

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

Makefile: multiclip.pro ../../../../.qmake.cache /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++/qmake.conf ../../../../lib/libqt.prl
	$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile multiclip.pro
qmake: 
	@$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile multiclip.pro

dist: 
	@mkdir -p .obj/release-shared/multiclip && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .obj/release-shared/multiclip/ && $(COPY_FILE) --parents multiclip.ui.h .obj/release-shared/multiclip/ && ( cd `dirname .obj/release-shared/multiclip` && $(TAR) multiclip.tar multiclip && $(GZIP) multiclip.tar ) && $(MOVE) `dirname .obj/release-shared/multiclip`/multiclip.tar.gz . && $(DEL_FILE) -r .obj/release-shared/multiclip

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

.obj/release-shared/main.o: main.cpp multiclip.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/main.o main.cpp

multiclip.h: multiclip.ui multiclip.ui.h
	$(UIC) multiclip.ui -o multiclip.h

multiclip.cpp: multiclip.h multiclip.ui multiclip.ui.h multiclip.ui.h
	$(UIC) multiclip.ui -i multiclip.h -o multiclip.cpp

.obj/release-shared/multiclip.o: multiclip.cpp multiclip.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/multiclip.o multiclip.cpp

.obj/release-shared/moc_multiclip.o: .moc/release-shared/moc_multiclip.cpp  multiclip.h 
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/moc_multiclip.o .moc/release-shared/moc_multiclip.cpp

.moc/release-shared/moc_multiclip.cpp: $(MOC) multiclip.h
	$(MOC) multiclip.h -o .moc/release-shared/moc_multiclip.cpp

####### Install

install:  

uninstall:  

