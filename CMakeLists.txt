cmake_minimum_required(VERSION 2.8.4)
project(cimg)

install(DIRECTORY ./ DESTINATION include/
                FILES_MATCHING PATTERN "*.h")
