cmake_minimum_required(VERSION 3.26)
project(LinkedLists)

set(CMAKE_CXX_STANDARD 17)

add_executable(LinkedLists main.cpp
        LinkedListBase.cpp
        LinkedListBase.h
        SinglyLinkedList.cpp
        SinglyLinkedList.h
        DoublyLinkedList.cpp
        DoublyLinkedList.h)
