cmake_minimum_required(VERSION 2.6)


add_executable(mposplit mposplit.c)

install(TARGETS mposplit DESTINATION /usr/bin)
