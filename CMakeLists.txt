cmake_minimum_required(VERSION 2.8)
project(hello)

include_directories(${CMAKE_SOURCE_DIR}/include) #khai bao file h ở đâu

set(SOURCES_FILE #tạo 1 biến để chứa 2 file thực thi
	${CMAKE_SOURCE_DIR}/src/hellomake.c 
	${CMAKE_SOURCE_DIR}/src/main.c 
)
add_executable(hello ${SOURCES_FILE}) #lệnh để thực thi 2 file phía trên



