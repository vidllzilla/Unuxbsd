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

Third-party software distributed under the Common Development and Distribution License (CDDL).

contrib

Imported third-party software.

crypto

Cryptographic libraries and related utilities.

etc

Template files for the /etc directory.

gnu

Third-party software distributed under the GPL or LGPL.

include

System header files.

kerberos5

Heimdal Kerberos build infrastructure.

krb5

MIT Kerberos build infrastructure.

lib

System libraries.

libexec

Programs intended to be executed by other programs or system services.

packages

Base system packages.

release

Build scripts and tools for producing system releases and images.

rescue

Build files for the statically linked /rescue utilities.

sbin

System administration commands.

secure

Build infrastructure for cryptographic components, excluding Kerberos.

share

Shared data, documentation, and resources.

stand

Boot loader source code.

sys

Kernel source code and platform-specific system components.

targets

Support files for experimental DIRDEPS_BUILD.

tests

Automated test suites.

tools

Development tools and utilities not included in the installed base system.

usr.bin

User-level command-line programs.

usr.sbin

System administration utilities.

Additional directories may contain their own documentation, copyright notices, and license information.

For project documentation, release information, and development updates, refer to the official UNUXBSD project resources.
