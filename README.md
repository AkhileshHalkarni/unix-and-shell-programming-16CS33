# unix-and-shell-programming-16CS33
#DESCRIPTION
Bzcmp and bzdiff are used to invoke the cmp or the diff program on bzip2 compressed files. All options specified are passed directly to cmp or diff. If only 1 file is specified, then the files compared are file1 and an uncompressed file1.bz2. If two files are specified, then they are uncompressed if necessary and fed to cmp or diff. The exit status from cmp or diff is preserved.
