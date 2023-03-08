# TA-Lib
TA-Lib - Technical Analysis Library 金融量化分析技术分析库

Copy from https://github.com/TA-Lib/ta-lib

官方发布版只提供了源代码，没有提供64-bit的C编译库，那就自己编译一个吧。
(https://ta-lib.org/hdr_dw.html)

博客园某能指标简介:
https://www.cnblogs.com/interdrp/p/16982663.html

##### Windows

Download [TA-Lib-0.5.0.zip]
and unzip to ``C:\TA-Lib``.

> This is a 32-bit binary release.  If you want to use 64-bit Python, you will
> need to build a 64-bit version of the library. Some unofficial (**and
> unsupported**) instructions for building on 64-bit Windows 10, here for
> reference:
>
> 1. Download and Unzip ``TA-Lib-0.5.0.zip``
> 2. Move the Unzipped Folder ``TA-Lib`` to ``C:\``
> 3. Download and Install Visual Studio Community (2015 or later)
>    * Remember to Select ``[Visual C++]`` Feature
> 4. Build TA-Lib Library
>    * From Windows Start Menu, Start ``[VS2015 x64 Native Tools Command
>      Prompt]``
>    * Move to ``C:\TA-Lib\c\make\cdr\win32\msvc``
>    * Build the Library ``nmake``

