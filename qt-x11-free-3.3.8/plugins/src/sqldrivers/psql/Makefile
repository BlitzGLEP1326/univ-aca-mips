#############################################################################
# Makefile for building: libqsqlpsql.so
# Generated by qmake (1.07a) (Qt 3.3.8) on: Wed Oct  9 10:41:19 2013
# Project:  psql.pro
# Template: lib
# Command: $(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile psql.pro
#############################################################################

####### Compiler, tools and options

CC       = gcc
CXX      = g++
LEX      = flex
YACC     = yacc
CFLAGS   = -pipe -Wall -W -O2 -fPIC  -DQT_NO_DEBUG -DQT_PLUGIN -DQT_SHARED
CXXFLAGS = -pipe -Wall -W -O2 -fPIC  -DQT_NO_DEBUG -DQT_PLUGIN -DQT_SHARED
LEXFLAGS = 
YACCFLAGS= -d
INCPATH  = -I/home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -I. -I../../../../include -I.moc/release-shared/
LINK     = g++
LFLAGS   =  -Wl,-rpath,/home/smrcascao/Transferências/qt-x11-free-3.3.8/lib -shared -Wl,-rpath,/home/smrcascao/Transferências/qt-x11-free-3.3.8/plugins/sqldrivers
LIBS     = $(SUBLIBS) -L/home/smrcascao/Transferências/qt-x11-free-3.3.8/lib -L/usr/X11R6/lib -lpq -lqt -lXext -lX11 -lm -lSM -lICE -ldl
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

HEADERS = ../../../../src/sql/drivers/psql/qsql_psql.h
SOURCES = main.cpp \
		../../../../src/sql/drivers/psql/qsql_psql.cpp
OBJECTS = .obj/main.o \
		.obj/qsql_psql.o
FORMS = 
UICDECLS = 
UICIMPLS = 
SRCMOC   = 
OBJMOC = 
DIST	   = psql.pro
QMAKE_TARGET = qsqlpsql
DESTDIR  = ../../../sqldrivers/
TARGET   = libqsqlpsql.so
TARGETD   = libqsqlpsql.so

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

all: Makefile  ../../../sqldrivers/$(TARGET)

../../../sqldrivers/$(TARGET):  $(UICDECLS) $(OBJECTS) $(OBJMOC) $(SUBLIBS) $(OBJCOMP)  
	test -d ../../../sqldrivers/ || mkdir -p ../../../sqldrivers/
	-$(DEL_FILE) $(TARGET)
	$(LINK) $(LFLAGS) -o $(TARGET) $(OBJECTS) $(OBJMOC) $(LIBS) $(OBJCOMP)
	-$(MOVE) $(TARGET) ../../../sqldrivers/



mocables: $(SRCMOC)
uicables: $(UICDECLS) $(UICIMPLS)

$(MOC): 
	( cd /home/smrcascao/Transferências/qt-x11-free-3.3.8/src/moc && $(MAKE) )

Makefile: psql.pro ../../../../.qmake.cache /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++/qmake.conf ../../../../lib/libqt.prl
	$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile psql.pro
qmake: 
	@$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile psql.pro

dist: 
	@mkdir -p .obj/qsqlpsql && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .obj/qsqlpsql/ && ( cd `dirname .obj/qsqlpsql` && $(TAR) qsqlpsql.tar qsqlpsql && $(GZIP) qsqlpsql.tar ) && $(MOVE) `dirname .obj/qsqlpsql`/qsqlpsql.tar.gz . && $(DEL_FILE) -r .obj/qsqlpsql

mocclean:

uiclean:

yaccclean:
lexclean:
clean:
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) ../../../sqldrivers/$(TARGET) $(TARGET)


FORCE:

####### Compile

.obj/main.o: main.cpp ../../../../src/sql/drivers/psql/qsql_psql.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/main.o main.cpp

.obj/qsql_psql.o: ../../../../src/sql/drivers/psql/qsql_psql.cpp ../../../../src/sql/drivers/psql/qsql_psql.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/qsql_psql.o ../../../../src/sql/drivers/psql/qsql_psql.cpp

####### Install

install_target: all 
	@$(CHK_DIR_EXISTS) "$(INSTALL_ROOT)../../../sqldrivers/" || $(MKDIR) "$(INSTALL_ROOT)../../../sqldrivers/"
	-$(INSTALL_FILE) "../../../sqldrivers/$(TARGET)" "$(INSTALL_ROOT)../../../sqldrivers/$(TARGET)"
	-strip --strip-unneeded "$(INSTALL_ROOT)../../../sqldrivers/$(TARGET)"

uninstall_target: 
	-$(DEL_FILE) "$(INSTALL_ROOT)../../../sqldrivers/$(TARGET)"
	-$(DEL_DIR) "$(INSTALL_ROOT)../../../sqldrivers/"


install: install_target  

uninstall: uninstall_target  

