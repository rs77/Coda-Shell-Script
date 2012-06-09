CODA SHELL SCRIPT
=================
Coda for the command line

Version 1.0
Version 1.1
Script now works with Coda 2 & makes Coda 2 default text editor


OVERVIEW
-----------------
Open files with Panic, Inc.'s Coda <http://www.panic.com/coda/> from the command line.


USAGE
-----------------
	coda [--help|-h] [<file> ...]

	--help|-h   show a usage message

	<file>      file will be opened in Coda.app (omit to launch Coda.app)
	            NOTE: if a specified file does not exist, it will be created

Launch Coda:

	> coda

Open file.txt (either command):

	> coda file.txt
	> open file.txt

Open file.txt and create and open file2.txt:

	> coda file.txt file2.txt


CREDITS
-----------------
(C) 2011 Noah Frederick <http://noahfrederick.com/>

Credit goes to Command-Line Coda, a Perl script (C) Aditya Bhargava, for the idea.
See <http://wefoundland.com/project/command-line_coda/>.

Coda (C) Panic, Inc. Coda is a trademark of Panic, Inc.


SOURCE
-----------------
The Git repository is available at <https://github.com/noahfrederick/Coda-Shell-Script>.
