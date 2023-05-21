GNU jargs fork "as is".
Forked from https://sourceforge.net/projects/jargs/

Building:
  - check out javaforce
    git clone http://github.com/pquiring/javaforce
    cd javaforce
  - check out jargs
    cd lib
    git clone http://github.com/pquiring/jargs
  - build it
    cd jargs
    ant

Notes:
  - JavaForce is only used for build scripts to download dependancies and build deployment artifacts
