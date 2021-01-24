px4_add_module(
    MODULE modules__flip_control
    MAIN flip_control
    COMPILE_FLAGS -Os
    STACK_MAIN 1200
    SRCS
        flip_control.cpp
    DEPENDS
        platforms__common
    )
