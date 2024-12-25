ARCHS = arm64 arm64e
TARGET := iphone:clang:latest:14.0
INSTALL_TARGET_PROCESSES = Discord
FINALPACKAGE = 1

include ~/theos/makefiles/common.mk

TWEAK_NAME = SideloadFix

SideloadFix_FILES = $(wildcard Hooks/*.m) $(wildcard Hooks/*.xm)
SideloadFix_CFLAGS = -fobjc-arc

include ~/theos/makefiles/tweak.mk
