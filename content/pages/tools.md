---
content_type: page
learning_resource_types:
- Tools
ocw_type: CourseSection
title: Tools
uid: 4a943900-de94-8e8c-5c50-0874d4a8bdcf
---

{{< tableopen >}}
{{< theadopen >}}
{{< tropen >}}
{{< thopen >}}
FILES
{{< thclose >}}
{{< thopen >}}
DESCRIPTIONS
{{< thclose >}}

{{< trclose >}}

{{< theadclose >}}
{{< tropen >}}
{{< tdopen >}}
6004.tgz ([TGZ]({{< baseurl >}}/resources/6004))
{{< tdclose >}}
{{< tdopen >}}
Compressed tar archive of all 6.004 files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


jsim.jar ([JAR]({{< baseurl >}}/resources/jsim-1))

nominal.jsim ([JSIM]({{< baseurl >}}/resources/nominal))

8clocks.jsim ([JSIM]({{< baseurl >}}/resources/8clocks))

stdcell.jsim ([JSIM]({{< baseurl >}}/resources/stdcell))


{{< tdclose >}}
{{< tdopen >}}
Latest release of JSim (2.0.28) and include files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


bsim.jar ([JAR]({{< baseurl >}}/resources/bsim))

beta.uasm ([UASM]({{< baseurl >}}/resources/beta))


{{< tdclose >}}
{{< tdopen >}}
Latest release of BSim (1.1.11) and include files
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
tmsim.jar ([JAR]({{< baseurl >}}/resources/tmsim))
{{< tdclose >}}
{{< tdopen >}}
Latest release of TMSim (1.1.8)
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
lab1checkoff.jsim ([JSIM]({{< baseurl >}}/resources/lab1checkoff))
{{< tdclose >}}
{{< tdopen >}}
Checkoff file for Lab 1
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
lab2checkoff.jsim ([JSIM]({{< baseurl >}}/resources/lab2checkoff))
{{< tdclose >}}
{{< tdopen >}}
Checkoff file for Lab 2
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


lab3checkoff\_6.jsim ([JSIM]({{< baseurl >}}/resources/lab3checkoff_6))

lab3checkoff\_10.jsim ([JSIM]({{< baseurl >}}/resources/lab3checkoff_10))

lab3adder.jsim ([JSIM]({{< baseurl >}}/resources/lab3adder))

lab3boolean.jsim ([JSIM]({{< baseurl >}}/resources/lab3boolean))

lab3compare.jsim ([JSIM]({{< baseurl >}}/resources/lab3compare))

lab3multiply.jsim ([JSIM]({{< baseurl >}}/resources/lab3multiply))

lab3shifter.jsim ([JSIM]({{< baseurl >}}/resources/lab3shifter))


{{< tdclose >}}
{{< tdopen >}}
Checkoff files for Lab 3
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
lab4header ([TXT]({{< baseurl >}}/resources/lab4header))
{{< tdclose >}}
{{< tdopen >}}
Header file for Lab 4
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
lab5checkoff.uasm ([UASM]({{< baseurl >}}/resources/lab5checkoff))
{{< tdclose >}}
{{< tdopen >}}
Checkoff file for Lab 5
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


lab6basicblock.uasm ([UASM]({{< baseurl >}}/resources/lab6basicblock))

lab6basicblock.jsim ([JSIM]({{< baseurl >}}/resources/lab6basicblock-1))

lab6pc.jsim ([JSIM]({{< baseurl >}}/resources/lab6pc))

lab6regfile.jsim ([JSIM]({{< baseurl >}}/resources/lab6regfile))

lab6ctl.jsim ([JSIM]({{< baseurl >}}/resources/lab6ctl))

lab6.uasm ([UASM]({{< baseurl >}}/resources/lab6))

lab6checkoff.jsim ([JSIM]({{< baseurl >}}/resources/lab6checkoff))


{{< tdclose >}}
{{< tdopen >}}
Checkoff files for Lab 6
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


lab7macros.uasm ([UASM]({{< baseurl >}}/resources/lab7macros))

lab7checkoff.uasm ([UASM]({{< baseurl >}}/resources/lab7checkoff))

swapregs.uasm ([UASM]({{< baseurl >}}/resources/swapregs))


{{< tdclose >}}
{{< tdopen >}}
Checkoff files for Lab 7
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
lab8.uasm ([UASM]({{< baseurl >}}/resources/lab8))
{{< tdclose >}}
{{< tdopen >}}
File for Lab 8
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}


projcheckoff.uasm ([UASM]({{< baseurl >}}/resources/projcheckoff-1))

projcheckoff.bin ([BIN]({{< baseurl >}}/resources/projcheckoff))

projcheckoff.jsim ([JSIM]({{< baseurl >}}/resources/projcheckoff-2))


{{< tdclose >}}
{{< tdopen >}}
Files for design project
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
jsim.el ([EL]({{< baseurl >}}/resources/jsim))
{{< tdclose >}}
{{< tdopen >}}
Major Emacs mode for editing JSim netlists
{{< tdclose >}}

{{< trclose >}}
{{< tropen >}}
{{< tdopen >}}
ant.jar ([JAR]({{< baseurl >}}/resources/ant))
{{< tdclose >}}
{{< tdopen >}}
Ant demo from lecture 6 (just for fun!)
{{< tdclose >}}

{{< trclose >}}

{{< tableclose >}}

Running JSim
------------

First, you'll need to install a Java system. The Sun Java Runtime Environment, Standard Edition (J2SE), for Linux, Solaris and Windows can be downloaded from [Sun's official site](http://java.sun.com/javase/index.jsp). J2SE for Mac OS X is available from [Apple's Web site](http://developer.apple.com/java/). On Linux, you'll want to change your PATH environment variable so that the "java" command is on your search path. On Windows and OS X, double-clicking any of the 6.004 jar files will run the program (assuming you've installed the Sun Java environment).

Once you've installed a Java environment and downloaded the 6.004 files, you can run JSim using the following command:

> java -jar jsim.jar -Xms8m -Xmx32m -reporterrors file...

You may have to specify complete pathnames for "java" and "jsim.jar" depending on your current search path and working directory. Each of the arguments is explained below.

> \-**jar jsim.jar** adds the java archive jsim.jar to the list of files Java examines when trying to find classes. jsim.jar contains the classes used by jsim for displaying/editing netlists, running simulations and browsing the results.
> 
> If you get an error of the form "Exception in thread "main" java.lang.NoClassDefFoundError: jsim/JSim", the Java runtime didn't find the jsim.jar file — try giving its full pathname, e.g., C:\\6.004\\jsim.jar or whatever is appropriate for your installation.
> 
> **\-Xms8m -Xmx32m** sets the minimum heap size to 8MB and the maximum heap size to 32MB. Starting JSim with a generous heap allocation avoids a lot of garbage collection overhead the first time your circuit is processed. If you run out of memory, try specifying the **\-no-local-names** option when running JSim. This will greatly reduce the size of the node name hashtable JSim constructs when processing the netlist. The downside of using this option is that nodes can only be referred to by using their name in the (sub)circuit where they were first defined.
> 
> **\-reporterrors** asks JSim to provide a backtrace whenever it encounters an internal error.
> 
> **file...** are optional arguments specifying one or more JSim netlist files.

Editing Netlists
----------------

The netlist editor built into JSim is based on the JTextArea class in Swing. Many people find the editing facilities provided by this class to be underwhelming and prefer to use an external editor. jsim.el defines a new major mode for EMACS useful for editing JSim netlists. You can invoke the mode automatically when reading in a ".jsim" file by adding the following to your .emacs file:

;;; jsim support, assumes jsim.el lives in your home directory

(autoload 'jsim-mode "~/jsim" nil t)

(setq auto-mode-alist (cons '("\\.jsim$" . jsim-mode) auto-mode-alist))

(add-hook 'jsim-mode-hook 'turn-on-font-lock)