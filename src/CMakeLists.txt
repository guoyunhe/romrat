qt5_add_resources(romrat_SRCS resources.qrc)
add_executable(romrat main.cpp ${romrat_SRCS})
target_link_libraries(romrat Qt5::Qml Qt5::Gui)

