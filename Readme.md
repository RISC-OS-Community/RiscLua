# RiscLua
RiscLua is a port to RISC OS of the Lua programming language. It differs from standard Lua in a few small details to be more conformant to RISC OS. The packaging of RiscLua has also varied. At one point it was a relocatable module, but it was found that error-handling was easier when packaged as an application.

Lua license is included [here](LICENSE)

Changes to Lua port for RISC OS are copyright Gavin Wraith and distributed under the same license as Lua original code (MIT license)


## Status:
```
RiscLua 86 (VFP)
Based on Lua 5.4.3
Compiler: GCC 4.7.4
Libraries:  riscos, lpeg
Numbers: 64bit integers, 64bit vfp
package.path:  rlua86:lib.?,?
package.cpath: rlua86:solib.?/so,?/so
date: 2021/09/18
```

For more info please click [here](http://www.wra1th.plus.com/lua/risclua.html)

