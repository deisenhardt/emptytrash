# emptytrash

If Finder cannot empty trash, sudo can. Useful for messages like the following 

“Trash” can’t be opened right now because it’s being used by another task, 
such as moving or copying an item or emptying the Trash. Try again when the 
current task is complete. 


                                         [ Skip ] [ Stop ] [ Continue ]


note: sometimes the script may fail to kill a pid but will still empty trash anyway.  This will be clearly stated in stdout if it occurs, and you should investigate the pid further as needed.
