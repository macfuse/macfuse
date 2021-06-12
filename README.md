macFUSE
=======

macFUSE is a software package for macOS that lets non-privileged users create their own file systems without having to write a single line of kernel code. This is achieved by running file system code in user space while the macFUSE kernel extension provides only a "bridge" to the actual kernel interfaces.

About macFUSE
-------------

The latest version of macFUSE supports macOS 10.9 to macOS 12. 

The software package provides multiple APIs for developing full-featured user space file systems. libfuse.dylib provides a superset of the standard Unix FUSE API. macFUSE.framework is a high-level Objective-C wrapper for the libfuse C API.

Developers can create numerous types of file systems using the provided APIs, e.g. on-disk file systems, layering file systems, network/distributed file system and many more. Three popular use cases are accessing files in the cloud, accessing files on non-native (unsupported by macOS) file systems and transparent encryption/decryption of files.

macFUSE file systems are regular applications (as opposed to kernel extensions). This means developers have as much flexibility and choice in programming tools, debuggers, and libraries as they have when developing regular application for macOS.

For more information see https://macfuse.io and the macFUSE wiki.

License
-------

Please see LICENSE.txt.

Source Code
-----------

This repository contains the source code of libfuse.dylib and macFUSE.framework. The other components, e.g. the macFUSE kernel extension, are closed-source.    

The source code of the last full open source release (version 3.8.3, supports macOS 10.5 to macOS 10.14.4), can be found in the [support/osxfuse-3](https://github.com/osxfuse/osxfuse/tree/support/osxfuse-3) branch on https://github.com/osxfuse/osxfuse/.
