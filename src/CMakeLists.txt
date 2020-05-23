cmake_minimum_required(VERSION 3.4.1)

# Compiler options
add_compile_options(-Wall)

# Submodule library
add_library(zip
            STATIC

            # Source
            zip.c)

# Linking
target_link_libraries(zip)
