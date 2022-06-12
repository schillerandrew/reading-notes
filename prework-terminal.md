> # The Command Line

- command line (terminal) = a text-based interface (for an OS)
- shell = part of the OS that defines the terminal's behavior
- bash (Bourne again shell) = the most common shell

- absolute (file)path = specifies a location in relation to the root directory; always have a forward slash at the start
- relative (file)path = specifies a location in relation to the current directory; doesn't begin with a forward slash

- `file FILENAME/DIRECTORY` = tells you the file type of the file/dir
- in Linux, everything is a file, even directories
- files can have an extension or no extension
- Linux is case-sensitive

- `man COMMAND` = accesses the manual pages, a help function for each command
  - to exit the manual pages, hit 'q'
- `man -k SEARCH-TERM` = search the manual pages by keyword
- `/SEARCH-TERM` = search keyword once already in a manual page
  - `n` = after searching within a manual page, go to the next result

  - `cp SOURCE DEST` = copies a file
  - `mv SOURCE DEST` = moves a file
  - `rm FILENAME` = deletes a file

  - `rm -r` = removes a directory that isn't empty

  - `~` = refers to root directory
  - `.` = refers to current directory
  - `..` = refers to parent directory of the current directory

  - filenames/directories beginning with a `.` are hidden (`ls -a` to view hidden things)
  