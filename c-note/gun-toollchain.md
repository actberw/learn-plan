###GNU工具链
1. GNU工具链包含一下几部分:
 - gnu make 自动化编译和构建工具
 - GCC (GNU Compiler Collection) 编译器集合
 - binutils (GNU Binary Utilities) as, ld等工具
 - gdb (GNU Debugger) 调试器 
 - autotools(GNU build system)
    - Autoconf
    - Autoheader
    - Automake
    - Libtool

2. makefile编写参见pdf(跟我一起写Makefile)
3. binutils 包含的命令 

  command | desc
  ----|------
  as      | assembler popularly known as GAS (Gnu ASsembler)
  ld      | linker
  gprof   | profiler
  addr2line | convert address to file and line
  ar      | create, modify, and extract from archives
  c++filt | demangling filter for C++ sy mbols
  dlltool | creation of Windows dynamic-link libraries
  gold    | alternative linker
  nlmconv | object file conversion to a NetWare Loadable Module
  nm      | list symbols in object files
  objcopy | copy object files, possibly maki     ng changes
  objdump | dump information about object files
  ranlib  | generate indexes for archives
  readelf | display content of ELF files
  size    | list total and section sizes
  strings | list printable strings
  strip   | remove symbols from an object file
  windmc  | generates Windows message resources
  windres | compiler for Windows resource files    

4. autotools(refer#1)

####refer:
- http://blog.csdn.net/scucj/article/details/6079052
