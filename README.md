# Unix Handbook <!-- omit in toc -->

## Table of Contents <!-- omit in toc -->

- [References](#references)
- [What is Unix?](#what-is-unix)
- [What is Linux?](#what-is-linux)
- [Unix Architecture](#unix-architecture)
- [Unix Philosophy](#unix-philosophy)
- [Shell](#shell)
	- [What is a shell?](#what-is-a-shell)

## References

- <https://bash.cyberciti.biz/guide/Main_Page>
- <https://www.tutorialspoint.com/unix/index.htm>
- <https://ipwithease.com/linux-vs-unix/>

## What is Unix?

The Unix operating system is a set of programs that act as a link between the computer and the user.

The computer programs that allocate the system resources and coordinate all the details of the computer's internals is called the operating system or the kernel.

Users communicate with the kernel through a program known as the shell. The shell is a command line interpreter; it translates commands entered by the user and converts them into a language that is understood by the kernel.

## What is Linux?

Linux is a free open-source operating system based on Unix. Linus Torvalds originally created Linux with the assistance of developers from around the world. Linux is:

- Free
- Unix Like
- Open Source
- Network operating system

| Parameter | Linux | Unix |
|---|---|---|
| Inception Year | 1991 | 1969 |
| Standard | Open source operating system which is freely available | Operating system can only be used by its copywriters |
| System type | Just the kernel | Complete Operating system |
| Target use | Can be used by anyone including home user and developer | Developed mainly for servers, workstations and mainframes |
| Cost | LINUX is freely available and distributed with no associated cost | UNIX variants come as customized cost |
| Security | 60-100 viruses listed till date | 85-120 viruses listed till date |
| Interface type | Primarily uses GUI with option of CLI | Primarily uses CLI |
| Portability | Portable | Not portable |
| Variants | Ubuntu, RedHat, Solaris, OpenSuse, etc. | AIS, HP-UX, BSD, etc. |
| Source | Available in general public | Not available in general public |

## Unix Architecture

Here is a basic block diagram of a Unix system −

![Unix Architecture](unix_architecture.jpg)

The main concept that unites all the versions of Unix is the following four basics −

- **Kernel** − The kernel is the heart of the operating system. It interacts with the hardware and most of the tasks like memory management, task scheduling and file management.

- **Shell** − The shell is the utility that processes your requests. When you type in a command at your terminal, the shell interprets the command and calls the program that you want. The shell uses standard syntax for all commands. C Shell, Bourne Shell and Korn Shell are the most famous shells which are available with most of the Unix variants.

- **Commands and Utilities** − There are various commands and utilities which you can make use of in your day to day activities. `cp`, `mv`, `cat` and `grep`, etc. are few examples of commands and utilities. There are over 250 standard commands plus numerous others provided through 3rd party software. All the commands come along with various options.

- **Files and Directories** − All the data of Unix is organized into files. All files are then organized into directories. These directories are further organized into a tree-like structure called the filesystem.

## Unix Philosophy

The Unix philosophy is philosophical approaches to developing software based on the experience of leading developers of the Unix operating system. The following philosophical approaches also applies to Linux operating systems.

- Do one thing and do it well - Write programs that do one thing and do it well. Write programs to work together. Write programs to handle text streams, because that is a universal interface.
- Everything is file - Ease of use and security is offered by treating hardware as a file.
- Small is beautiful.
- Store data and configuration in flat text files - Text file is a universal interface. Easy to create, backup and move to another system.
- Use shell scripts to increase leverage and portability - Use shell script to automate common tasks across various UNIX / - Linux installations.
- Chain programs together to complete complex task - Use shell pipes and filters to chain small utilities that perform one task at time.
- Choose portability over efficiency.
- Keep it Simple, Stupid (KISS).

## Shell

Computers understand the language of zeros and ones known as binary language. The shell accepts human readable commands and translates them into something the kernel can read and process.

### What is a shell?

- The shell is a user program or it is an environment provided for user interaction.
- It is a command language interpreter that executes commands read from the standard input device such as keyboard or from a file.
- The shell gets started when you log in or open a console (terminal).
- Quick and dirty way to execute utilities.
- The shell is not part of system kernel, but uses the system kernel to execute programs, create files etc.
- Several shells are available for Linux including:
  - The Bourne Shell
  - The C Shell
  - The Korn Shell
  - The GNU Bourne-Again Shell
