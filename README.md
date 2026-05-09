Similar to the other Codespace, this repository exists to provide a fully working C development environment inside GitHub Codespaces. My original setup had issues getting a clean toolchain working reliably across different devices, so I created a reproducible devcontainer that includes:

* GCC
* GDB
* LLVM/Clang/LLD/LLDB
* GNU Binutils
* GNU Make
* PExports
* Dos2unix
* Yasm
* NASM
* JWasm
* Ccache
* CMake
* Ninja
* Doxygen

The .devcontainer configuration ensures that Codespaces automatically builds a complete C toolchain without requiring system-level installs or sudo. This makes the environment portable, stable, and identical every time it’s opened.
