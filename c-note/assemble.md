###汇编语言
1. 语法格式

绝大多数 Linux 程序员以前只接触过DOS/Windows 下的汇编语言，这些汇编代码都是 Intel 风格的。但在 Unix 和 Linux 系统中，更多采用的还是 AT&T 格式，两者在语法格式上有着很大的不同：

- 在 AT&T 汇编格式中，寄存器名要加上 '%' 作为前缀；而在 Intel 汇编格式中，寄存器名不需要加前缀
- 在 AT&T 汇编格式中，用 '$' 前缀表示一个立即操作数；而在 Intel 汇编格式中，立即数的表示不用带任何前缀
- AT&T 和 Intel 格式中的源操作数和目标操作数的位置正好相反。在 Intel 汇编格式中，目标操作数在源操作数的左边；而在 AT&T 汇编格式中，目标操作数在源操作数的右边。
- 在 AT&T 汇编格式中，操作数的字长由操作符的最后一个字母决定，后缀'b'、'w'、'l'分别表示操作数为字节（byte，8 比特）、字（word，16 比特）和长字（long，32比特）；而在 Intel 汇编格式中，操作数的字长是用 "byte ptr" 和 "word ptr" 等前缀来表示的。

  AT&T 格式 | Intel 格式
  ----|------
  movb val, %al | mov al, byte ptr val
- 在 AT&T 汇编格式中，绝对转移和调用指令（jump/call）的操作数前要加上'*'作为前缀，而在 Intel 格式中则不需要。
- 远程转移指令和远程子调用指令的操作码，在 AT&T 汇编格式中为 "ljump" 和 "lcall"，而在 Intel 汇编格式中则为 "jmp far" 和 "call far"，即：
- 在 AT&T 汇编格式中，内存操作数的寻址方式是`section:disp(base, index, scale)`, 而在 Intel 汇编格式中，内存操作数的寻址方式为`section:[base + index*scale + disp]`


####refer:
- http://oss.org.cn/kernel-book/ch02/2.6.1.htm
- http://www.ibm.com/developerworks/cn/linux/l-assembly/
- http://learn.akae.cn/media/ch18s01.html
- http://www.cnblogs.com/BoyXiao/archive/2010/11/20/1882716.html
