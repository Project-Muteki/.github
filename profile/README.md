## Hi there 👋

This organization is about reverse engineering some newer (since 2008) Besta electronic dictionaries and related devices, as well as homebrew developments for such platforms.

Currently we provide a GCC-based toolchain and a newlib port with quite a bit of the ANSI C APIs implemented, as well as some POSIX APIs whenever they make sense to implement.

As to documentation of the system calls:

- Threading is fully covered.
- Filesystem has most of the essentials documented, but file-descriptor-related structures are still largely undocumented due to the sheer complexity of these.
- Some miscellaneous syscalls that may or may not related to libc porting (RTC, battery percentage, etc.) are documented.
- UI related syscalls are heavily work in progress.

Use the [discussion area](https://github.com/Project-Muteki/project-muteki.github.io/discussions) if you have any general questions regarding to the project.
