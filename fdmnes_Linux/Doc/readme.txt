This package contains:

- "fdmnes_linux64"     : executable of fdmnes for Linux 64 bits (Intel)

- run_fdmnes_command   : Command for Linux to execute fdmnes_linux64.
                         When clicking on it, the working directory of fdmnes_Linux is the current rirectory
                         and not the default user's home directory.

- "Sim/Test_stand/in"  : directory containing a set of examples of indata files for fdmnes
- "fdmfile.txt"        : fdmnes indata file  

- "Manuel.pdf"         : manual in French
- "Manuel_Eng.pdf"     : manual in English
- "Notes_SpectroX.pdf" : Notes on x-ray absorption spectroscopies in French
- "FDMNES_modifications.txt" : summary of the modifications and corrections in FDMNES
- "Benchmark_Wilcke_ESRF.txt" : A benchmark on the parallelisation done by Rainer Wilcke, ESRF, Grenoble, France 
   
fdmfile.txt must be in the same directory than the executable when running.
On Mac and on Linux when clicking on the executable, if fdmfile.txt is not found anyway,
this means that the default working directory is not the current one where is the executable.
This problem is solved for Mac by clicking on the command "run_fdmnes_command" instad of directly on the executable.

When the example indata files are not working, especially under linux, open them, save and close them,
then try again.
