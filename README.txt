#!/bin/bash
#### Simple example for autogen


aclocal
autoconf
automake --add-missing --foreign
./configure
make
