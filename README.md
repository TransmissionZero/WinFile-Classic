# Windows File Manager (WinFile)

## Table of Contents

  - [Introduction](#introduction)
  - [History](#history)
  - [License](#license)

## Introduction

This is a fork of [Microsoft's Windows File Manager](https://github.com/Microsoft/winfile). It is an attempt to get the
application running on older versions of Windows such as Windows NT 3.x and Windows 9x.

Currently the Unicode build successfully builds with Visual C++ 4.2, and the application runs under Windows NT 4. There
is an error on application startup under Windows NT 3.51, but I'll be looking at Windows NT 3.x support next. Windows 9x
support will be trickier, because there are lots of compiler errors in the ANSI build. If Windows 9x is possible, who
knows? Could it run under [Win32s](https://en.wikipedia.org/wiki/Win32s)?

## History

The Windows File Manager was originally released with Windows 3.0 in the early 1990s. You can
[read more about File Manager's history](https://en.wikipedia.org/wiki/File_Manager_(Windows)) on Wikipedia.

## License

Copyright (c) Microsoft Corporation. All rights reserved.

This repository contains additional changes made outside of Microsoft.

Licensed under the [MIT](LICENSE) License.
