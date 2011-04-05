# Copyright (C) 2007-2009 LuaDist.
# Created by Peter Kapec
# Redistribution and use of this file is allowed according to the terms of the MIT license.
# For details see the COPYRIGHT file distributed with LuaDist.
# Please note that the package source code is licensed under its own license.

PROJECT(etree NONE)
CMAKE_MINIMUM_REQUIRED(VERSION 2.6)
INCLUDE(dist.cmake)

# Install all files and documentation
INSTALL (FILES src/etree.lua DESTINATION ${INSTALL_LMOD})
INSTALL (FILES LICENSE README DESTINATION ${INSTALL_DATA})
INSTALL (FILES doc/style.css doc/manual.html doc/manual.txt DESTINATION ${INSTALL_DOC})
