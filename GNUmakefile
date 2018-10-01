include $(GNUSTEP_MAKEFILES)/common.make

HOPPER_SDK_PATH=../SDK

COMMON_OBJC_FLAGS = -I$(HOPPER_SDK_PATH)/include -DLINUX -Wno-format -fblocks -fobjc-nonfragile-abi -fobjc-arc

BUNDLE_NAME = XtensaCPU

XtensaCPU_OBJC_FILES = XtensaCPU.m XtensaCtx.m
#XtensaCPU_C_FILES = \
	Capstone/arch/M68K/M68KModule.c \
	Capstone/arch/M68K/M68KDisassembler.c \
	Capstone/arch/M68K/M68KInstPrinter.c \
	Capstone/MCRegisterInfo.c \
	Capstone/MCInst.c \
	Capstone/MCInstrDesc.c \
	Capstone/cs.c \
	Capstone/SStream.c \
	Capstone/utils.c

XtensaCPU_CFLAGS = 
XtensaCPU_OBJCFLAGS = $(COMMON_OBJC_FLAGS)

include $(GNUSTEP_MAKEFILES)/bundle.make
