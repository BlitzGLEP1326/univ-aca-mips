#############################################################################
# Makefile for building: helpviewer
# Generated by qmake (1.07a) (Qt 3.3.8) on: Wed Oct  9 10:41:24 2013
# Project:  helpviewer.pro
# Template: app
# Command: $(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile helpviewer.pro
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
INCPATH  = -I/home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -I. -I../../include -I.moc/release-shared/
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

HEADERS = helpwindow.h
SOURCES = helpwindow.cpp \
		main.cpp
OBJECTS = .obj/release-shared/helpwindow.o \
		.obj/release-shared/main.o
FORMS = 
UICDECLS = 
UICIMPLS = 
SRCMOC   = .moc/release-shared/moc_helpwindow.cpp
OBJMOC = .obj/release-shared/moc_helpwindow.o
DIST	   = helpviewer.pro
QMAKE_TARGET = helpviewer
DESTDIR  = 
TARGET   = helpviewer

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

Makefile: helpviewer.pro ../../.qmake.cache /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++/qmake.conf ../../lib/libqt.prl
	$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile helpviewer.pro
qmake: 
	@$(QMAKE) -spec /home/smrcascao/Transferências/qt-x11-free-3.3.8/mkspecs/linux-g++ -o Makefile helpviewer.pro

dist: 
	@mkdir -p .obj/release-shared/helpviewer && $(COPY_FILE) --parents $(SOURCES) $(HEADERS) $(FORMS) $(DIST) .obj/release-shared/helpviewer/ && ( cd `dirname .obj/release-shared/helpviewer` && $(TAR) helpviewer.tar helpviewer && $(GZIP) helpviewer.tar ) && $(MOVE) `dirname .obj/release-shared/helpviewer`/helpviewer.tar.gz . && $(DEL_FILE) -r .obj/release-shared/helpviewer

mocclean:
	-$(DEL_FILE) $(OBJMOC)
	-$(DEL_FILE) $(SRCMOC)

uiclean:

yaccclean:
lexclean:
clean: mocclean
	-$(DEL_FILE) $(OBJECTS)
	-$(DEL_FILE) *~ core *.core


####### Sub-libraries

distclean: clean
	-$(DEL_FILE) $(TARGET) $(TARGET)


FORCE:

####### Compile

.obj/release-shared/helpwindow.o: helpwindow.cpp helpwindow.h \
		../../include/qstatusbar.h \
		../../include/qpixmap.h \
		../../include/qpopupmenu.h \
		../../include/qmenubar.h \
		../../include/qtoolbar.h \
		../../include/qtoolbutton.h \
		../../include/qiconset.h \
		../../include/qfile.h \
		../../include/qtextstream.h \
		../../include/qstylesheet.h \
		../../include/qmessagebox.h \
		../../include/qfiledialog.h \
		../../include/qapplication.h \
		../../include/qcombobox.h \
		../../include/qevent.h \
		../../include/qlineedit.h \
		../../include/qobjectlist.h \
		../../include/qfileinfo.h \
		../../include/qdatastream.h \
		../../include/qprinter.h \
		../../include/qsimplerichtext.h \
		../../include/qpainter.h \
		../../include/qpaintdevicemetrics.h \
		../../include/qmainwindow.h \
		../../include/qtextbrowser.h \
		../../include/qstringlist.h \
		../../include/qmap.h \
		../../include/qdir.h \
		../../include/qwidget.h \
		../../include/qptrlist.h \
		../../include/qwindowdefs.h \
		../../include/qobject.h \
		../../include/qpaintdevice.h \
		../../include/qpalette.h \
		../../include/qfont.h \
		../../include/qfontmetrics.h \
		../../include/qfontinfo.h \
		../../include/qsizepolicy.h \
		../../include/qwinexport.h \
		../../include/qobjectdefs.h \
		../../include/qstring.h \
		../../include/qnamespace.h \
		../../include/qglobal.h \
		../../include/qconfig-minimal.h \
		../../include/qconfig-small.h \
		../../include/qconfig-medium.h \
		../../include/qconfig-large.h \
		../../include/qconfig.h \
		../../include/qmodules.h \
		../../include/qfeatures.h \
		../../include/qcstring.h \
		../../include/qmemarray.h \
		../../include/qgarray.h \
		../../include/qshared.h \
		../../include/qregion.h \
		../../include/qmime.h \
		../../include/qpair.h \
		../../include/qrect.h \
		../../include/qsize.h \
		../../include/qpoint.h \
		../../include/zutil.h \
		../../include/qvaluelist.h \
		../../include/zlib.h \
		../../include/qiodevice.h \
		../../include/qtl.h \
		../../include/qglist.h \
		../../include/qptrcollection.h \
		../../include/qcolor.h \
		../../include/qbrush.h \
		../../include/qstrlist.h \
		../../include/qdockwindow.h \
		../../include/qframe.h \
		../../include/qtextedit.h \
		../../include/qscrollview.h \
		../../include/qptrvector.h \
		../../include/qscrollbar.h \
		../../include/qrangecontrol.h \
		../../include/qdict.h \
		../../include/qgvector.h \
		../../include/qgdict.h \
		../../include/qdatetime.h \
		../../include/qmenudata.h \
		../../include/qkeysequence.h \
		../../include/qsignal.h \
		../../include/qvariant.h \
		../../include/qbutton.h \
		../../include/qdialog.h \
		../../include/qurloperator.h \
		../../include/qurlinfo.h \
		../../include/qurl.h \
		../../include/qnetworkprotocol.h \
		../../include/qdesktopwidget.h \
		../../include/qasciidict.h \
		../../include/qtranslator.h \
		../../include/qpen.h \
		../../include/qpointarray.h \
		../../include/qwmatrix.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/helpwindow.o helpwindow.cpp

.obj/release-shared/main.o: main.cpp helpwindow.h \
		../../include/qapplication.h \
		../../include/qdir.h \
		../../include/qmainwindow.h \
		../../include/qtextbrowser.h \
		../../include/qstringlist.h \
		../../include/qmap.h \
		../../include/qwidget.h \
		../../include/qtoolbar.h \
		../../include/qptrlist.h \
		../../include/qtextstream.h \
		../../include/qwindowdefs.h \
		../../include/qobject.h \
		../../include/qpaintdevice.h \
		../../include/qpalette.h \
		../../include/qfont.h \
		../../include/qfontmetrics.h \
		../../include/qfontinfo.h \
		../../include/qsizepolicy.h \
		../../include/qwinexport.h \
		../../include/qobjectdefs.h \
		../../include/qstring.h \
		../../include/qnamespace.h \
		../../include/qglobal.h \
		../../include/qconfig-minimal.h \
		../../include/qconfig-small.h \
		../../include/qconfig-medium.h \
		../../include/qconfig-large.h \
		../../include/qconfig.h \
		../../include/qmodules.h \
		../../include/qfeatures.h \
		../../include/qcstring.h \
		../../include/qmemarray.h \
		../../include/qgarray.h \
		../../include/qshared.h \
		../../include/qevent.h \
		../../include/qregion.h \
		../../include/qmime.h \
		../../include/qpair.h \
		../../include/qrect.h \
		../../include/qsize.h \
		../../include/qpoint.h \
		../../include/zutil.h \
		../../include/qdatastream.h \
		../../include/qvaluelist.h \
		../../include/zlib.h \
		../../include/qiodevice.h \
		../../include/qtl.h \
		../../include/qglist.h \
		../../include/qptrcollection.h \
		../../include/qcolor.h \
		../../include/qbrush.h \
		../../include/qstrlist.h \
		../../include/qdockwindow.h \
		../../include/qframe.h \
		../../include/qpixmap.h \
		../../include/qtextedit.h \
		../../include/qscrollview.h \
		../../include/qstylesheet.h \
		../../include/qptrvector.h \
		../../include/qscrollbar.h \
		../../include/qrangecontrol.h \
		../../include/qdict.h \
		../../include/qgvector.h \
		../../include/qgdict.h \
		../../include/qfileinfo.h \
		../../include/qfile.h \
		../../include/qdatetime.h \
		../../include/qdesktopwidget.h \
		../../include/qasciidict.h \
		../../include/qtranslator.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/main.o main.cpp

.obj/release-shared/moc_helpwindow.o: .moc/release-shared/moc_helpwindow.cpp  helpwindow.h ../../include/qmainwindow.h \
		../../include/qtextbrowser.h \
		../../include/qstringlist.h \
		../../include/qmap.h \
		../../include/qdir.h \
		../../include/qwidget.h \
		../../include/qtoolbar.h \
		../../include/qptrlist.h \
		../../include/qtextstream.h \
		../../include/qwindowdefs.h \
		../../include/qobject.h \
		../../include/qpaintdevice.h \
		../../include/qpalette.h \
		../../include/qfont.h \
		../../include/qfontmetrics.h \
		../../include/qfontinfo.h \
		../../include/qsizepolicy.h \
		../../include/qwinexport.h \
		../../include/qobjectdefs.h \
		../../include/qstring.h \
		../../include/qnamespace.h \
		../../include/qglobal.h \
		../../include/qconfig-minimal.h \
		../../include/qconfig-small.h \
		../../include/qconfig-medium.h \
		../../include/qconfig-large.h \
		../../include/qconfig.h \
		../../include/qmodules.h \
		../../include/qfeatures.h \
		../../include/qcstring.h \
		../../include/qmemarray.h \
		../../include/qgarray.h \
		../../include/qshared.h \
		../../include/qevent.h \
		../../include/qregion.h \
		../../include/qmime.h \
		../../include/qpair.h \
		../../include/qrect.h \
		../../include/qsize.h \
		../../include/qpoint.h \
		../../include/zutil.h \
		../../include/qdatastream.h \
		../../include/qvaluelist.h \
		../../include/zlib.h \
		../../include/qiodevice.h \
		../../include/qtl.h \
		../../include/qglist.h \
		../../include/qptrcollection.h \
		../../include/qcolor.h \
		../../include/qbrush.h \
		../../include/qstrlist.h \
		../../include/qdockwindow.h \
		../../include/qframe.h \
		../../include/qpixmap.h \
		../../include/qtextedit.h \
		../../include/qscrollview.h \
		../../include/qstylesheet.h \
		../../include/qptrvector.h \
		../../include/qscrollbar.h \
		../../include/qrangecontrol.h \
		../../include/qdict.h \
		../../include/qgvector.h \
		../../include/qgdict.h \
		../../include/qfileinfo.h \
		../../include/qfile.h \
		../../include/qdatetime.h
	$(CXX) -c $(CXXFLAGS) $(INCPATH) -o .obj/release-shared/moc_helpwindow.o .moc/release-shared/moc_helpwindow.cpp

.moc/release-shared/moc_helpwindow.cpp: $(MOC) helpwindow.h
	$(MOC) helpwindow.h -o .moc/release-shared/moc_helpwindow.cpp

####### Install

install:  

uninstall:  

