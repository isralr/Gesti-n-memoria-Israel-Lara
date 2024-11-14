cmake_minimum_required(VERSION 3.29)
project(Gesti_n_memoria_Israel_Lara C)

set(CMAKE_C_STANDARD 11)

add_executable(Gesti_n_memoria_Israel_Lara
    main.c
        sys/mman.h
        sys/wait.h)
