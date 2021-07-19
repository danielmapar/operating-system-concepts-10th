# Operating System Concepts 10th edition - Notes

* **POSIX.** POSIX (which stands for Portable Operating System Interface) represents
a set of standards implemented primarily for UNIX-based operating
systems. Although Windows systems can also run certain POSIX programs, our coverage of POSIX focuses on Linux and UNIX systems. POSIX compliant systems must implement the POSIX core standard (POSIX.1);
Linux and macOS are examples of POSIX-compliant systems. POSIX also
defines several extensions to the standards, including real-time extensions
(POSIX.1b) and an extension for a threads library (POSIX.1c, better known as Pthreads). We provide several programming examples written in C
illustrating the POSIX base API, as well as Pthreads and the extensions for
real-time programming. These example programswere tested on Linux 4.4
and macOS 10.11 systems using the gcc compiler.

* **Java**. Java is a widely used programming language with a rich API and
built-in language support for concurrent and parallel programming. Java
programs run on any operating system supporting a Java virtual machine
(or JVM).We illustrate various operating-system and networking concepts
with Java programs tested using Version 1.8 of the Java Development Kit
(JDK).

* **Windows systems**. The primary programming environment forWindows
systems is theWindows API, which provides a comprehensive set of functions
for managing processes, threads, memory, and peripheral devices.
We supply a modest number of C programs illustrating the use of this API.
Programs were tested on a system running Windows 10.