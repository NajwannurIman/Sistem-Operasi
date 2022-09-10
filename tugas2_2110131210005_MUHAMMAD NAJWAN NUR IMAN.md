<h1><center>1</h1>
<h1><center>INTRODUCTION</h1>
A modern computer consists of one or more processors, some main memory,
disks, printers, a keyboard, a mouse, a display, network interfaces, and various
other input/output devices. All in all, a complex system.oo If every application pro-
grammer had to understand how all these things work in detail, no code would ever
get written. Furthermore, managing all these components and using them optimally
is an exceedingly challenging job. For this reason, computers are equipped with a
layer of software called the <b>operating system</b>, whose job is to provide user pro-
grams with a better, simpler, cleaner, model of the computer and to handle manag-
ing all the resources just mentioned. Operating systems are the subject of this
book.
Most readers will have had some experience with an operating system such as
Windows, Linux, FreeBSD, or OS X, but appearances can be deceiving. The pro-
gram that users interact with, usually called the <b>shell</b> when it is text based and the
<b>GUI (Graphical User Interface)</b>—which is pronounced ‘‘gooey’’—when it uses
icons, is actually not part of the operating system, although it uses the operating
system to get its work done.
A simple overview of the main components under discussion here is given in
Fig. 1-1. Here we see the hardware at the bottom. The hardware consists of chips,
boards, disks, a keyboard, a monitor, and similar physical objects. On top of the
hardware is the software. Most computers have two modes of operation: kernel
mode and user mode. The operating system, the most fundamental piece of soft-
ware, runs in <B>kernel mode</b> (also called <b>supervisor mode</b>). In this mode it has
uagsiuahsa