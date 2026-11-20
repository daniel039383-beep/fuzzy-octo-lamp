ARCHS = arm64 arm64e
TARGET := iphone:clang:latest:15.0

include $(THEOS)/makefiles/common.mk

TWEAK_NAME = WhatsAppModMenu
WhatsAppModMenu_FILES = Tweak.xm
WhatsAppModMenu_CFLAGS = -fobjc-arc -Wno-deprecated-declarations
WhatsAppModMenu_FRAMEWORKS = UIKit Foundation CoreGraphics

include $(THEOS_MAKE_PATH)/tweak.mk
