# ab2ascii
Converts AmigaBasic Source-Code-Files to ASCII without orginal AmigaBasic-Installation

ab2ascii reads binary AmigaBASIC sources, expands tokens and symbols and generates ASCII output.  
Today there is need for ab2ascii since AmigaBASIC does not run anymore under versions of Kickstart V37+.  
ab2ascii should do exactly the same as the AmigaBASIC equivalent

                            SAVE "filename",A

In fact many interresting AmigaBASIC programs have been published in the past and they should not be lost.

By default ab2ascii converts from the standard input stream to the stdout, i.e. you can convert your binaries through a pipe.  
If any input filenames are given in the command line these will be used instead of stdin.

