include_directories(${CURSES_INCLUDE_DIR})

add_executable(wano
    wano.cpp
    document.cpp
    textarea.cpp
    menu.cpp
)

target_link_libraries(wano curses_ui ${CURSES_LIBRARIES} ${PANEL_LIBRARY})
