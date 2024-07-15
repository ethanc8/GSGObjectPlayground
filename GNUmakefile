include $(GNUSTEP_MAKEFILES)/common.make

TOOL_NAME = GSGObjectPlayground
GSGObjectPlayground_OBJC_FILES = main.m

# gobject-introspection-1.0
GSGObjectPlayground_TOOL_LIBS += $(shell pkg-config --libs-only-l gobject-introspection-1.0)
GSGObjectPlayground_LDFLAGS += $(shell pkg-config --libs-only-L gobject-introspection-1.0) $(shell pkg-config --libs-only-other gobject-introspection-1.0)
GSGObjectPlayground_OBJCFLAGS += $(shell pkg-config --cflags gobject-introspection-1.0)

include $(GNUSTEP_MAKEFILES)/tool.make