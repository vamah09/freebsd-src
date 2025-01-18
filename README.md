FreeBSD Source:
---------------
这是 FreeBSD 源码目录的最上层。

FreeBSD是一个操作系统，用于为现代服务器、桌面和嵌入式平台提供支持。

有关版权信息，请参阅本目录中的[the file COPYRIGHT](COPYRIGHT)。

此目录中的 Makefile 支持许多用于构建 FreeBSD 源代码树组件（或所有）的目标。
参阅 build（7）， config（8）， [FreeBSD 用户空间构建手册]（https://docs.freebsd.org/en/books/handbook/cutting-edge/#makeworld） 和 [内核手册]（https://docs.freebsd.org/en/books/handbook/kernelconfig/） 以获取更多信息，包括设置 make（1） 变量。

有关 FreeBSD 支持的 CPU 架构和平台的信息，请参阅 [FreeBSD
网站的平台页面]（https://www.freebsd.org/platforms/）。

对于官方的 FreeBSD 可启动映像，请参见 [release page]（https://download.freebsd.org/ftp/releases/ISO-IMAGES/）。

源码路线图：
---------------
| Directory | Description |
| --------- | ----------- |
| bin | System/user commands. |
| cddl | Various commands and libraries under the Common Development and Distribution License. |
| contrib | Packages contributed by 3rd parties. |
| crypto | Cryptography stuff (see [crypto/README](crypto/README)). |
| etc | Template files for /etc. |
| gnu | Commands and libraries under the GNU General Public License (GPL) or Lesser General Public License (LGPL). Please see [gnu/COPYING](gnu/COPYING) and [gnu/COPYING.LIB](gnu/COPYING.LIB) for more information. |
| include | System include files. |
| kerberos5 | Kerberos5 (Heimdal) package. |
| lib | System libraries. |
| libexec | System daemons. |
| release | Release building Makefile & associated tools. |
| rescue | Build system for statically linked /rescue utilities. |
| sbin | System commands. |
| secure | Cryptographic libraries and commands. |
| share | Shared resources. |
| stand | Boot loader sources. |
| sys | Kernel sources (see [sys/README.md](sys/README.md)). |
| targets | Support for experimental `DIRDEPS_BUILD` |
| tests | Regression tests which can be run by Kyua.  See [tests/README](tests/README) for additional information. |
| tools | Utilities for regression testing and miscellaneous tasks. |
| usr.bin | User commands. |
| usr.sbin | System administration commands. |

关于将您的源代码树与 FreeBSD 项目的一个或多个开发分支同步的信息， 请参考 [FreeBSD 手册]（https://docs.freebsd.org/en/books/handbook/cutting-edge/#current-stable）。
