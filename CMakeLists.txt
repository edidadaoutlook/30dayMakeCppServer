cmake_minimum_required(VERSION 3.25)
project(30dayMakeCppServer)

set(CMAKE_CXX_STANDARD 14)

include_directories(code/day02)
include_directories(code/day03)
include_directories(code/day04)
include_directories(code/day05)
include_directories(code/day06/src)
include_directories(code/day07/src)
include_directories(code/day08/src)
include_directories(code/day09/src)
include_directories(code/day10/src)
include_directories(code/day11/src)
include_directories(code/day12/src)
include_directories(code/day13/src/include)
include_directories(code/day14/src/include)
include_directories(code/day15/src/include)
include_directories(code/day16/src/include)

add_executable(30dayMakeCppServer_day01_client
        code/day01/client.cpp
)

add_executable(30dayMakeCppServer_day01_server
        code/day01/server.cpp
)

add_executable(30dayMakeCppServer_day02_client
        code/day02/client.cpp
        code/day02/util.cpp
)

add_executable(30dayMakeCppServer_day02_server
        code/day02/server.cpp
        code/day02/util.cpp
)

add_executable(30dayMakeCppServer_day03_client
        code/day03/client.cpp
        code/day03/util.cpp
)

add_executable(30dayMakeCppServer_day03_server
        code/day03/server.cpp
        code/day03/util.cpp
)

add_executable(30dayMakeCppServer_day04_client
        code/day04/client.cpp
        code/day04/util.cpp
)

add_executable(30dayMakeCppServer_day04_server
        code/day04/server.cpp
        code/day04/Epoll.cpp
        code/day04/InetAddress.cpp
        code/day04/util.cpp
)

add_executable(30dayMakeCppServer_day05_client
        code/day05/client.cpp
        code/day05/util.cpp
)

add_executable(30dayMakeCppServer_day05_server
        code/day05/Channel.cpp
        code/day05/Epoll.cpp
        code/day05/InetAddress.cpp
        code/day05/server.cpp
        code/day05/Socket.cpp
        code/day05/util.cpp
)

add_executable(30dayMakeCppServer_day06_client
        code/day06/client.cpp
        code/day06/util.cpp
)

add_executable(30dayMakeCppServer_day06_server
        code/day06/src/Channel.cpp
        code/day06/src/Epoll.cpp
        code/day06/src/EventLoop.cpp
        code/day06/src/InetAddress.cpp
        code/day06/src/Server.cpp
        code/day06/src/Socket.cpp
        code/day06/src/util.cpp
        code/day06/client.cpp
        code/day06/server.cpp
)

add_executable(30dayMakeCppServer_day07_client
        code/day07/client.cpp
        code/day07/util.cpp
)

add_executable(30dayMakeCppServer_day07_server
        code/day07/src/Acceptor.cpp
        code/day07/src/Channel.cpp
        code/day07/src/Epoll.cpp
        code/day07/src/EventLoop.cpp
        code/day07/src/InetAddress.cpp
        code/day07/src/Server.cpp
        code/day07/src/Socket.cpp
        code/day07/src/util.cpp
        code/day07/client.cpp
        code/day07/server.cpp
)

add_executable(30dayMakeCppServer_day08_client
        code/day08/client.cpp
        code/day08/util.cpp
)

add_executable(30dayMakeCppServer_day08_server
        code/day08/src/Acceptor.cpp
        code/day08/src/Channel.cpp
        code/day08/src/Connection.cpp
        code/day08/src/Epoll.cpp
        code/day08/src/EventLoop.cpp
        code/day08/src/InetAddress.cpp
        code/day08/src/Server.cpp
        code/day08/src/Socket.cpp
        code/day08/src/util.cpp
        code/day08/client.cpp
        code/day08/server.cpp
)

add_executable(30dayMakeCppServer_day09_client
        code/day09/client.cpp
        code/day09/util.cpp
)

add_executable(30dayMakeCppServer_day09_server
        code/day09/src/Acceptor.cpp
        code/day09/src/Buffer.cpp
        code/day09/src/Channel.cpp
        code/day09/src/Connection.cpp
        code/day09/src/Epoll.cpp
        code/day09/src/EventLoop.cpp
        code/day09/src/InetAddress.cpp
        code/day09/src/Server.cpp
        code/day09/src/Socket.cpp
        code/day09/src/util.cpp
        code/day09/client.cpp
        code/day09/server.cpp
)

add_executable(30dayMakeCppServer_day10_client
        code/day10/client.cpp
        code/day10/util.cpp
        code/day10/src/Buffer.cpp code/day10/src/Socket.cpp code/day10/src/InetAddress.cpp
)

add_executable(30dayMakeCppServer_day10_server
        code/day10/server.cpp
        code/day10/util.cpp
        code/day10/src/Acceptor.cpp
        code/day10/src/Buffer.cpp
        code/day10/src/Channel.cpp
        code/day10/src/Connection.cpp
        code/day10/src/Epoll.cpp
        code/day10/src/EventLoop.cpp
        code/day10/src/InetAddress.cpp
        code/day10/src/Server.cpp
        code/day10/src/Socket.cpp
        code/day10/src/ThreadPool.cpp
)

add_executable(30dayMakeCppServer_day11_client
        code/day11/client.cpp
        code/src/util.cpp code/src/Buffer.cpp code/src/Socket.cpp code/src/InetAddress.cpp
        code/src/util.cpp code/src/Buffer.cpp code/src/Socket.cpp code/src/InetAddress.cpp
)

add_executable(30dayMakeCppServer_day11_server
        code/day11/server.cpp
        code/day11/src/Acceptor.cpp
        code/day11/src/Buffer.cpp
        code/day11/src/Channel.cpp
        code/day11/src/Connection.cpp
        code/day11/src/Epoll.cpp
        code/day11/src/EventLoop.cpp
        code/day11/src/InetAddress.cpp
        code/day11/src/Server.cpp
        code/day11/src/Socket.cpp
        code/day11/src/ThreadPool.cpp
        code/day11/src/util.cpp
)

add_executable(30dayMakeCppServer_day12_client
        code/day12/client.cpp
        code/day12/src/util.cpp
        code/day12/src/Socket.cpp
        code/day12/src/Buffer.cpp
)

add_executable(30dayMakeCppServer_day12_server
        code/day12/src/Acceptor.cpp
        code/day12/src/Buffer.cpp
        code/day12/src/Channel.cpp
        code/day12/src/Connection.cpp
        code/day12/src/Epoll.cpp
        code/day12/src/EventLoop.cpp
        code/day12/src/Server.cpp
        code/day12/src/Socket.cpp
        code/day12/src/ThreadPool.cpp
        code/day12/src/util.cpp
        code/day12/server.cpp
)

add_subdirectory(code/day13)

add_subdirectory(code/day14)

add_subdirectory(code/day15)

add_subdirectory(code/day16)
