cross-compilers
===============
Dockerfiles for cross compiling environments
--------------------------------------------

.. image:: https://circleci.com/gh/thewtex/cross-compilers/tree/master.svg?style=svg
  :target: https://circleci.com/gh/thewtex/cross-compilers/tree/master

.. |base-images| image:: https://badge.imagelayers.io/thewtex/cross-compiler-base:latest.svg
  :target: https://imagelayers.io/?images=thewtex/cross-compiler-base:latest

thewtex/cross-compiler-base
  |base-images| Base image for other toolchain images. From Debian Jessie with GCC,
  make, autotools, CMake, Ninja, Git, and Python.