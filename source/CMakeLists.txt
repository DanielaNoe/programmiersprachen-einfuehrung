# erzeugt Executable namens "helloworld" aus dem Source-File helloworld.cpp
add_executable(helloworld helloworld.cpp)

# erzeugt Executable namens "summe_1_bis_50" aus dem Source-File summe_1_bis_50.cpp
add_executable(summe_1_bis_50 summe_1_bis_50.cpp)

# fuegen Sie für das Erzeugen weiterer Executables Zeilen der Form 'add_executable(TARGET SOURCE_FILE_1 SOURCE_FILE_2 ...) '
# (CMake Dokumentation: https://cmake.org/cmake/help/latest/command/add_executable.html)