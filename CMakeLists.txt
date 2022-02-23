cmake_minimum_required(VERSION 3.22)

project(yomamma LANGUAGES C)

include(GNUInstallDirs)

install(FILES file.txt DESTINATION ${CMAKE_INSTALL_LIBDIR})
install(FILES file.txt DESTINATION ${CMAKE_INSTALL_BINDIR})
install(FILES file.txt DESTINATION ${CMAKE_INSTALL_SYSCONFDIR})
install(FILES file.txt DESTINATION ${CMAKE_INSTALL_DATAROOTDIR})