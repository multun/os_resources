# Part I -- The userland

Before understanding how your OS work, you better understand how regular
applications work, and interact with it.

Let's set some questions:

 - How does a processor works?
   - What's a register?
   - What's an instruction?
 - What's the program counter?
 - How does a userland program communicates with kernel-land?
 - What is userland?
 - What's the program stack?
 - What's virtual memory (like paging), when you have some?
 - How can two programs share memory?
 - What's the dynamic linker, why do you need it?

## Resources

 - https://www.youtube.com/watch?v=u9WK73mCD6U
 - http://www.emulator101.com/
 - http://bottomupcs.sourceforge.net/csbu/c1453.htm
 - http://nand2tetris.org/course.php
 - https://manybutfinite.com/post/journey-to-the-stack/
 - https://manybutfinite.com/post/anatomy-of-a-program-in-memory/
 - https://manybutfinite.com/post/system-calls/
 - https://eli.thegreenplace.net/2011/02/04/where-the-top-of-the-stack-is-on-x86/
 - https://eli.thegreenplace.net/2011/09/06/stack-frame-layout-on-x86-64/
 - https://techtalk.intersec.com/2013/07/memory-part-1-memory-types/

## Going further

 - https://gist.github.com/CMCDragonkai/10ab53654b2aa6ce55c11cfc5b2432a4
 - https://www.akkadia.org/drepper/
 - https://www.akkadia.org/drepper/dsohowto.pdf
 - https://www.akkadia.org/drepper/cpumemory.pdf

# Part II -- Going kernel

 - What do you need an OS for?
 - What's a context switch? When does it occur? Why do you need it?
 - How does your OS manages to share its time between tasks?
   - What's scheduling?
 - How does a kernel manages memory?
   - What's segmentation? Why is it crap?
   - What's paging? How does the kernel manages it?

## Resources

 - `Operating System Concepts - 9th edition`

 - https://manybutfinite.com/post/memory-translation-and-segmentation/
 - https://manybutfinite.com/post/cpu-rings-privilege-and-protection/

 - https://manybutfinite.com/post/how-computers-boot-up/
 - https://manybutfinite.com/post/when-does-your-os-run/
 - https://manybutfinite.com/post/how-the-kernel-manages-your-memory/

# Other

 - https://www.youtube.com/playlist?list=PLhixgUqwRTjxglIswKp9mpkfPNfHkzyeN