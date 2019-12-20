# Dockerfile for steschu/alpine-opengl

This Docker image is intended to be used for CI builds of OpenGL C/C++ based projects that use CMake for their project description.

The image also includes the GNU gold linker, ninja, cppcheck as well as wget and ccache.

Due to its intended use in CI, the image is kept as small as possible while still providing all meaningful tools for building C/C++ projects.
