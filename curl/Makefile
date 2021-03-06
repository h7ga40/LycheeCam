﻿# This file was automagically generated by mbed.org. For more information, 
# see http://mbed.org/handbook/Exporting-to-GCC-ARM-Embedded

###############################################################################
# Boiler-plate

# cross-platform directory manipulation
ifeq ($(shell echo $$OS),$$OS)
    MAKEDIR = if not exist "$(1)" mkdir "$(1)"
    RM = rmdir /S /Q "$(1)"
else
    MAKEDIR = '$(SHELL)' -c "mkdir -p \"$(1)\""
    RM = '$(SHELL)' -c "rm -rf \"$(1)\""
endif

OBJDIR := Debug
# Move to the build directory
ifeq (,$(filter $(OBJDIR),$(notdir $(CURDIR))))
.SUFFIXES:
mkfile_path := $(abspath $(lastword $(MAKEFILE_LIST)))
MAKETARGET = '$(MAKE)' --no-print-directory -C $(OBJDIR) -f '$(mkfile_path)' \
		'SRCDIR=$(CURDIR)' $(MAKECMDGOALS)
.PHONY: $(OBJDIR) clean
all:
	+@$(call MAKEDIR,$(OBJDIR))
	+@$(MAKETARGET)
$(OBJDIR): all
Makefile : ;
% :: $(OBJDIR) ; :
clean :
	$(call RM,$(OBJDIR))

else

# trick rules into thinking we are in the root, when we are in the bulid dir
VPATH = ../../curl

# Boiler-plate
###############################################################################
# Project settings

PROJECT := curl


# Project settings
###############################################################################
# Objects and Paths

OBJECTS += lib/amigaos.o
OBJECTS += lib/asyn-ares.o
OBJECTS += lib/asyn-thread.o
OBJECTS += lib/base64.o
OBJECTS += lib/conncache.o
OBJECTS += lib/connect.o
OBJECTS += lib/content_encoding.o
OBJECTS += lib/cookie.o
OBJECTS += lib/curl_addrinfo.o
OBJECTS += lib/curl_des.o
OBJECTS += lib/curl_endian.o
OBJECTS += lib/curl_fnmatch.o
OBJECTS += lib/curl_gethostname.o
OBJECTS += lib/curl_gssapi.o
OBJECTS += lib/curl_memrchr.o
OBJECTS += lib/curl_multibyte.o
OBJECTS += lib/curl_ntlm_core.o
OBJECTS += lib/curl_ntlm_wb.o
OBJECTS += lib/curl_rtmp.o
OBJECTS += lib/curl_sasl.o
OBJECTS += lib/curl_sspi.o
OBJECTS += lib/curl_threads.o
OBJECTS += lib/dict.o
OBJECTS += lib/dotdot.o
OBJECTS += lib/easy.o
OBJECTS += lib/escape.o
OBJECTS += lib/file.o
OBJECTS += lib/fileinfo.o
OBJECTS += lib/formdata.o
OBJECTS += lib/ftp.o
OBJECTS += lib/ftplistparser.o
OBJECTS += lib/getenv.o
OBJECTS += lib/getinfo.o
OBJECTS += lib/gopher.o
OBJECTS += lib/hash.o
OBJECTS += lib/hmac.o
OBJECTS += lib/hostasyn.o
OBJECTS += lib/hostcheck.o
OBJECTS += lib/hostip.o
OBJECTS += lib/hostip4.o
OBJECTS += lib/hostip6.o
OBJECTS += lib/hostsyn.o
OBJECTS += lib/http.o
OBJECTS += lib/http2.o
OBJECTS += lib/http_chunks.o
OBJECTS += lib/http_digest.o
OBJECTS += lib/http_negotiate.o
OBJECTS += lib/http_ntlm.o
OBJECTS += lib/http_proxy.o
OBJECTS += lib/idn_win32.o
OBJECTS += lib/if2ip.o
OBJECTS += lib/imap.o
OBJECTS += lib/inet_ntop.o
OBJECTS += lib/inet_pton.o
OBJECTS += lib/krb5.o
OBJECTS += lib/ldap.o
OBJECTS += lib/llist.o
OBJECTS += lib/md4.o
OBJECTS += lib/md5.o
OBJECTS += lib/memdebug.o
OBJECTS += lib/mime.o
OBJECTS += lib/mprintf.o
OBJECTS += lib/multi.o
OBJECTS += lib/netrc.o
OBJECTS += lib/non-ascii.o
OBJECTS += lib/nonblock.o
OBJECTS += lib/nwlib.o
OBJECTS += lib/nwos.o
OBJECTS += lib/openldap.o
OBJECTS += lib/parsedate.o
OBJECTS += lib/pingpong.o
OBJECTS += lib/pipeline.o
OBJECTS += lib/pop3.o
OBJECTS += lib/progress.o
OBJECTS += lib/rand.o
OBJECTS += lib/rtsp.o
OBJECTS += lib/security.o
OBJECTS += lib/select.o
OBJECTS += lib/sendf.o
OBJECTS += lib/setopt.o
OBJECTS += lib/sha256.o
OBJECTS += lib/share.o
OBJECTS += lib/slist.o
OBJECTS += lib/smb.o
OBJECTS += lib/smtp.o
OBJECTS += lib/socks.o
OBJECTS += lib/socks_gssapi.o
OBJECTS += lib/socks_sspi.o
OBJECTS += lib/speedcheck.o
OBJECTS += lib/splay.o
OBJECTS += lib/ssh.o
OBJECTS += lib/strcase.o
OBJECTS += lib/strdup.o
OBJECTS += lib/strerror.o
OBJECTS += lib/strtok.o
OBJECTS += lib/strtoofft.o
OBJECTS += lib/telnet.o
OBJECTS += lib/tftp.o
OBJECTS += lib/timeval.o
OBJECTS += lib/transfer.o
OBJECTS += lib/url.o
OBJECTS += lib/version.o
OBJECTS += lib/warnless.o
OBJECTS += lib/wildcard.o
OBJECTS += lib/x509asn1.o
OBJECTS += lib/vauth/cleartext.o
OBJECTS += lib/vauth/cram.o
OBJECTS += lib/vauth/digest.o
OBJECTS += lib/vauth/ntlm.o
OBJECTS += lib/vauth/oauth2.o
OBJECTS += lib/vauth/vauth.o
OBJECTS += lib/vtls/axtls.o
OBJECTS += lib/vtls/cyassl.o
OBJECTS += lib/vtls/darwinssl.o
OBJECTS += lib/vtls/gskit.o
OBJECTS += lib/vtls/gtls.o
OBJECTS += lib/vtls/mbedtls.o
OBJECTS += lib/vtls/nss.o
OBJECTS += lib/vtls/openssl.o
OBJECTS += lib/vtls/polarssl.o
OBJECTS += lib/vtls/polarssl_threadlock.o
OBJECTS += lib/vtls/schannel.o
OBJECTS += lib/vtls/vtls.o
OBJECTS += src/slist_wc.o
OBJECTS += src/tool_binmode.o
OBJECTS += src/tool_bname.o
OBJECTS += src/tool_cb_dbg.o
OBJECTS += src/tool_cb_hdr.o
OBJECTS += src/tool_cb_prg.o
OBJECTS += src/tool_cb_rea.o
OBJECTS += src/tool_cb_see.o
OBJECTS += src/tool_cb_wrt.o
OBJECTS += src/tool_cfgable.o
OBJECTS += src/tool_convert.o
OBJECTS += src/tool_dirhie.o
OBJECTS += src/tool_doswin.o
OBJECTS += src/tool_easysrc.o
OBJECTS += src/tool_formparse.o
OBJECTS += src/tool_getparam.o
OBJECTS += src/tool_getpass.o
OBJECTS += src/tool_help.o
OBJECTS += src/tool_helpers.o
OBJECTS += src/tool_homedir.o
OBJECTS += src/tool_hugehelp.o
OBJECTS += src/tool_libinfo.o
OBJECTS += src/tool_main.o
OBJECTS += src/tool_metalink.o
OBJECTS += src/tool_msgs.o
OBJECTS += src/tool_operate.o
OBJECTS += src/tool_operhlp.o
OBJECTS += src/tool_panykey.o
OBJECTS += src/tool_paramhlp.o
OBJECTS += src/tool_parsecfg.o
OBJECTS += src/tool_setopt.o
OBJECTS += src/tool_sleep.o
OBJECTS += src/tool_strdup.o
OBJECTS += src/tool_urlglob.o
OBJECTS += src/tool_util.o
OBJECTS += src/tool_vms.o
OBJECTS += src/tool_writeout.o
OBJECTS += src/tool_xattr.o

INCLUDE_PATHS += -I../../musl/include
INCLUDE_PATHS += -I../../zlib/src
INCLUDE_PATHS += -I../../mbed-os/cmsis/TARGET_CORTEX_A
INCLUDE_PATHS += -I../../mbed-os/cmsis
INCLUDE_PATHS += -I../../mbed-os/drivers
INCLUDE_PATHS += -I../../mbed-os/events/equeue
INCLUDE_PATHS += -I../../mbed-os/events
INCLUDE_PATHS += -I../../mbed-os/features/device_key/source
INCLUDE_PATHS += -I../../mbed-os/features/storage/blockdevice
INCLUDE_PATHS += -I../../mbed-os/features/storage/filesystem/fat/ChaN
INCLUDE_PATHS += -I../../mbed-os/features/storage/filesystem/fat
INCLUDE_PATHS += -I../../mbed-os/features/storage/filesystem/littlefs/littlefs
INCLUDE_PATHS += -I../../mbed-os/features/storage/filesystem/littlefs
INCLUDE_PATHS += -I../../mbed-os/features/storage
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/greentea-client
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/mbed-client-randlib/mbed-client-randlib/platform
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/mbed-client-randlib/mbed-client-randlib
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/mbed-coap
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/mbed-coap/source/include
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/mbed-trace
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/nanostack-libservice/mbed-client-libservice/platform
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/nanostack-libservice/mbed-client-libservice
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/nanostack-libservice
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/unity
INCLUDE_PATHS += -I../../mbed-os/features/frameworks/utest
INCLUDE_PATHS += -I../../mbed-os/features/mbedtls/inc
INCLUDE_PATHS += -I../../mbed-os/features/mbedtls/platform/inc
INCLUDE_PATHS += -I../../mbed-os/features/mbedtls
INCLUDE_PATHS += -I../../mbed-os/features/netsocket
INCLUDE_PATHS += -I../../mbed-os/features/storage/nvstore/source
INCLUDE_PATHS += -I../../mbed-os/features
INCLUDE_PATHS += -I../../mbed-os/hal/storage_abstraction
INCLUDE_PATHS += -I../../mbed-os/hal
INCLUDE_PATHS += -I../../mbed-os/platform
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX/rtx4
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX/rtx5/Include
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX/rtx5/RTX/Config
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX/rtx5/RTX/Include
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX/rtx5/RTX/Source
INCLUDE_PATHS += -I../../mbed-os/rtos/TARGET_CORTEX
INCLUDE_PATHS += -I../../mbed-os/rtos
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/TARGET_GR_LYCHEE/device/inc/iobitmasks
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/TARGET_GR_LYCHEE/device/inc/iodefines
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/TARGET_GR_LYCHEE/device/inc
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/TARGET_GR_LYCHEE/device
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/TARGET_GR_LYCHEE
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX/common
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS/TARGET_RZ_A1XX
INCLUDE_PATHS += -I../../mbed-os/targets/TARGET_RENESAS
INCLUDE_PATHS += -I../../mbed-os
INCLUDE_PATHS += -I../../curl/include
INCLUDE_PATHS += -I../../curl/lib


# Objects and Paths
###############################################################################
# Tools and Flags

AS      = arm-none-eabi-gcc
CC      = arm-none-eabi-gcc
CPP     = arm-none-eabi-g++
AR      = arm-none-eabi-ar
RANLIB  = arm-none-eabi-ranlib


C_FLAGS += -std=gnu11
C_FLAGS += -mcpu=cortex-a9
C_FLAGS += -march=armv7-a
C_FLAGS += -marm
C_FLAGS += -mthumb-interwork
C_FLAGS += -mlittle-endian
C_FLAGS += -mfloat-abi=hard
C_FLAGS += -mfpu=neon-fp16
C_FLAGS += -Og
C_FLAGS += -fmessage-length=0
C_FLAGS += -fsigned-char
C_FLAGS += -ffunction-sections
C_FLAGS += -fdata-sections
C_FLAGS += -Wall
C_FLAGS += -Wextra
C_FLAGS += -Wno-unused-parameter
C_FLAGS += -Wno-missing-field-initializers
C_FLAGS += -Wnull-dereference
C_FLAGS += -g3
C_FLAGS += -Wstack-usage=256

C_FLAGS += --include ../../mbed-os/mbed_config.h
C_FLAGS += -DHAVE_CONFIG_H
C_FLAGS += -DBUILDING_LIBCURL
C_FLAGS += -D__NEWLIB__
C_FLAGS += -DARM_MATH_CA9
C_FLAGS += -D__FPU_PRESENT=1
C_FLAGS += -D__MBED__=1
C_FLAGS += -DDEVICE_I2CSLAVE=1
C_FLAGS += -DTARGET_LIKE_MBED
C_FLAGS += -DDEVICE_PORTINOUT=1
C_FLAGS += -DDEVICE_PORTIN=1
C_FLAGS += -DTOOLCHAIN_object
C_FLAGS += -DDEVICE_SERIAL_ASYNCH=1
C_FLAGS += -DDEVICE_RTC
C_FLAGS += -D__CMSIS_RTOS
C_FLAGS += -D__EVAL
C_FLAGS += -DTOOLCHAIN_GCC
C_FLAGS += -DTARGET_CORTEX_A
C_FLAGS += -DDEVICE_CAN=1
C_FLAGS += -DMBED_BUILD_TIMESTAMP=1487815611.57
C_FLAGS += -DDEVICE_I2C_ASYNCH=1
C_FLAGS += -DTARGET_UVISOR_UNSUPPORTED
C_FLAGS += -D__MBED_CMSIS_RTOS_CA9
C_FLAGS += -DTARGET_LIKE_CORTEX_A9
C_FLAGS += -DDEVICE_SERIAL=1
C_FLAGS += -DTARGET_MBRZA1LU
C_FLAGS += -DDEVICE_INTERRUPTIN=1
C_FLAGS += -DDEVICE_I2C=1
C_FLAGS += -DDEVICE_PORTOUT=1
C_FLAGS += -DDEVICE_STDIO_MESSAGES=1
C_FLAGS += -DDEVICE_SPI_ASYNCH=1
C_FLAGS += -DTARGET_RENESAS
C_FLAGS += -DTARGET_RELEASE
C_FLAGS += -DDEVICE_SERIAL_FC=1
C_FLAGS += -DTARGET_GR_LYCHEE
C_FLAGS += -DTARGET_A9
C_FLAGS += -D__CORTEX_A9
C_FLAGS += -DTARGET_RZ_A1XX
C_FLAGS += -DTARGET_RZA1UL
C_FLAGS += -DTARGET_FF_ARDUINO
C_FLAGS += -DTOOLCHAIN_GCC_ARM
C_FLAGS += -DDEVICE_SPI=1
C_FLAGS += -DDEVICE_SPISLAVE=1
C_FLAGS += -DDEVICE_ANALOGIN=1
C_FLAGS += -DDEVICE_PWMOUT=1
C_FLAGS += -DDEVICE_TRNG=1
C_FLAGS += -D__OPENCV_BUILD
C_FLAGS += -D__ARM_NEON__


CXX_FLAGS += -std=gnu++11
CXX_FLAGS += -mcpu=cortex-a9
CXX_FLAGS += -march=armv7-a
CXX_FLAGS += -marm
CXX_FLAGS += -mthumb-interwork
CXX_FLAGS += -mlittle-endian
CXX_FLAGS += -mfloat-abi=hard
CXX_FLAGS += -mfpu=neon-fp16
CXX_FLAGS += -Og
CXX_FLAGS += -fmessage-length=0
CXX_FLAGS += -fsigned-char
CXX_FLAGS += -ffunction-sections
CXX_FLAGS += -fdata-sections
CXX_FLAGS += -Wall
CXX_FLAGS += -Wextra
CXX_FLAGS += -Wno-unused-parameter
CXX_FLAGS += -Wno-missing-field-initializers
CXX_FLAGS += -Wnull-dereference
CXX_FLAGS += -g3
CXX_FLAGS += -Wstack-usage=256

CXX_FLAGS += --include ../../mbed-os/mbed_config.h


ASM_FLAGS += -x
ASM_FLAGS += assembler-with-cpp
ASM_FLAGS += -mcpu=cortex-a9
ASM_FLAGS += -march=armv7-a
ASM_FLAGS += -marm
ASM_FLAGS += -mthumb-interwork
ASM_FLAGS += -mlittle-endian
ASM_FLAGS += -mfloat-abi=hard
ASM_FLAGS += -mfpu=neon-fp16
ASM_FLAGS += -Og
ASM_FLAGS += -fmessage-length=0
ASM_FLAGS += -fsigned-char
ASM_FLAGS += -ffunction-sections
ASM_FLAGS += -fdata-sections
ASM_FLAGS += -Wall
ASM_FLAGS += -Wextra
ASM_FLAGS += -Wno-unused-parameter
ASM_FLAGS += -Wno-missing-field-initializers
ASM_FLAGS += -Wnull-dereference
ASM_FLAGS += -g3
ASM_FLAGS += -Wstack-usage=256


# Tools and Flags
###############################################################################
# Rules

.PHONY: all lst size


all: lib$(PROJECT).a


.s.o:
	+@$(call MAKEDIR,$(dir $@))
	+@echo "Assemble: $(notdir $<)"
	@$(AS) -c $(ASM_FLAGS) -o $@ $<

.S.o:
	+@$(call MAKEDIR,$(dir $@))
	+@echo "Assemble: $(notdir $<)"
	@$(AS) -c $(ASM_FLAGS) -o $@ $<

.c.o:
	+@$(call MAKEDIR,$(dir $@))
	+@echo "Compile: $(notdir $<)"
	@$(CC) $(C_FLAGS) $(INCLUDE_PATHS) -MMD -MP -MF"$(@:%.o=%.d)" -MT"$(@)" -c -o "$@" "$<"

.cpp.o:
	+@$(call MAKEDIR,$(dir $@))
	+@echo "Compile: $(notdir $<)"
	@$(CPP) $(CXX_FLAGS) $(INCLUDE_PATHS) -MMD -MP -MF"$(@:%.o=%.d)" -MT"$(@)" -c -o "$@" "$<"

lib$(PROJECT).a: $(OBJECTS)
	rm -f lib$(PROJECT).a
	$(AR) -rcs lib$(PROJECT).a $(OBJECTS)
	$(RANLIB) lib$(PROJECT).a

# Rules
###############################################################################
# Dependencies

DEPS = $(OBJECTS:.o=.d) $(SYS_OBJECTS:.o=.d)
-include $(DEPS)
endif

# Dependencies
###############################################################################
