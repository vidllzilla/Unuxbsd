UNUXBSD Source

This is the top level of the UNUXBSD source directory.

UNUXBSD is an operating system based on the FreeBSD source code, with additional original software, build infrastructure, documentation, and system components developed by the UNUXBSD Project.

The project combines the stability and BSD heritage of FreeBSD with original enhancements created by the UNUXBSD Project.

Copyright

Original FreeBSD source code remains copyrighted by The FreeBSD Project and its respective copyright holders.

Original UNUXBSD source code, documentation, artwork, build scripts, and other original works are copyrighted by the UNUXBSD Project and are licensed under the CUN License Version 2.0, unless otherwise stated.

Third-party software included in this source tree remains subject to its own copyright notices and license terms.

Source Tree

The source tree follows the general organization of the FreeBSD source tree. Individual directories may contain additional copyright notices and license information.

For build instructions, configuration, and platform-specific information, consult the documentation included with the project.

For licensing information:

COPYRIGHT — FreeBSD and third-party copyright notices.

LICENSE.TXT — CUN License Version 2.0 for original UNUXBSD works.

Individual source directories may contain additional license files where applicable.

The Makefile in this directory supports a number of targets for building components (or all) of the FreeBSD source tree.
See build(7), config(8), [FreeBSD handbook on building userland](https://docs.freebsd.org/en/books/handbook/cutting-edge/#makeworld), and [Handbook for kernels](https://docs.freebsd.org/en/books/handbook/kernelconfig/) for more information, including setting make(1) variables.

For information on the CPU architectures and platforms supported by FreeBSD, see the [FreeBSD
website's Platforms page](https://www.freebsd.org/platforms/).

For official FreeBSD bootable images, see the [release page](https://download.freebsd.org/ftp/releases/ISO-IMAGES/).

Source Roadmap:
---------------
| Directory | Description |
| --------- | ----------- |
| bin | System/user commands. |
| cddl | Source code for third-party software under the Common Development and Distribution License. |
| contrib | Source code for third-party software. |
| crypto | Source code for cryptographic libraries and commands (see [crypto/README](crypto/README)). |
| etc | Template files for /etc. |
| gnu | Source code for third-party software under the GNU General Public License (GPL) or Lesser General Public License (LGPL). Please see [gnu/COPYING](gnu/COPYING) and [gnu/COPYING.LIB](gnu/COPYING.LIB) for more information. |
| include | System include files. |
| kerberos5 | Build system for Kerberos 5 (Heimdal). |
| krb5 | Build system for Kerberos 5 (MIT). |
| lib | System libraries. |
| libexec | System commands intended to be executed by other commands or daemons. |
| packages | Base system packages. |
| release | Makefiles and scripts used for building releases and VM images. |
| rescue | Build system for statically linked /rescue commands. |
| sbin | System commands. |
| secure | Build system for cryptographic libraries and commands (excluding Kerberos). |
| share | Shared resources. |
| stand | Boot loader sources. |
| sys | Kernel sources (see [sys/README.md](sys/README.md)). |
| targets | Support for experimental `DIRDEPS_BUILD` |
| tests | Tests which can be run by Kyua.  See [tests/README](tests/README) for additional information. |
| tools | Ancillary utilities and tests (not included in the build). |
| usr.bin | User commands. |
| usr.sbin | System administration commands. |

For information on synchronizing your source tree with one or more of the FreeBSD Project's development branches, please see [FreeBSD Handbook](https://docs.freebsd.org/en/books/handbook/cutting-edge/#current-stable).
🚀
