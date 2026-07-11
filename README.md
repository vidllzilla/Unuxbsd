UNUXBSD Source

This is the top-level source directory for the UNUXBSD Project.

UNUXBSD is an operating system built on the FreeBSD source code with additional original software, documentation, build infrastructure, and system components developed by the UNUXBSD Project.

Copyright

The FreeBSD-derived portions of this source tree remain copyrighted by The FreeBSD Project and their respective copyright holders and continue to be governed by their original license terms.

Original files created by the UNUXBSD Project are copyrighted by the UNUXBSD Project and are licensed under the CUN License Version 2.0, unless another license is stated.

Third-party software included in this source tree remains under its respective copyright notices and license terms.

Source Tree

The source tree follows the general organization of the FreeBSD source tree. Some directories may contain additional copyright notices, licenses, or documentation specific to their contents.

The top-level Makefile provides targets for building individual components or the complete operating system. Refer to the project's documentation for build instructions, supported architectures, kernel configuration, and release procedures.

Source Roadmap

Directory

Description

bin

System and user commands.

cddl

Source code for third-party software under the Common Development and Distribution License (CDDL).

contrib

Source code for third-party software.

crypto

Source code for cryptographic libraries and commands. See crypto/README for additional information.

etc

Template files for /etc.

gnu

Source code for third-party software under the GNU General Public License (GPL) or GNU Lesser General Public License (LGPL). See gnu/COPYING and gnu/COPYING.LIB for additional information.

include

System header files.

kerberos5

Build system for Kerberos 5 (Heimdal).

krb5

Build system for Kerberos 5 (MIT).

lib

System libraries.

libexec

System commands intended to be executed by other commands or daemons.

packages

Base system packages.

release

Makefiles and scripts used to build releases and virtual machine images.

rescue

Build system for statically linked /rescue commands.

sbin

System commands.

secure

Build system for cryptographic libraries and commands, excluding Kerberos.

share

Shared resources.

stand

Boot loader sources.

sys

Kernel source code. See sys/README.md for additional information.

targets

Support for experimental DIRDEPS_BUILD.

tests

Test suites that can be run using Kyua. See tests/README for additional information.

tools

Ancillary utilities and tests that are not included in the system build.

usr.bin

User commands.

usr.sbin

System administration commands.
