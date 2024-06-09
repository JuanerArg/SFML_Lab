cmake_minimum_required(VERSION 3.10)
project(Proyecto_Ajedrez_Cuantico_SFML)

set(CMAKE_CXX_STANDARD 17)

# Ruta a SFML
set(SFML_DIR "E:/Proyects/OOP Proyects/Proyecto_Ajedrez_Cuantico_SFML/SFML-2.6.1/lib/cmake/SFML")

find_package(SFML 2.5 COMPONENTS graphics audio REQUIRED)

add_executable(Proyecto_Ajedrez_Cuantico_SFML SFML_Lab/src/main.cpp)
target_link_libraries(Proyecto_Ajedrez_Cuantico_SFML sfml-graphics sfml-audio)