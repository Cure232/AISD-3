# CMakeList.txt: проект CMake для AISD-3; включите исходный код и определения,
# укажите здесь логику для конкретного проекта.
#
cmake_minimum_required (VERSION 3.8)

project ("AISD-3")

# Добавьте источник в исполняемый файл этого проекта.
add_executable (AISD-3 "AISD-3.cpp" "AISD-3.h")

# TODO: Добавьте тесты и целевые объекты, если это необходимо.
