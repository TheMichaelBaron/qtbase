# Generated from evdevkeyboard.pro.

#####################################################################
## QEvdevKeyboardPlugin Plugin:
#####################################################################

qt_internal_add_plugin(QEvdevKeyboardPlugin
    OUTPUT_NAME qevdevkeyboardplugin
    TYPE generic
    DEFAULT_IF FALSE
    SOURCES
        main.cpp
    PUBLIC_LIBRARIES
        Qt::Core
        Qt::CorePrivate
        Qt::Gui
        Qt::GuiPrivate
        Qt::InputSupportPrivate
)

#### Keys ignored in scope 1:.:.:evdevkeyboard.pro:<TRUE>:
# OTHER_FILES = "evdevkeyboard.json"
# PLUGIN_EXTENDS = "-"
