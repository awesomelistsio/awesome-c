# Awesome C [![Awesome Lists](https://srv-cdn.himpfen.io/badges/awesome-lists/awesomelists-flat.svg)](https://github.com/awesomelistsio/awesome)

[![Ko-Fi](https://srv-cdn.himpfen.io/badges/kofi/kofi-flat.svg)](https://ko-fi.com/awesomelists) &nbsp; [![PayPal](https://srv-cdn.himpfen.io/badges/paypal/paypal-flat.svg)](https://www.paypal.com/donate/?hosted_button_id=3LLKRXJU44EJJ) &nbsp; [![Stripe](https://srv-cdn.himpfen.io/badges/stripe/stripe-flat.svg)](https://tinyurl.com/e8ymxdw3) &nbsp; [![X](https://srv-cdn.himpfen.io/badges/twitter/twitter-flat.svg)](https://x.com/ListsAwesome) &nbsp; [![Facebook](https://srv-cdn.himpfen.io/badges/facebook-pages/facebook-pages-flat.svg)](https://www.facebook.com/awesomelists)

> A curated list of C libraries, frameworks, compilers, tooling, utilities, learning resources, and ecosystem components — covering systems programming, embedded development, performance optimization, and cross-platform software engineering.

## Contents

- [Official Resources](#official-resources)
- [Compilers](#compilers)
- [Build Systems](#build-systems)
- [Standard Libraries & Utility Libraries](#standard-libraries--utility-libraries)
- [Memory Management](#memory-management)
- [Networking](#networking)
- [Multithreading & Concurrency](#multithreading--concurrency)
- [Graphics & Multimedia](#graphics--multimedia)
- [Game Development](#game-development)
- [Numerical & Scientific Computing](#numerical--scientific-computing)
- [Embedded & Systems Programming](#embedded--systems-programming)
- [Testing & Debugging](#testing--debugging)
- [Learning Resources](#learning-resources)
- [Related Awesome Lists](#related-awesome-lists)

## Official Resources

- [C Language Standard (ISO/IEC)](https://www.iso.org/standard/74528.html) – Official standard documentation.
- [C FAQ](http://c-faq.com/) – Classic C programming FAQ.
- [cppreference C Section](https://en.cppreference.com/w/c) – Comprehensive reference for C language and library features.

## Compilers

- [GCC](https://gcc.gnu.org/) – GNU Compiler Collection.
- [Clang/LLVM](https://clang.llvm.org/) – Modern, modular compiler suite.
- [TinyCC](https://github.com/TinyCC/tinycc) – Small, fast C compiler.
- [PCC](https://github.com/ggrubb/pcc-libs) – Portable C Compiler.
- [MSVC](https://learn.microsoft.com/cpp/) – Microsoft’s C/C++ compiler toolchain.

## Build Systems

- [CMake](https://github.com/Kitware/CMake) – Cross-platform build system.
- [Meson](https://github.com/mesonbuild/meson) – Fast, modern build system.
- [Ninja](https://github.com/ninja-build/ninja) – Small, low-level build tool.
- [Autotools](https://www.gnu.org/software/automake/) – Classic build system for Unix.

## Standard Libraries & Utility Libraries

- [musl libc](https://musl.libc.org/) – Lightweight standard library implementation.
- [glib](https://github.com/GNOME/glib) – Portable low-level core library.
- [libuv](https://github.com/libuv/libuv) – Cross-platform asynchronous I/O.
- [klib](https://github.com/attractivechaos/klib) – Small and efficient utility library.
- [sds](https://github.com/redis/sds) – Simple dynamic strings library used in Redis.
- [uthash](https://github.com/troydhanson/uthash) – Hash tables and data structures for C.
- [cJSON](https://github.com/DaveGamble/cJSON) – Lightweight JSON parser.
- [Jansson](https://github.com/akheron/jansson) – Full-featured JSON library.

## Memory Management

- [talloc](https://github.com/samba-team/talloc) – Hierarchical memory allocator.
- [jemalloc](https://github.com/jemalloc/jemalloc) – High-performance malloc implementation.
- [mimalloc](https://github.com/microsoft/mimalloc) – Optimized allocator by Microsoft.
- [rpmalloc](https://github.com/mjansson/rpmalloc) – Fast, lock-free memory allocator.

## Networking

- [libcurl](https://github.com/curl/curl) – HTTP and networking toolkit.
- [nghttp2](https://github.com/nghttp2/nghttp2) – HTTP/2 library.
- [libwebsockets](https://github.com/warmcat/libwebsockets) – WebSocket server and client.
- [nanomsg](https://github.com/nanomsg/nanomsg) – High-performance messaging library.
- [ZeroMQ](https://github.com/zeromq/libzmq) – Asynchronous messaging framework.

## Multithreading & Concurrency

- [pthread](https://pubs.opengroup.org/onlinepubs/9699919799/) – POSIX threads.
- [Concurrency Kit](https://github.com/concurrencykit/ck) – Lock-free concurrency primitives.
- [OpenMP](https://github.com/OpenMP) – Parallelization framework for C.

## Graphics & Multimedia

- [SDL2](https://github.com/libsdl-org/SDL) – Multimedia, graphics, and input library.
- [SFML (C Bindings)](https://github.com/SFML/csfml) – Multimedia library bindings for C.
- [Cairo](https://github.com/freedesktop/cairo) – 2D graphics rendering.
- [OpenGL](https://www.opengl.org/) – GPU hardware-accelerated rendering.
- [stb](https://github.com/nothings/stb) – Single-file image and graphics libraries.

## Game Development

- [Raylib (C Library)](https://github.com/raysan5/raylib) – Simple and modern game programming library.
- [SDL2](https://github.com/libsdl-org/SDL) – Foundation for many games.
- [cglm](https://github.com/recp/cglm) – Graphics math library for games and engines.

## Numerical & Scientific Computing

- [BLAS](https://www.netlib.org/blas/) – Basic linear algebra subprograms.
- [LAPACK](https://www.netlib.org/lapack/) – Linear algebra routines.
- [FFTW](https://github.com/FFTW/fftw3) – Fast Fourier Transform library.
- [GSL](https://www.gnu.org/software/gsl/) – GNU Scientific Library.

## Embedded & Systems Programming

- [FreeRTOS](https://github.com/FreeRTOS/FreeRTOS) – Real-time operating system kernel.
- [lwIP](https://github.com/lwip-tcpip/lwip) – Lightweight TCP/IP stack.
- [mbed TLS](https://github.com/Mbed-TLS/mbedtls) – Embedded-friendly TLS library.
- [Zephyr RTOS](https://github.com/zephyrproject-rtos/zephyr) – Real-time OS for embedded systems.

## Testing & Debugging

- [Unity Test Framework](https://github.com/ThrowTheSwitch/Unity) – Unit testing for C.
- [Check](https://github.com/libcheck/check) – Unit testing framework.
- [Valgrind](https://valgrind.org/) – Memory debugging and profiling.
- [GDB](https://www.gnu.org/software/gdb/) – The GNU debugger.
- [AddressSanitizer](https://clang.llvm.org/docs/AddressSanitizer.html) – Detect memory errors.

## Learning Resources

- **Books**
  - *The C Programming Language* by Kernighan & Ritchie.
  - *Expert C Programming: Deep C Secrets*.
  - *C Programming: A Modern Approach*.

- **Online**
  - [Learn C in Y Minutes](https://learnxinyminutes.com/docs/c/)
  - [TutorialsPoint C Programming](https://www.tutorialspoint.com/cprogramming/)
  - [Harvard CS50](https://cs50.harvard.edu/) – C programming foundations.

- **Reference**
  - [cppreference (C Section)](https://en.cppreference.com/w/c)
  - [ISO Standards](https://www.iso.org/standard/74528.html)

## Related Awesome Lists

- [Awesome Programming Languages](https://github.com/awesomelistsio/awesome-programming-languages)
- [Awesome Systems Programming](https://github.com/awesomelistsio/awesome-systems-programming)
- [Awesome Embedded](https://github.com/awesomelistsio/awesome-embedded)
- [Awesome Linux](https://github.com/awesomelistsio/awesome-linux)

## Contribute

Contributions are welcome!

## License

[![CC0](https://mirrors.creativecommons.org/presskit/buttons/88x31/svg/by-sa.svg)](http://creativecommons.org/licenses/by-sa/4.0/)
