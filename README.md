Project 0x16.C SIMPLE SHELL

Group project on creating your own shell interpreter.
Carried out by:
1) Bruce Mahagwa <https://github.com/Bruce-Mahagwa>
2) Wairimu Maringa <https://github.com/WairimuMaringa>

General requirements of the project:
• Allowed editors: vi, vim, emacs.

• All your files will be compiled on Ubuntu 20.04 LTS using gcc, using the options -Wall -Werror -Wextra -pedantic -std=gnu89.

• All your files should end with a new line.

• README.md file, at the root of the folder of the project is mandatory.

• Your code should use the Betty style. It will be checked using betty-style.pl and betty-doc.pl.

• Your shell should not have any memory leaks.

• No more than 5 functions per file.

• All your header files should be include guarded.

• Use system calls only when you need to (https://alx-intranet.hbtn.io/rltoken/EU7B1PTSy14INnZEShpobQ).

• Write a README with the description of your project.

• You should have an AUTHORS file at the root of your repository, listing all individuals having contributed content to the repository.


List of the allowed functions and system calls include:
• access (man 2 access).
• chdir (man 2 chdir).
• close (man 2 close).
• closedir (man 3 closedir).
• execve (man 2 execve).
• exit (man 3 exit).
• _exit (man 2 _exit).
• fflush (man 3 fflush).
• fork (man 2 fork).
• free (man 3 free).
• getcwd (man 3 getcwd).
• getline (man 3 getline).
• getpid (man 2 getpid).
• isatty (man 3 isatty).
• kill (man 2 kill).
• malloc (man 3 malloc).
• open (man 2 open).
• opendir (man 3 opendir).
• perror (man 3 perror).
• read (man 2 read).
• readdir (man 3 readdir).
• signal (man 2 signal).
• stat (__xstat) (man 2 stat).
• lstat (__lxstat) (man 2 lstat).
• fstat (__fxstat) (man 2 fstat).
• strtok (man 3 strtok).
• wait (man 2 wait).
• waitpid (man 2 waitpid).
• wait3 (man 2 wait3).
• wait4 (man 2 wait4).
• write (man 2 write).


Shell compilation was done this way: gcc -Wall -Werror -Wextra -pedantic -std=gnu89 *.c -o hsh.
The shell should work in both interactive and non-interactive modes.
