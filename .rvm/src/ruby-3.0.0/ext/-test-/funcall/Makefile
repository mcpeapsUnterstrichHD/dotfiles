
SHELL = /bin/sh

# V=0 quiet, V=1 verbose.  other values don't work.
V = 0
Q1 = $(V:1=)
Q = $(Q1:0=@)
ECHO1 = $(V:1=@ :)
ECHO = $(ECHO1:0=@ echo)
NULLCMD = :

#### Start of system configuration section. ####
top_srcdir = $(topdir)/.
srcdir = $(top_srcdir)/ext/-test-/funcall
topdir = ../../..
hdrdir = $(top_srcdir)/include
arch_hdrdir = $(extout)/include/$(arch)
PATH_SEPARATOR = :
VPATH = $(srcdir):$(arch_hdrdir)/ruby:$(hdrdir)/ruby
RUBYLIB =
RUBYOPT = -
prefix = $(DESTDIR)/Users/mahd/.rvm/rubies/ruby-3.0.0
rubysitearchprefix = $(rubylibprefix)/$(sitearch)
rubyarchprefix = $(rubylibprefix)/$(arch)
rubylibprefix = $(libdir)/$(RUBY_BASE_NAME)
exec_prefix = $(prefix)
vendorarchhdrdir = $(vendorhdrdir)/$(sitearch)
sitearchhdrdir = $(sitehdrdir)/$(sitearch)
rubyarchhdrdir = $(rubyhdrdir)/$(arch)
vendorhdrdir = $(rubyhdrdir)/vendor_ruby
sitehdrdir = $(rubyhdrdir)/site_ruby
rubyhdrdir = $(includedir)/$(RUBY_VERSION_NAME)
vendorarchdir = $(vendorlibdir)/$(sitearch)
vendorlibdir = $(vendordir)/$(ruby_version)
vendordir = $(rubylibprefix)/vendor_ruby
sitearchdir = $(sitelibdir)/$(sitearch)
sitelibdir = $(sitedir)/$(ruby_version)
sitedir = $(rubylibprefix)/site_ruby
rubyarchdir = $(rubylibdir)/$(arch)
rubylibdir = $(rubylibprefix)/$(ruby_version)
sitearchincludedir = $(includedir)/$(sitearch)
archincludedir = $(includedir)/$(arch)
sitearchlibdir = $(libdir)/$(sitearch)
archlibdir = $(libdir)/$(arch)
ridir = $(datarootdir)/$(RI_BASE_NAME)
mandir = $(datarootdir)/man
localedir = $(datarootdir)/locale
libdir = $(exec_prefix)/lib
psdir = $(docdir)
pdfdir = $(docdir)
dvidir = $(docdir)
htmldir = $(docdir)
infodir = $(datarootdir)/info
docdir = $(datarootdir)/doc/$(PACKAGE)
oldincludedir = $(SDKROOT)/usr/include
includedir = $(prefix)/include
runstatedir = $(localstatedir)/run
localstatedir = $(prefix)/var
sharedstatedir = $(prefix)/com
sysconfdir = $(prefix)/etc
datadir = $(datarootdir)
datarootdir = $(prefix)/share
libexecdir = $(exec_prefix)/libexec
sbindir = $(exec_prefix)/sbin
bindir = $(exec_prefix)/bin
archdir = $(rubyarchdir)


CC_WRAPPER = 
CC = gcc -fdeclspec
CXX = g++ -fdeclspec
LIBRUBY = $(LIBRUBY_SO)
LIBRUBY_A = lib$(RUBY_SO_NAME)-static.a
LIBRUBYARG_SHARED = -l$(RUBY_SO_NAME)
LIBRUBYARG_STATIC = -l$(RUBY_SO_NAME)-static -framework Security -framework Foundation $(MAINLIBS)
empty =
OUTFLAG = -o $(empty)
COUTFLAG = -o $(empty)
CSRCFLAG = $(empty)

RUBY_EXTCONF_H = extconf.h
cflags   = $(optflags) $(debugflags) $(warnflags)
cxxflags = 
optflags = -O3
debugflags = -ggdb3
warnflags = -Wall -Wextra -Wdeprecated-declarations -Wdivision-by-zero -Wimplicit-function-declaration -Wimplicit-int -Wmisleading-indentation -Wpointer-arith -Wshorten-64-to-32 -Wwrite-strings -Wmissing-noreturn -Wno-cast-function-type -Wno-constant-logical-operand -Wno-long-long -Wno-missing-field-initializers -Wno-overlength-strings -Wno-parentheses-equality -Wno-self-assign -Wno-tautological-compare -Wno-unused-parameter -Wno-unused-value -Wunused-variable -Wextra-tokens
cppflags = 
CCDLFLAGS = -fno-common
CFLAGS   = $(CCDLFLAGS) -O3 -I/opt/homebrew/opt/libyaml/include -I/opt/homebrew/opt/libksba/include -I/opt/homebrew/opt/readline/include -I/opt/homebrew/opt/zlib/include -I/opt/homebrew/opt/openssl@1.1/include -fno-common -pipe $(ARCH_FLAG)
INCFLAGS = -I. -I$(arch_hdrdir) -I$(hdrdir) -I$(srcdir)
DEFS     = 
CPPFLAGS = -DRUBY_EXTCONF_H=\"$(RUBY_EXTCONF_H)\" -D_XOPEN_SOURCE -D_DARWIN_C_SOURCE -D_DARWIN_UNLIMITED_SELECT -D_REENTRANT $(DEFS) $(cppflags)
CXXFLAGS = $(CCDLFLAGS)  $(ARCH_FLAG)
ldflags  = -L. -L/opt/homebrew/opt/libyaml/lib -L/opt/homebrew/opt/libksba/lib -L/opt/homebrew/opt/readline/lib -L/opt/homebrew/opt/zlib/lib -L/opt/homebrew/opt/openssl@1.1/lib -fstack-protector-strong -L/usr/local/lib
dldflags = -L/opt/homebrew/opt/libyaml/lib -L/opt/homebrew/opt/libksba/lib -L/opt/homebrew/opt/readline/lib -L/opt/homebrew/opt/zlib/lib -L/opt/homebrew/opt/openssl@1.1/lib -Wl,-undefined,dynamic_lookup 
ARCH_FLAG = -m64
DLDFLAGS = $(ldflags) $(dldflags) $(ARCH_FLAG)
LDSHARED = $(CC) -dynamic -bundle
LDSHAREDXX = $(CXX) -dynamic -bundle
AR = ar
EXEEXT = 

RUBY_INSTALL_NAME = $(RUBY_BASE_NAME)
RUBY_SO_NAME = ruby.3.0
RUBYW_INSTALL_NAME = 
RUBY_VERSION_NAME = $(RUBY_BASE_NAME)-$(ruby_version)
RUBYW_BASE_NAME = rubyw
RUBY_BASE_NAME = ruby

arch = arm64-darwin23
sitearch = $(arch)
ruby_version = 3.0.0
ruby = $(topdir)/miniruby -I'$(topdir)' -I'$(top_srcdir)/lib' -I'$(extout)/$(arch)' -I'$(extout)/common'
RUBY = $(ruby)
ruby_headers = $(hdrdir)/ruby.h $(hdrdir)/ruby/backward.h $(hdrdir)/ruby/ruby.h $(hdrdir)/ruby/defines.h $(hdrdir)/ruby/missing.h $(hdrdir)/ruby/intern.h $(hdrdir)/ruby/st.h $(hdrdir)/ruby/subst.h $(arch_hdrdir)/ruby/config.h $(RUBY_EXTCONF_H)

RM = rm -f
RM_RF = $(RUBY) -run -e rm -- -rf
RMDIRS = rmdir -p
MAKEDIRS = /opt/homebrew/opt/coreutils/bin/gmkdir -p
INSTALL = /opt/homebrew/opt/coreutils/bin/ginstall -c
INSTALL_PROG = $(INSTALL) -m 0755
INSTALL_DATA = $(INSTALL) -m 644
COPY = cp
TOUCH = exit >

#### End of system configuration section. ####

preload = 
EXTSO = 
libpath = . $(topdir)
LIBPATH =  -L. -L$(topdir)
DEFFILE = 

CLEANFILES = mkmf.log
DISTCLEANFILES = 
DISTCLEANDIRS = 

extout = $(topdir)/.ext
extout_prefix = $(extout)$(target_prefix)/
target_prefix = /-test-
LOCAL_LIBS = 
LIBS = $(LIBRUBYARG_SHARED)   
ORIG_SRCS = funcall.c
SRCS = $(ORIG_SRCS) 
OBJS = funcall.o
HDRS = 
LOCAL_HDRS = 
TARGET = funcall
TARGET_NAME = funcall
TARGET_ENTRY = Init_$(TARGET_NAME)
DLLIB = $(TARGET).bundle
EXTSTATIC = 
STATIC_LIB = 

TIMESTAMP_DIR = $(extout)/.timestamp
BINDIR        = $(extout)/bin
RUBYCOMMONDIR = $(extout)/common
RUBYLIBDIR    = $(RUBYCOMMONDIR)$(target_prefix)
RUBYARCHDIR   = $(extout)/$(arch)$(target_prefix)
HDRDIR        = $(extout)/include/ruby$(target_prefix)
ARCHHDRDIR    = $(extout)/include/$(arch)/ruby$(target_prefix)
TARGET_SO_DIR = $(RUBYARCHDIR)/
TARGET_SO     = $(TARGET_SO_DIR)$(DLLIB)
CLEANLIBS     = $(TARGET_SO) 
CLEANOBJS     = *.o  *.bak

all:    install
static: all
.PHONY: all install static install-so install-rb
.PHONY: clean clean-so clean-static clean-rb

clean-static::
clean-rb-default::
clean-rb::
clean-so::
clean: clean-so clean-static clean-rb-default clean-rb
		-$(Q)$(RM) $(CLEANLIBS) $(CLEANOBJS) $(CLEANFILES) .*.time

distclean-rb-default::
distclean-rb::
distclean-so::
distclean-static::
distclean: clean distclean-so distclean-static distclean-rb-default distclean-rb
		-$(Q)$(RM) Makefile $(RUBY_EXTCONF_H) conftest.* mkmf.log
		-$(Q)$(RM) core ruby$(EXEEXT) *~ $(DISTCLEANFILES)
		-$(Q)$(RMDIRS) $(DISTCLEANDIRS) 2> /dev/null || true

realclean: distclean
install: install-so install-rb

install-so: $(TARGET_SO)
clean-so::
	-$(Q)$(RM) $(TARGET_SO) $(TIMESTAMP_DIR)/$(arch)/.-test-.time
	-$(Q)$(RMDIRS) $(TARGET_SO_DIR) 2> /dev/null || true
clean-static::
	-$(Q)$(RM) $(STATIC_LIB)
install-rb: pre-install-rb do-install-rb install-rb-default
install-rb-default: pre-install-rb-default do-install-rb-default
pre-install-rb: Makefile
pre-install-rb-default: Makefile
do-install-rb:
do-install-rb-default:
pre-install-rb-default:
	@$(NULLCMD)
$(TIMESTAMP_DIR)/$(arch)/.-test-.time:
	$(Q) $(MAKEDIRS) $(@D) $(TARGET_SO_DIR)
	$(Q) $(TOUCH) $@

site-install: site-install-so site-install-rb
site-install-so: install-so
site-install-rb: install-rb

.SUFFIXES: .c .m .cc .mm .cxx .cpp .o .S

.cc.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cc.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.mm.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.mm.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cxx.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cxx.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.cpp.o:
	$(ECHO) compiling $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.cpp.S:
	$(ECHO) translating $(<)
	$(Q) $(CXX) $(INCFLAGS) $(CPPFLAGS) $(CXXFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.c.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.c.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

.m.o:
	$(ECHO) compiling $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -c $(CSRCFLAG)$<

.m.S:
	$(ECHO) translating $(<)
	$(Q) $(CC) $(INCFLAGS) $(CPPFLAGS) $(CFLAGS) $(COUTFLAG)$@ -S $(CSRCFLAG)$<

$(TARGET_SO): $(OBJS) Makefile $(TIMESTAMP_DIR)/$(arch)/.-test-.time
	$(ECHO) linking shared-object -test-/$(DLLIB)
	-$(Q)$(RM) $(@)
	$(Q) $(LDSHARED) -o $@ $(OBJS) $(LIBPATH) $(DLDFLAGS) $(LOCAL_LIBS) $(LIBS)
	$(Q) $(POSTLINK)



###
$(OBJS): $(RUBY_EXTCONF_H)

# AUTOGENERATED DEPENDENCIES START
funcall.o: $(RUBY_EXTCONF_H)
funcall.o: $(arch_hdrdir)/ruby/config.h
funcall.o: $(hdrdir)/ruby.h
funcall.o: $(hdrdir)/ruby/internal/anyargs.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/char.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/double.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/fixnum.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/gid_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/int.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/intptr_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/long.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/long_long.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/mode_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/off_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/pid_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/short.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/size_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/st_data_t.h
funcall.o: $(hdrdir)/ruby/internal/arithmetic/uid_t.h
funcall.o: $(hdrdir)/ruby/internal/assume.h
funcall.o: $(hdrdir)/ruby/internal/attr/alloc_size.h
funcall.o: $(hdrdir)/ruby/internal/attr/artificial.h
funcall.o: $(hdrdir)/ruby/internal/attr/cold.h
funcall.o: $(hdrdir)/ruby/internal/attr/const.h
funcall.o: $(hdrdir)/ruby/internal/attr/constexpr.h
funcall.o: $(hdrdir)/ruby/internal/attr/deprecated.h
funcall.o: $(hdrdir)/ruby/internal/attr/diagnose_if.h
funcall.o: $(hdrdir)/ruby/internal/attr/enum_extensibility.h
funcall.o: $(hdrdir)/ruby/internal/attr/error.h
funcall.o: $(hdrdir)/ruby/internal/attr/flag_enum.h
funcall.o: $(hdrdir)/ruby/internal/attr/forceinline.h
funcall.o: $(hdrdir)/ruby/internal/attr/format.h
funcall.o: $(hdrdir)/ruby/internal/attr/maybe_unused.h
funcall.o: $(hdrdir)/ruby/internal/attr/noalias.h
funcall.o: $(hdrdir)/ruby/internal/attr/nodiscard.h
funcall.o: $(hdrdir)/ruby/internal/attr/noexcept.h
funcall.o: $(hdrdir)/ruby/internal/attr/noinline.h
funcall.o: $(hdrdir)/ruby/internal/attr/nonnull.h
funcall.o: $(hdrdir)/ruby/internal/attr/noreturn.h
funcall.o: $(hdrdir)/ruby/internal/attr/pure.h
funcall.o: $(hdrdir)/ruby/internal/attr/restrict.h
funcall.o: $(hdrdir)/ruby/internal/attr/returns_nonnull.h
funcall.o: $(hdrdir)/ruby/internal/attr/warning.h
funcall.o: $(hdrdir)/ruby/internal/attr/weakref.h
funcall.o: $(hdrdir)/ruby/internal/cast.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/apple.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/clang.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/gcc.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/intel.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/msvc.h
funcall.o: $(hdrdir)/ruby/internal/compiler_is/sunpro.h
funcall.o: $(hdrdir)/ruby/internal/compiler_since.h
funcall.o: $(hdrdir)/ruby/internal/config.h
funcall.o: $(hdrdir)/ruby/internal/constant_p.h
funcall.o: $(hdrdir)/ruby/internal/core.h
funcall.o: $(hdrdir)/ruby/internal/core/rarray.h
funcall.o: $(hdrdir)/ruby/internal/core/rbasic.h
funcall.o: $(hdrdir)/ruby/internal/core/rbignum.h
funcall.o: $(hdrdir)/ruby/internal/core/rclass.h
funcall.o: $(hdrdir)/ruby/internal/core/rdata.h
funcall.o: $(hdrdir)/ruby/internal/core/rfile.h
funcall.o: $(hdrdir)/ruby/internal/core/rhash.h
funcall.o: $(hdrdir)/ruby/internal/core/robject.h
funcall.o: $(hdrdir)/ruby/internal/core/rregexp.h
funcall.o: $(hdrdir)/ruby/internal/core/rstring.h
funcall.o: $(hdrdir)/ruby/internal/core/rstruct.h
funcall.o: $(hdrdir)/ruby/internal/core/rtypeddata.h
funcall.o: $(hdrdir)/ruby/internal/ctype.h
funcall.o: $(hdrdir)/ruby/internal/dllexport.h
funcall.o: $(hdrdir)/ruby/internal/dosish.h
funcall.o: $(hdrdir)/ruby/internal/error.h
funcall.o: $(hdrdir)/ruby/internal/eval.h
funcall.o: $(hdrdir)/ruby/internal/event.h
funcall.o: $(hdrdir)/ruby/internal/fl_type.h
funcall.o: $(hdrdir)/ruby/internal/gc.h
funcall.o: $(hdrdir)/ruby/internal/glob.h
funcall.o: $(hdrdir)/ruby/internal/globals.h
funcall.o: $(hdrdir)/ruby/internal/has/attribute.h
funcall.o: $(hdrdir)/ruby/internal/has/builtin.h
funcall.o: $(hdrdir)/ruby/internal/has/c_attribute.h
funcall.o: $(hdrdir)/ruby/internal/has/cpp_attribute.h
funcall.o: $(hdrdir)/ruby/internal/has/declspec_attribute.h
funcall.o: $(hdrdir)/ruby/internal/has/extension.h
funcall.o: $(hdrdir)/ruby/internal/has/feature.h
funcall.o: $(hdrdir)/ruby/internal/has/warning.h
funcall.o: $(hdrdir)/ruby/internal/intern/array.h
funcall.o: $(hdrdir)/ruby/internal/intern/bignum.h
funcall.o: $(hdrdir)/ruby/internal/intern/class.h
funcall.o: $(hdrdir)/ruby/internal/intern/compar.h
funcall.o: $(hdrdir)/ruby/internal/intern/complex.h
funcall.o: $(hdrdir)/ruby/internal/intern/cont.h
funcall.o: $(hdrdir)/ruby/internal/intern/dir.h
funcall.o: $(hdrdir)/ruby/internal/intern/enum.h
funcall.o: $(hdrdir)/ruby/internal/intern/enumerator.h
funcall.o: $(hdrdir)/ruby/internal/intern/error.h
funcall.o: $(hdrdir)/ruby/internal/intern/eval.h
funcall.o: $(hdrdir)/ruby/internal/intern/file.h
funcall.o: $(hdrdir)/ruby/internal/intern/gc.h
funcall.o: $(hdrdir)/ruby/internal/intern/hash.h
funcall.o: $(hdrdir)/ruby/internal/intern/io.h
funcall.o: $(hdrdir)/ruby/internal/intern/load.h
funcall.o: $(hdrdir)/ruby/internal/intern/marshal.h
funcall.o: $(hdrdir)/ruby/internal/intern/numeric.h
funcall.o: $(hdrdir)/ruby/internal/intern/object.h
funcall.o: $(hdrdir)/ruby/internal/intern/parse.h
funcall.o: $(hdrdir)/ruby/internal/intern/proc.h
funcall.o: $(hdrdir)/ruby/internal/intern/process.h
funcall.o: $(hdrdir)/ruby/internal/intern/random.h
funcall.o: $(hdrdir)/ruby/internal/intern/range.h
funcall.o: $(hdrdir)/ruby/internal/intern/rational.h
funcall.o: $(hdrdir)/ruby/internal/intern/re.h
funcall.o: $(hdrdir)/ruby/internal/intern/ruby.h
funcall.o: $(hdrdir)/ruby/internal/intern/select.h
funcall.o: $(hdrdir)/ruby/internal/intern/select/largesize.h
funcall.o: $(hdrdir)/ruby/internal/intern/signal.h
funcall.o: $(hdrdir)/ruby/internal/intern/sprintf.h
funcall.o: $(hdrdir)/ruby/internal/intern/string.h
funcall.o: $(hdrdir)/ruby/internal/intern/struct.h
funcall.o: $(hdrdir)/ruby/internal/intern/thread.h
funcall.o: $(hdrdir)/ruby/internal/intern/time.h
funcall.o: $(hdrdir)/ruby/internal/intern/variable.h
funcall.o: $(hdrdir)/ruby/internal/intern/vm.h
funcall.o: $(hdrdir)/ruby/internal/interpreter.h
funcall.o: $(hdrdir)/ruby/internal/iterator.h
funcall.o: $(hdrdir)/ruby/internal/memory.h
funcall.o: $(hdrdir)/ruby/internal/method.h
funcall.o: $(hdrdir)/ruby/internal/module.h
funcall.o: $(hdrdir)/ruby/internal/newobj.h
funcall.o: $(hdrdir)/ruby/internal/rgengc.h
funcall.o: $(hdrdir)/ruby/internal/scan_args.h
funcall.o: $(hdrdir)/ruby/internal/special_consts.h
funcall.o: $(hdrdir)/ruby/internal/static_assert.h
funcall.o: $(hdrdir)/ruby/internal/stdalign.h
funcall.o: $(hdrdir)/ruby/internal/stdbool.h
funcall.o: $(hdrdir)/ruby/internal/symbol.h
funcall.o: $(hdrdir)/ruby/internal/token_paste.h
funcall.o: $(hdrdir)/ruby/internal/value.h
funcall.o: $(hdrdir)/ruby/internal/value_type.h
funcall.o: $(hdrdir)/ruby/internal/variable.h
funcall.o: $(hdrdir)/ruby/internal/warning_push.h
funcall.o: $(hdrdir)/ruby/internal/xmalloc.h
funcall.o: $(hdrdir)/ruby/assert.h
funcall.o: $(hdrdir)/ruby/backward.h
funcall.o: $(hdrdir)/ruby/backward/2/assume.h
funcall.o: $(hdrdir)/ruby/backward/2/attributes.h
funcall.o: $(hdrdir)/ruby/backward/2/bool.h
funcall.o: $(hdrdir)/ruby/backward/2/gcc_version_since.h
funcall.o: $(hdrdir)/ruby/backward/2/inttypes.h
funcall.o: $(hdrdir)/ruby/backward/2/limits.h
funcall.o: $(hdrdir)/ruby/backward/2/long_long.h
funcall.o: $(hdrdir)/ruby/backward/2/stdalign.h
funcall.o: $(hdrdir)/ruby/backward/2/stdarg.h
funcall.o: $(hdrdir)/ruby/defines.h
funcall.o: $(hdrdir)/ruby/intern.h
funcall.o: $(hdrdir)/ruby/missing.h
funcall.o: $(hdrdir)/ruby/ruby.h
funcall.o: $(hdrdir)/ruby/st.h
funcall.o: $(hdrdir)/ruby/subst.h
funcall.o: funcall.c
# AUTOGENERATED DEPENDENCIES END
