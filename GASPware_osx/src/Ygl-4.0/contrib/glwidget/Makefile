# Makefile generated by imake - do not edit!
# $XConsortium: imake.c,v 1.91 95/01/12 16:15:47 kaleb Exp $

# ----------------------------------------------------------------------
# Makefile generated from "Imake.tmpl" and <Imakefile>
# $XConsortium: Imake.tmpl,v 1.224.1.1 95/06/19 17:51:01 gildea Exp $
#

.SUFFIXES: .i

# $XConsortium: Imake.cf,v 1.19 95/01/05 19:24:32 kaleb Exp $

# -----------------------------------------------------------------------
# site-specific configuration parameters that need to come before
# the platform-specific parameters - edit site.def to change

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# site:  $XConsortium: site.sample,v 1.9 94/04/08 17:02:06 rws Exp $

# -----------------------------------------------------------------------
# platform-specific configuration parameters - edit osf1.cf to change

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# platform:  $XConsortium: osf1.cf,v 1.42.1.1 94/09/15 20:41:35 kaleb Exp $

# operating system:  OSF/1 4.0

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# $XConsortium: osfLib.rules,v 1.9 94/01/18 14:58:49 rws Exp $

# -----------------------------------------------------------------------
# site-specific configuration parameters that go after
# the platform-specific parameters - edit site.def to change

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# site:  $XConsortium: site.sample,v 1.9 94/04/08 17:02:06 rws Exp $

RTOP = $(TOP)/..
DPSTop = $(RTOP)/adobe/dps
DPSSRC = $(DPSTop)
DPSLIBSRC = $(DPSSRC)/lib/dps
DPSTKSRC = $(DPSTop)/lib/dpstk
PSRESSRC = $(DPSTop)/lib/psres

# -----------------------------------------------------------------------
# Imake rules for building libraries, programs, scripts, and data files
# rules:  $XConsortium: Imake.rules,v 1.197.1.1 95/06/19 18:01:48 gildea Exp $

 _NULLCMD_ = @ echo '\c'

          PATHSEP = /
            SHELL = /bin/sh

              TOP = .
      CURRENT_DIR = .

            IMAKE = imake
           DEPEND = makedepend
        MKDIRHIER = mkdirhier
        CONFIGSRC = $(TOP)/config
         IMAKESRC = $(CONFIGSRC)/imake
        DEPENDSRC = $(CONFIGSRC)/makedepend
           IXXSRC = $(UNSUPPORTEDSRC)/programs/ixx
              IXX = ixx
         IXXFLAGS = -s BaseObject -m TypeObj -r RequestObj -p Xf
      IXXINCLUDES = -i '<X11/Fresco/enter-scope.h>'

          INCROOT = /usr/include
        USRLIBDIR = /usr/lib
         SHLIBDIR = /usr/shlib
       LINTLIBDIR = $(USRLIBDIR)/lint
          MANPATH = /usr/man
    MANSOURCEPATH = $(MANPATH)/man
           MANDIR = $(MANSOURCEPATH)$(MANSUFFIX)
        LIBMANDIR = $(MANSOURCEPATH)$(LIBMANSUFFIX)
       FILEMANDIR = $(MANSOURCEPATH)$(FILEMANSUFFIX)

               AR = ar clqZ
  BOOTSTRAPCFLAGS =
               CC = cc $(SHAREDSWITCH)
               AS = as

.SUFFIXES: .cxx

              CXX = cxx
    CXXDEBUGFLAGS = -O2
 CXXEXTRA_DEFINES =
CXXEXTRA_INCLUDES =
  CXXIDL_INCLUDES = -I$(TOP)/include
   CXXSTD_DEFINES = -D__STDC__=1 -DLONG_BIT=64
       CXXOPTIONS =
  CXXSTD_INCLUDES =
      CXXINCLUDES = $(INCLUDES) $(TOP_INCLUDES) $(CXXEXTRA_INCLUDES) $(CXXSTD_INCLUDES) $(CXXIDL_INCLUDES)
       CXXDEFINES = $(CXXINCLUDES) $(CXXSTD_DEFINES) $(THREADS_CXXDEFINES) $(CXXEXTRA_DEFINES)
         CXXFLAGS = $(CXXDEBUGFLAGS) $(CXXOPTIONS) $(THREADS_CXXFLAGS) $(CXXDEFINES)

         COMPRESS = compress
              CPP = /lib/cpp $(STD_CPP_DEFINES)
    PREPROCESSCMD = cc $(SHAREDSWITCH) -E $(STD_CPP_DEFINES)
          INSTALL = installbsd
     INSTALLFLAGS = -c
               LD = ld
              LEX = lex
           LEXLIB = -ll
             YACC = yacc
           CCYACC = yacc
             LINT = lint
      LINTLIBFLAG = -C
         LINTOPTS = -axz
               LN = ln -s
             MAKE = make
               MV = mv -f
               CP = cp

               RM = rm -f
        MANSUFFIX = n
     LIBMANSUFFIX = 3
    FILEMANSUFFIX = 4
            TROFF = psroff
         MSMACROS = -ms
              TBL = tbl
              EQN = eqn

            DVIPS = dvips
            LATEX = latex

     STD_INCLUDES =
  STD_CPP_DEFINES = -DLONG_BIT=64
      STD_DEFINES = -DLONG_BIT=64
 EXTRA_LOAD_FLAGS =
  EXTRA_LDOPTIONS =
  EXTRA_LIBRARIES =
             TAGS = ctags

    SHAREDCODEDEF =
         SHLIBDEF =

     SHLIBLDFLAGS = -shared -no_archive

         PICFLAGS =

      CXXPICFLAGS =

    PROTO_DEFINES =

     INSTPGMFLAGS =

     INSTBINFLAGS = -m 0755
     INSTUIDFLAGS = -m 4755
     INSTLIBFLAGS = -m 0644
     INSTINCFLAGS = -m 0444
     INSTMANFLAGS = -m 0444
     INSTDATFLAGS = -m 0444
    INSTKMEMFLAGS = -m 4755

      PROJECTROOT = /usr

     TOP_INCLUDES = -I$(INCROOT)

      CDEBUGFLAGS = -O2
        CCOPTIONS = -std1

      ALLINCLUDES = $(INCLUDES) $(EXTRA_INCLUDES) $(TOP_INCLUDES) $(STD_INCLUDES)
       ALLDEFINES = $(ALLINCLUDES) $(STD_DEFINES) $(EXTRA_DEFINES) $(PROTO_DEFINES) $(THREADS_DEFINES) $(DEFINES)
           CFLAGS = $(CDEBUGFLAGS) $(CCOPTIONS) $(THREADS_CFLAGS) $(ALLDEFINES)
        LINTFLAGS = $(LINTOPTS) -DLINT $(ALLDEFINES) $(DEPEND_DEFINES)
         LDPRELIB = -L$(USRLIBDIR)
        LDPOSTLIB =
        LDOPTIONS = $(CDEBUGFLAGS) $(CCOPTIONS)  $(EXTRA_LDOPTIONS) $(THREADS_LDFLAGS) $(LOCAL_LDFLAGS) $(LDPRELIB)
     CXXLDOPTIONS = $(CXXDEBUGFLAGS) $(CXXOPTIONS) $(EXTRA_LDOPTIONS) $(THREADS_CXXLDFLAGS) $(LOCAL_LDFLAGS) $(LDPRELIB)

           LDLIBS = $(LDPOSTLIB) $(THREADS_LIBS) $(SYS_LIBRARIES) $(EXTRA_LIBRARIES)

           CCLINK = $(CC)

          CXXLINK = $(CXX)

     LDSTRIPFLAGS = -x
   LDCOMBINEFLAGS = -X -r
      DEPENDFLAGS =

        MACROFILE = osf1.cf
           RM_CMD = $(RM)

    IMAKE_DEFINES =

         IRULESRC = $(CONFIGDIR)
        IMAKE_CMD = $(IMAKE) -DUseInstalled -I$(IRULESRC) $(IMAKE_DEFINES)

     ICONFIGFILES = $(IRULESRC)/Imake.tmpl $(IRULESRC)/Project.tmpl \
			$(IRULESRC)/site.def $(IRULESRC)/$(MACROFILE) \
			 $(EXTRA_ICONFIGFILES)

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# @(#)$RCSfile: Dec.rules,v $ $Revision: 1.1.4.2 $ (DEC) $Date: 1995/12/20 21:18:49 $
#
# -------------------------------------------------------------------------
# DEC-Specific System Build Rules

#   $RCSfile: Motif.rules,v $ $Revision: 1.5.230.5 $ $Date: 1994/03/29 00:07:28 $

#pragma ident "@(#)$RCSfile: Project.tmpl,v $ $Revision: 1.1.6.8 $ (DEC) $Date: 1996/02/14 21:47:28 $"
# ----------------------------------------------------------------------
# X Window System Build Parameters and Rules
# $XConsortium: Project.tmpl /main/dbe950926/1 1995/09/26 17:04:28 dpw $

# -----------------------------------------------------------------------
# X Window System make variables; these need to be coordinated with rules

           BINDIR = /usr/bin/X11
     BUILDINCROOT = $(TOP)
      BUILDINCDIR = $(BUILDINCROOT)/X11
      BUILDINCTOP = ..
      BUILDLIBDIR = $(TOP)/usrlib
      BUILDLIBTOP = ..
           INCDIR = $(INCROOT)/X11
           ADMDIR = /usr/adm
           LIBDIR = $(USRLIBDIR)/X11
           VARDIR = /usr/var/X11
          FONTDIR = $(LIBDIR)/fonts
      USERFONTDIR = $(VARDIR)/fonts/user
         XINITDIR = $(LIBDIR)/xinit
           XDMDIR = $(VARDIR)/xdm
           TWMDIR = $(LIBDIR)/twm
           XSMDIR = $(LIBDIR)/xsm
           NLSDIR = $(LIBDIR)/nls
       XLOCALEDIR = $(LIBDIR)/locale
        PEXAPIDIR = $(LIBDIR)/PEX
      XAPPLOADDIR = $(LIBDIR)/app-defaults
       FONTCFLAGS = -t

     INSTAPPFLAGS = $(INSTDATFLAGS)

              RGB = rgb
            FONTC = bdftopcf
        MKFONTDIR = mkfontdir

       DOCUTILSRC = $(TOP)/doc/util
       XDOCMACROS = $(DOCUTILSRC)/macros.t
       XIDXMACROS = $(DOCUTILSRC)/indexmacros.t
       PROGRAMSRC = $(TOP)/programs
           LIBSRC = $(TOP)/lib
          FONTSRC = $(TOP)/fonts
       INCLUDESRC = $(TOP)/X11
        SERVERSRC = $(TOP)/programs/Xserver
          UTILSRC = $(TOP)/util
       CONTRIBSRC = $(TOP)/../contrib
   UNSUPPORTEDSRC = $(TOP)/unsupported
           DOCSRC = $(TOP)/doc
           RGBSRC = $(TOP)/programs/rgb
      BDFTOPCFSRC = $(PROGRAMSRC)/bdftopcf
     MKFONTDIRSRC = $(PROGRAMSRC)/mkfontdir
    FONTSERVERSRC = $(PROGRAMSRC)/xfs
       FONTINCSRC = $(TOP)/include/fonts
        EXTINCSRC = $(TOP)/include/extensions
     TRANSCOMMSRC = $(LIBSRC)/xtrans
   TRANS_INCLUDES = -I$(TRANSCOMMSRC)

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# @(#)$RCSfile: osfLib.tmpl,v $ $Revision: 1.1.4.5 $ (DEC) $Date: 1994/11/07 21:58:42 $
#
# $XConsortium: osfLib.tmpl,v 1.18 94/06/03 21:38:46 matt Exp $

          XLIBSRC = $(LIBSRC)/X11

SOXLIBREV = 6.0
DEPXONLYLIB =
XONLYLIB = -lX11

LINTXONLY = $(LINTLIBDIR)/llib-lX11.ln

         XLIBONLY = $(XONLYLIB)

      XEXTLIBSRC = $(LIBSRC)/Xext

SOXEXTREV = 6.0
DEPEXTENSIONLIB =
EXTENSIONLIB = -lXext

LINTEXTENSION = $(LINTLIBDIR)/llib-lXext.ln

LINTEXTENSIONLIB = $(LINTEXTENSION)
          DEPXLIB = $(DEPEXTENSIONLIB) $(DEPXONLYLIB)
             XLIB = $(EXTENSIONLIB) $(XONLYLIB)
         LINTXLIB = $(LINTXONLYLIB)

         XAUTHSRC = $(LIBSRC)/Xau

DEPXAUTHLIB = $(USRLIBDIR)/libXau.a
XAUTHLIB = -lXau

LINTXAUTH = $(LINTLIBDIR)/llib-lXau.ln

      XDMCPLIBSRC = $(LIBSRC)/Xdmcp

DEPXDMCPLIB = $(USRLIBDIR)/libXdmcp.a
XDMCPLIB = -lXdmcp

LINTXDMCP = $(LINTLIBDIR)/llib-lXdmcp.ln

           XMUSRC = $(LIBSRC)/Xmu

SOXMUREV = 6.0
DEPXMULIB =
XMULIB = -lXmu

LINTXMU = $(LINTLIBDIR)/llib-lXmu.ln

       OLDXLIBSRC = $(LIBSRC)/oldX

DEPOLDXLIB = $(USRLIBDIR)/liboldX.a
OLDXLIB = -loldX

LINTOLDX = $(LINTLIBDIR)/llib-loldX.ln

       TOOLKITSRC = $(LIBSRC)/Xt

SOXTREV = 6.0
DEPXTOOLONLYLIB =
XTOOLONLYLIB = -lXt

LINTXTOOLONLY = $(LINTLIBDIR)/llib-lXt.ln

      DEPXTOOLLIB = $(DEPXTOOLONLYLIB) $(DEPSMLIB) $(DEPICELIB)
         XTOOLLIB = $(XTOOLONLYLIB) $(SMLIB) $(ICELIB)
     LINTXTOOLLIB = $(LINTXTOOLONLYLIB)

       AWIDGETSRC = $(LIBSRC)/Xaw

SOXAWREV = 6.0
DEPXAWLIB =
XAWLIB = -lXaw

LINTXAW = $(LINTLIBDIR)/llib-lXaw.ln

       XTFSRC = $(TOP)/workInProgress/Xtf

SOXTFREV = 0.7
DEPXTFLIB =
XTFLIB = -lXtf

LINTXTF = $(LINTLIBDIR)/llib-lXtf.ln

       FRESCOSRC = $(TOP)/workInProgress/Fresco

SOFRESCOREV = 0.7
DEPFRESCOLIB =
FRESCOLIB = -lFresco

LINTFRESCO = $(LINTLIBDIR)/llib-lFresco.ln

         XILIBSRC = $(LIBSRC)/Xi

SOXINPUTREV = 6.0
DEPXILIB =
XILIB = -lXi

LINTXI = $(LINTLIBDIR)/llib-lXi.ln

      XTESTLIBSRC = $(LIBSRC)/Xtst

SOXTESTREV = 6.0
DEPXTESTLIB =
XTESTLIB = -lXtst

LINTXTEST = $(LINTLIBDIR)/llib-lXtst.ln

        PEXLIBSRC = $(LIBSRC)/PEX5

DEPPEXLIB = $(USRLIBDIR)/libPEX5.a
PEXLIB = -lPEX5

LINTPEX = $(LINTLIBDIR)/llib-lPEX5.ln

        XIELIBSRC = $(LIBSRC)/XIE

SOXIEREV = 6.0
DEPXIELIB =
XIELIB = -lXIE

LINTXIE = $(LINTLIBDIR)/llib-lXIE.ln

      PHIGSLIBSRC = $(LIBSRC)/PHIGS

DEPPHIGSLIB = $(USRLIBDIR)/libphigs.a
PHIGSLIB = -lphigs

LINTPHIGS = $(LINTLIBDIR)/llib-lphigs.ln

DEPXBSDLIB = $(USRLIBDIR)/libXbsd.a
XBSDLIB = -lXbsd

LINTXBSD = $(LINTLIBDIR)/llib-lXbsd.ln

           ICESRC = $(LIBSRC)/ICE

SOICEREV = 6.0
DEPICELIB =
ICELIB = -lICE

LINTICE = $(LINTLIBDIR)/llib-lICE.ln

            SMSRC = $(LIBSRC)/SM

SOSMREV = 6.0
DEPSMLIB =
SMLIB = -lSM

LINTSM = $(LINTLIBDIR)/llib-lSM.ln

         FSLIBSRC = $(LIBSRC)/FS

DEPFSLIB = $(USRLIBDIR)/libFS.a
FSLIB = -lFS

LINTFS = $(LINTLIBDIR)/llib-lFS.ln

SODPSREV = ShareddpsRev
DEPDPSLIB =
DPSLIB = -ldps

LINTDPS = $(LINTLIBDIR)/llib-ldps.ln

SODPSTKREV = 6.0
DEPDPSTKLIB =
DPSTKLIB = -ldpstk

LINTDPSTK = $(LINTLIBDIR)/llib-ldpstk.ln

SOPSRESREV = 6.0
DEPPSRESLIB =
PSRESLIB = -lpsres

LINTPSRES = $(LINTLIBDIR)/llib-lpsres.ln

         FONTLIBSRC = $(LIBSRC)/font

DEPFONTLIB = $(USRLIBDIR)/libfont.a
FONTLIB = -lfont

LINTFONT = $(LINTLIBDIR)/llib-lfont.ln

DEPFONT_STATICLIB = $(USRLIBDIR)/libfont_static.a
FONT_STATICLIB = -lfont_static

LINTFONT_STATIC = $(LINTLIBDIR)/llib-lfont_static.ln

    XKBFILELIBSRC = $(LIBSRC)/xkbfile

DEPXKBFILELIB = $(USRLIBDIR)/libxkbfile.a
XKBFILELIB = -lxkbfile

LINTXKBFILE = $(LINTLIBDIR)/llib-lxkbfile.ln

          DEPLIBS = $(DEPXAWLIB) $(DEPXMULIB) $(DEPXTOOLLIB) $(DEPXLIB)

         DEPLIBS1 = $(DEPLIBS)
         DEPLIBS2 = $(DEPLIBS)
         DEPLIBS3 = $(DEPLIBS)

#
# *****************************************************************
# *                                                               *
# *    Copyright (c) Digital Equipment Corporation, 1991, 1999    *
# *                                                               *
# *   All Rights Reserved.  Unpublished rights  reserved  under   *
# *   the copyright laws of the United States.                    *
# *                                                               *
# *   The software contained on this media  is  proprietary  to   *
# *   and  embodies  the  confidential  technology  of  Digital   *
# *   Equipment Corporation.  Possession, use,  duplication  or   *
# *   dissemination of the software and media is authorized only  *
# *   pursuant to a valid written license from Digital Equipment  *
# *   Corporation.                                                *
# *                                                               *
# *   RESTRICTED RIGHTS LEGEND   Use, duplication, or disclosure  *
# *   by the U.S. Government is subject to restrictions  as  set  *
# *   forth in Subparagraph (c)(1)(ii)  of  DFARS  252.227-7013,  *
# *   or  in  FAR 52.227-19, as applicable.                       *
# *                                                               *
# *****************************************************************
#
# HISTORY
#
# @(#)$RCSfile: Dec.tmpl,v $ $Revision: 1.1.2.13 $ (DEC) $Date: 1995/06/22 15:38:09 $
#
# -------------------------------------------------------------------------
# DEC-Specific System Build Parameters

          HELPDIR = $(LIBDIR)/help
           UIDDIR = $(LIBDIR)/uid
           CDADIR = $(USRLIBDIR)/cda

           DXMSRC = $(MLIBSRC)/DXm
           XIESRC = $(LIBSRC)/XIE
           IDSSRC = $(MLIBSRC)/ids
           BKRSRC = $(MLIBSRC)/bkr
        DWI18NSRC = $(MLIBSRC)/dwi18n
           LWKSRC = $(MLIBSRC)/lwk
           DVRSRC = $(MLIBSRC)/dvr

        XSHLIBDIR = /usr/shlib/X11

       DEPDXMLIB = $(USRSHLIBDIR)/libDXm.so
          DXMLIB = -lDXm

       MDXMLIB = $(DXMLIB)

        DEPXIELIB = $(USRSHLIBDIR)/libXIE.so
           XIELIB = -lXIE

        DEPIDSLIB = $(USRSHLIBDIR)/libids.so
           IDSLIB = -lids

        DEPBKRLIB = $(USRSHLIBDIR)/libbkr.so
           BKRLIB = -lbkr

        DEPDWI18NLIB = $(USRLIBDIR)/libdwi18n.a
           DWI18NLIB =  -ldwi18n

        DEPLWKLIB = $(USRSHLIBDIR)/liblwkdxm.so
           LWKLIB = -llwkdxm

        DEPDVRLIB = $(USRSHLIBDIR)/libdvr.so
           DVRLIB = -ldvr

        DEPIMGLIB =
        DEPIPSLIB =
        DEPCHFLIB =
        DEPCDALIB =
        DEPDVSLIB =

    DEPIDS_NOXLIB =

           IMGLIB = -limg
           IPSLIB = -lips
           CHFLIB = -lchf
           CDALIB = -lcda
       IDS_NOXLIB = -lids_nox
           DVSLIB = -ldvs

     DEBUGUSRLIBDIR=/usr/debugshlib

            LOCAR = LocArCmd
            LOCCC = cc
        LOCSHARCC = LocShareCcCmd
  LOCSTD_INCLUDES =
 LOCEXTRA_LIBRARIES =
     LOCCCOPTIONS = -non_shared -std1
   LOCALLINCLUDES = $(INCLUDES) $(EXTRA_INCLUDES) $(TOP_INCLUDES) $(LOCSTD_INCLUDES)
    LOCALLDEFINES = $(LOCALLINCLUDES) $(STD_DEFINES) $(EXTRA_DEFINES) $(PROTO_DEFINES) $(DEFINES)
        LOCCFLAGS = $(CDEBUGFLAGS) $(LOCCCOPTIONS) $(LOCALLDEFINES)

        LOCLDLIBS = $(SYS_LIBRARIES) $(LOCEXTRA_LIBRARIES)

     LOCLDOPTIONS = $(CDEBUGFLAGS) $(LOCCCOPTIONS) $(LOCAL_LDFLAGS) -L$(USRLIBDIR)

#   XRCSfile: Motif.tmpl,v $ $Revision: 1.1.2.9 $ $Date: 1995/01/25 22:13:08 $

          SOXMREV = GlobalSharedRev
         SOMRMREV = GlobalSharedRev
         SOUILREV = GlobalSharedRev
     SOACOMMONREV = GlobalSharedRev
      SOSCRIPTREV = GlobalSharedRev
        SOUTILREV = GlobalSharedRev
      SOCREATEREV = GlobalSharedRev
      SOVISUALREV = GlobalSharedRev
       SOSYNTHREV = GlobalSharedRev
     SOMCOMMONREV = GlobalSharedRev

              XTOP = $(TOP)/../xc
              MTOP = $(TOP)
     XBUILDINCROOT = $(XTOP)
      XBUILDINCDIR = $(XBUILDINCROOT)/X11

         CLIENTSRC = $(XTOP)/programs
           DEMOSRC = $(XTOP)/demos
            LIBSRC = $(XTOP)/lib
           FONTSRC = $(XTOP)/fonts
        INCLUDESRC = $(XTOP)/X11
         SERVERSRC = $(XTOP)/programs/Xserver
           UTILSRC = $(XTOP)/util
        EXAMPLESRC = $(XTOP)/examples
            DOCSRC = $(XTOP)/doc
            RGBSRC = $(XTOP)/programs/rgb
      EXTENSIONSRC = $(XTOP)/extensions

      TOP_INCLUDES = -I$(INCROOT)

      UIL_INCLUDES = -I$(USRINCDIR)/uil

     XPM_DEFINES =

     XPM_TOP = $(XTOP)

     XPM_INCLUDES	= -I$(XPM_TOP)/include/X11

     XPM_LIBS		= $(XPM_TOP)/lib/libXpm.a

      USRINCDIR = /usr/include
         UIDDIR = $(LIBDIR)/uid
        TESTSRC = $(MTOP)/tests
        TESTLIB = $(TESTSRC)/lib
  GENERALSRCLIB = $(TESTSRC)/General/lib
  GENERALSRCBIN = $(TESTSRC)/General/bin
   MANUALSRCLIB = $(TESTSRC)/Manual/lib
   MANUALSRCBIN = $(TESTSRC)/Manual/bin
     AUTOSRCLIB = $(TESTSRC)/Auto/lib
     AUTOSRCBIN = $(TESTSRC)/Auto/bin
       COMMONPP = $(GENERALSRCBIN)/Commonpp
         GENRUN = $(GENERALSRCBIN)/Genrun
         MANRUN = $(GENERALSRCBIN)/Manrun

     TESTCOMSRC = $(MANUALSRCLIB)/Common

    MTOOLKITSRC = $(TOOLKITSRC)
    MINCLUDESRC = $(MTOP)/X11
        MLIBSRC = $(MTOP)/lib
     MCLIENTSRC = $(MTOP)/clients
       MDEMOSRC = $(MTOP)/demos
     MWIDGETSRC = $(MLIBSRC)/Xm
   MRESOURCESRC = $(MLIBSRC)/Mrm
         UILSRC = $(MCLIENTSRC)/uil

            UIL = uil

   XMEXTRA_LIBS =

SOXMREV = GlobalSharedRev
DEPXMLIBONLYLIB =
XMLIBONLYLIB = -lXm

LINTXMLIBONLY = $(LINTLIBDIR)/llib-lXm.ln

   XMLIB = $(XMLIBONLYLIB)
   DEPXMLIB = $(DEPXMLIBONLYLIB)

SOMRMREV = GlobalSharedRev
DEPMRESOURCELIBLIB =
MRESOURCELIBLIB = -lMrm

LINTMRESOURCELIB = $(LINTLIBDIR)/llib-lMrm.ln

$(SOUILREV) = GlobalSharedRev
DEPUILLIBLIB =
UILLIBLIB = -lUil

LINTUILLIB = $(LINTLIBDIR)/llib-lUil.ln

$(SOMCOMMONREV) = GlobalSharedRev
DEPTESTCOMLIBLIB =
TESTCOMLIBLIB = -lCommon

LINTTESTCOMLIB = $(LINTLIBDIR)/llib-lCommon.ln

TESTUILCOMLIB = $(TESTCOMSRC)/libCommonUil.a

  LINTMRESOURCE = $(MRESOURCESRC)/libMrm.a
LINTXMWIDGETLIB = $(MWIDGETSRC)/llib-l/Xm.ln
     LINTXMTOOL = $(MTOOLKITSRC)/llib-lXt.ln
     LINTUILLIB = $(UILSRC)/llib-lUil.ln

      YACCFLAGS =
       UILFLAGS =

         RM_CMD = $(RM) *.CKP *.ln *.BAK *.bak *.o core errs ,* *~ *.a .emacs_* tags TAGS make.log MakeOut  *.Dat

    STD_DEFINES = -DLONG_BIT=64  -DNO_MESSAGE_CATALOG

        DEPLIBS = $(DEPXMLIB) $(DEPXTOOLLIB) $(DEPXLIB)

        DEPLIBS1 = $(DEPLIBS)
        DEPLIBS2 = $(DEPLIBS)
        DEPLIBS3 = $(DEPLIBS)

        SODXMREV = GlobalSharedRev

        MDXMSRC = $(MLIBSRC)/DXm

SOMRMREV = GlobalSharedRev
DEPMDXMLIBLIB =
MDXMLIBLIB = -lDXm

LINTMDXMLIB = $(LINTLIBDIR)/llib-lDXm.ln

CONFIGSRC = $(XTOP)/config

        CONFIGDIR = $(LIBDIR)/config

# -----------------------------------------------------------------------
# start of Imakefile

SUBDIRS = examples

GLINCLUDEDIR = /usr/include/gl

REQUIREDLIBS 	= 	-lYgl 
TARGET		= glwidget

SRCS = glwidget.c
OBJS = glwidget.o

INCLUDES = -I.

MANSUFFIX = 3
MANDIR = /usr/local/man/man$(MANSUFFIX)

XLIBS = $(REQUIREDLIBS)

all:: lib$(TARGET).a

lib$(TARGET).a: $(OBJS)
	$(RM) $@
	$(AR) $@ $(OBJS)
	$(_NULLCMD_)
	$(_NULLCMD_)

install:: lib$(TARGET).a
	@if [ -d $(DESTDIR)$(USRLIBDIR) ]; then set +x; \
	else (set -x; $(MKDIRHIER) $(DESTDIR)$(USRLIBDIR)); fi
	$(INSTALL) $(INSTALLFLAGS) $(INSTLIBFLAGS) lib$(TARGET).a $(DESTDIR)$(USRLIBDIR)
	$(_NULLCMD_)

INSTALLFLAGS = $(INSTINCFLAGS)

install:: glwidget.h
	@if [ -d $(DESTDIR)$(GLINCLUDEDIR) ]; then set +x; \
	else (set -x; $(MKDIRHIER) $(DESTDIR)$(GLINCLUDEDIR)); fi
	@case '${MFLAGS}' in *[i]*) set +e;; esac; \
	for i in glwidget.h; do \
	(set -x; $(INSTALL) $(INSTALLFLAGS) $(INSTDATFLAGS) $$i $(DESTDIR)$(GLINCLUDEDIR)); \
	done

depend::
	$(DEPEND) $(DEPENDFLAGS) -- $(ALLDEFINES) $(DEPEND_DEFINES) -- $(SRCS)

all::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "making" all "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) CDEBUGFLAGS='$(CDEBUGFLAGS)' all); \
	done

depend::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "depending" "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) depend); \
	done

install.man:: $(TARGET).man
	@if [ -d $(DESTDIR)$(MANDIR) ]; then set +x; \
	else (set -x; $(MKDIRHIER) $(DESTDIR)$(MANDIR)); fi
	$(INSTALL) $(INSTALLFLAGS) $(INSTMANFLAGS) $(TARGET).man $(DESTDIR)$(MANDIR)/$(TARGET).$(MANSUFFIX)

etags::
	etags -t $(SRCS) glwidget.h

tarfile::
	make clean
	-ln -f Makefile.std Makefile
	-(cd examples; ln -f Makefile.std Makefile)
	(cd ..;gtar -cvf glwidget-1.1alpha.tar glwidget;\
	/bin/rm -rf /users/fred/prog/Ygl/src/contrib/glwidget/?*;\
	gtar -xvf glwidget-1.1alpha.tar -C /users/fred/prog/Ygl/src/contrib/;\
	gzip -f glwidget-1.1alpha.tar)

# -----------------------------------------------------------------------
# common rules for all Makefiles - do not edit

.c.i:
	$(RM) $@
	$(CC) -E $(CFLAGS) $(_NOOP_) $*.c > $@

emptyrule::

clean::
	$(RM_CMD) *.CKP *.ln *.BAK *.bak *.o core errs ,* *~ *.a .emacs_* tags TAGS make.log MakeOut "#"*

Makefile::
	-@if [ -f Makefile ]; then set -x; \
	$(RM) Makefile.bak; $(MV) Makefile Makefile.bak; \
	else exit 0; fi
	$(IMAKE_CMD) -DTOPDIR=$(TOP) -DCURDIR=$(CURRENT_DIR)

tags::
	$(TAGS) -w *.[ch]
	$(TAGS) -xw *.[ch] > TAGS

# -----------------------------------------------------------------------
# rules for building in SUBDIRS - do not edit

install::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "installing" "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) DESTDIR=$(DESTDIR) install); \
	done

install.man::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "installing man pages" "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) DESTDIR=$(DESTDIR) install.man); \
	done

clean::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "cleaning" "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) RM_CMD='$(RM_CMD)' clean); \
	done

tags::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo "tagging" "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) TAGS='$(TAGS)' tags); \
	done

Makefiles::
	-@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	case '${MFLAGS}' in *n*) executeit="no";; esac; \
	for i in $(SUBDIRS) ;\
	do \
	case "$(CURRENT_DIR)" in \
	.) curdir= ;; \
	*) curdir=$(CURRENT_DIR)/ ;; \
	esac; \
	echo "making Makefiles in $$curdir$$i..."; \
	itmp="$$i" \
	curtmp="$(CURRENT_DIR)" \
	toptmp=""; \
	case "$$itmp" in \
	../?*) \
	while echo "$$itmp" | grep '^../' > /dev/null;\
	do \
	toptmp="/`basename $$curtmp`$$toptmp"; \
	curtmp="`dirname $$curtmp`"; \
	itmp="`echo $$itmp | sed 's;../;;'`"; \
	done \
	;; \
	esac; \
	case "$$itmp" in \
	*/?*/?*/?*/?*)	newtop=../../../../..;; \
	*/?*/?*/?*)	newtop=../../../..;; \
	*/?*/?*)	newtop=../../..;; \
	*/?*)	newtop=../..;; \
	*)	newtop=..;; \
	esac; \
	newtop="$$newtop$$toptmp"; \
	case "$(TOP)" in \
	/?*) imaketop=$(TOP) \
	imakeprefix= ;; \
	.) imaketop=$$newtop \
	imakeprefix=$$newtop/ ;; \
	*) imaketop=$$newtop/$(TOP) \
	imakeprefix=$$newtop/ ;; \
	esac; \
	cd $$i; \
	$(RM) Makefile.bak; \
	if [ -f Makefile ]; then \
	echo "	$(MV) Makefile Makefile.bak"; \
	if [ "$$executeit" != "no" ]; then \
	$(MV) Makefile Makefile.bak; \
	fi; \
	fi; \
	if [ "$$executeit" != "no" ]; then \
	$(IMAKE_CMD) -DTOPDIR=$$imaketop -DCURDIR=$$curdir$$i; \
	fi; \
	$(MAKE) $(MFLAGS) Makefiles; \
	cd $$newtop; \
	done

includes::
	@case '${MFLAGS}' in *[ik]*) set +e;; esac; \
	for i in $(SUBDIRS) ;\
	do \
	(cd $$i ; echo including "in $(CURRENT_DIR)/$$i..."; \
	$(MAKE) $(MFLAGS) includes); \
	done

# -----------------------------------------------------------------------
# dependencies generated by makedepend

