cmake_minimum_required(VERSION 3.10)

set(PROJECT_NAME FES_FW)
project(${PROJECT_NAME} C CXX ASM)

# Set compiler flags 
set(CMAKE_C_COMPILER arm-none-eabi-gcc)
set(CMAKE_CXX_COMPILER arm-none-eabi-g++)
set(CMAKE_ASM_COMPILER arm-none-eabi-gcc)

# set STM32 flag 
set(MCU_FAMILY STM32F7xx)
