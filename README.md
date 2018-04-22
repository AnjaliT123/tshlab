# tshlab
tiny shell lab cs:app 3rd edition

This is my solution to the shell lab of Computer Systems: A Programmer's Perspective by Randall Bryant and David O'Halloran of CMU.

Users can execute programs either in foreground or in the background, which are then added to the tsh jobs queue.  The tsh program uses Linux signal handling and signal blocking code to reap zombie children and add/remove jobs from the job queue.
