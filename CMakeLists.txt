# SPDX-License-Identifier: GPL-2.0-only
# Copyright © Interactive Echoes. All rights reserved.
# Author: mozahzah

cmake_minimum_required(VERSION 3.20)

add_library(IEResources INTERFACE)
target_compile_definitions(IEResources INTERFACE IEResources_Folder_Path="${CMAKE_CURRENT_SOURCE_DIR}")