# JNachos-Installation

1. JNACHOS Setup:

To work on and run JNachos you will need the java and javac programs. These are freely available at: http://java.sun.
com/javase/downloads/index.jsp.
You can choose to install either NetBeans IDE or Eclipse (both free) and work on the programming projects from an
integrated development environment.

• http://www.eclipse.org/
• http://www.netbeans.org/

The other options include:

• Use the supplied Makefile to compile and run JNachos.
• Do all compilation, running, etc. by hand.

Download, Install & Compile JNachos

1) Download JNachos from:
http://web.ecs.syr.edu/~pjmcswee/cis486/

2) To unpack JNachos (UNIX): unzip jnachos.zip, on Windows you should be able to ’double-click’ the file to extract it
or you may need to use a winzip program.

3) There are three options for compiling and development with JNachos.
    (1) Use and IDE such as: Eclipse, Netbeans, IntelliJ. To integrate JNachos with Eclipse, create a new project either
        from an existing source (the source directory that was unpacked from JNachos) or a blank default Java project and then          copy in the jnachos directory (under the src directy where JNachos was expended).
    (2) If you prefer to use Emacs, Pico, VIM, etc. you can compile and run by hand:
          (a) cd JNachos/src
          (b) javac jnachos/*.java jnachos/*/*.java jnachos/*/*/*.java
              -d ../build/classes
          (c) cd ../build/classes
          (d) java jnachos/Main
    (3) Make files used to work, but needs some work to get it up and usable again, so please ignore the make files for
        how.

Download, Install & Compile JNachos

1) Download JNachos from:
http://web.ecs.syr.edu/~pjmcswee/cis657/

2) To unpack JNachos (UNIX): unzip jnachos 1 0.zip, on Windows you should be able to ’double-click’ the file to extract it or you may need to use a winzip program.
3) To integrate JNachos with Eclipse, create a new project from existing source (the source directory that was unpacked
from JNachos).
4) To run with the Makefile go to the unpacked directory and type ‘make run’, this will compile and run JNachos. You
can install a version of make on your machine, there are ‘make’ executables for windows
5) To compile and run by hand:
     (1) cd JNachos/src
     (2) javac jnachos/*.java jnachos/*/*.java jnachos/*/*/*.java
         -d ../build/classes
     (3) cd ../build/classes
     (4) java jnachos/Main
