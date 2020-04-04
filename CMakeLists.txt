# ten CMakeLists jest tylko po to zeby ide ladnie podswietlalo
project("MIMUW-S4-SIK")

set(CMAKE_C_FLAGS "-g -Wall -Wextra")


# zadanko 4
add_executable(nk-client-udp zadanko4/nk-client-udp.c)
add_executable(nk-server-udp zadanko4/nk-server-udp.c)

# zadanko 5
add_executable(nk-client-tcp zadanko5/nk-client-tcp.c)
add_executable(nk-server-tcp zadanko5/nk-server-tcp.c)

# zadanko 6
add_executable(file-client-tcp zadanko6/file-client-tcp.c)
add_executable(file-server-tcp zadanko6/file-server-tcp.c)