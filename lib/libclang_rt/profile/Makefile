# $FreeBSD$

.include <bsd.init.mk>

LIB=	clang_rt.profile-${CRTARCH}

.PATH:	${CRTSRC}/lib/profile

SRCS=	GCDAProfiling.c\
	InstrProfiling.c\
	InstrProfilingBuffer.c\
	InstrProfilingFile.c\
	InstrProfilingPlatformDarwin.c\
	InstrProfilingPlatformOther.c\
	InstrProfilingRuntime.cc\

.include <bsd.lib.mk>
