GNOME Settings
====================

GNOME Settings is GNOME's main interface for configuration of various aspects of
your desktop.

## Contributing

See `docs/CONTRIBUTING.md` for details on the contribution process, and `docs/HACKING.md`
for the coding style guidelines.

## Reporting Bugs

Bugs should be reported to the GNOME bug tracking system under the product
gnome-control-center. It is available at https://gitlab.gnome.org.

In the report please include the following information -

	Operating system and version
	For Linux, version of the C library
	How to reproduce the bug if possible
	If the bug was a crash, include the exact text that was printed out
	A stacktrace where possible [see below]

### How to get a stack trace

If the crash is reproducible, it is possible to get a stack trace and 
attach it to the bug report. The following steps are used to obtain a 
stack trace -
	
	Run the program in gdb [the GNU debugger] or any other debugger
		ie. gdb gnome-keyboard-properties
	Start the program
		ie. (gdb) run
	Reproduce the crash and the program will exit to the gdb prompt
	Get the back trace
		ie. (gdb) bt full

Once you have the backtrace, copy and paste this either into the 
'Comments' field or attach a file with it included.