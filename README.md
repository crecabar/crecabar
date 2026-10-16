# Cristian Recabarren

**Software Engineer · Software Architect · Founder of [Flō Finanstic](https://flofinanstic.com/) · Creator of [MyOS](https://github.com/crecabar/myos)**

I build software across two complementary areas: **application and product engineering** and **low-level systems programming**.

My professional work focuses on backend systems, domain modelling, maintainable architectures and software that solves real problems. Outside that work, I study operating systems by building one from the ground up.

Based in Santiago, Chile.

[❤️ Sponsor my open-source work](https://github.com/sponsors/crecabar)

## What I'm building

### [MyOS](https://github.com/crecabar/myos) — an educational Unix-like operating system

MyOS is an open-source, x86-64 operating system written primarily in C. Its purpose is to understand and implement the mechanisms that make an operating system work, with explicit contracts, incremental development and reproducible tests.

The kernel has progressed through UEFI boot, virtual memory, privilege separation, preemptive scheduling, ELF userspace execution, system calls, process lifecycle management and a virtual filesystem. **MyOS 0.3.0 now boots into an interactive userspace shell, `myos $`,** with an initial C runtime and Unix-style utilities. The next phase expands shell capabilities, including pipes, redirection and job control.

MyOS uses **LLVM/Clang, LLD, Limine, QEMU, GDB and GNU Make**, and has also booted on physical x86-64 hardware.

**Long-term direction:** a practical Unix-style userland, native filesystem and device support, a graphical environment capable of running `startx` / `xclock`, and eventually self-hosting.

> I do not want to build the next Linux. I want to understand how one is built.

**Explore the project:** [Kernel](https://github.com/crecabar/myos) · [Roadmap and issues](https://github.com/crecabar/myos/issues) · [libc](https://github.com/crecabar/myos-libc) · [Userland](https://github.com/crecabar/myos-userland) · [MFS filesystem](https://github.com/crecabar/myos-mfs) · [Vim port](https://github.com/crecabar/myos-vim)

The companion repositories represent planned or emerging components; they are not all fully implemented.

### [Flō Finanstic](https://flofinanstic.com/) — personal financial planning

I founded Flō to help people answer a question that matters *before* they spend:

> Knowing how much money you have is not the same as knowing how much you can spend.

Flō turns available money into a plan for priorities, commitments and goals. The product is evolving through a private beta.

My engineering work on Flō includes financial domain modelling, application architecture, automated testing and incremental separation of business rules from framework and infrastructure concerns.

**Stack:** PHP · Laravel · Vue · TypeScript · MySQL · Redis · Docker · AWS

Flō's main application is developed privately under the [Flō Finanstic organization](https://github.com/flofinanstic). The public GitHub profile therefore showcases more of my systems-programming work than of Flō's production code.

## Support my open-source work ❤️

I develop MyOS and other open-source projects to explore systems programming, share knowledge, and build useful educational tools.

If you find my work interesting or useful, you can help support its continued development.

**[❤️ Become a GitHub Sponsor](https://github.com/sponsors/crecabar)**

Every contribution helps sustain independent open-source development, testing and documentation. The code remains open to everyone, whether or not they sponsor my work. Thank you!

## Selected public projects

| Project | What it represents |
| --- | --- |
| **[MyOS](https://github.com/crecabar/myos)** | Operating-system engineering: kernel, userspace, memory, processes, filesystems and hardware interfaces. |
| **[deitel-book](https://github.com/crecabar/deitel-book)** | Systematic C programming exercises with an interactive launcher and automatic exercise discovery. |
| **[utem_thesis_template](https://github.com/crecabar/utem_thesis_template)** | A LaTeX engineering-thesis template, shared as a reusable resource for other students. |
| **[myos-mfs](https://github.com/crecabar/myos-mfs)** | The separately organized native, journaled filesystem project for MyOS; still at an early stage. |

## Engineering interests and tools

**Backend & application architecture:** PHP, Laravel, API design, domain modelling, clean/hexagonal architecture, relational databases, automated testing and static analysis.

**Systems & languages:** C, C++, x86-64, Unix-like operating systems, ELF, compilers and toolchains, memory management, processes and filesystems.

**Infrastructure & workflow:** Linux, macOS, Git, GitHub, Docker, QEMU, GDB, LLVM/Clang, GNU Make and AWS.

I value readable code, explicit invariants, testable boundaries and small changes that can be independently verified. Existing systems are valuable references, but good engineering requires understanding trade-offs instead of copying designs uncritically.

## Education and continued learning

I am a **Computer Engineer** with graduate studies in **Technology Management and Entrepreneurship**. My projects range from product and financial software to experiments in embedded programming, electronics, tools and operating systems.

I also completed **Babson Build 2023**.

## Contact

- **Email:** [cristian@flofinanstic.com](mailto:cristian@flofinanstic.com)
- **LinkedIn:** [linkedin.com/in/crecabar](https://www.linkedin.com/in/crecabar/)
- **Flō Finanstic:** [flofinanstic.com](https://flofinanstic.com/)
- **GitHub:** [@crecabar](https://github.com/crecabar) · [@flofinanstic](https://github.com/flofinanstic)
