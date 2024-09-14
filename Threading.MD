## Daemon threads

In computer science, a daemon is a process that runs in the background. Python threading has more 
specific meaning for the daemon. A daemon thread will shut down immidiately when the program 
exits.

If a program is running Threads that are not daemons, then the program will wait for these threads
to complete before it terminates. Threads that are daemons, however, are just killed
wherever they are when the program is exiting.