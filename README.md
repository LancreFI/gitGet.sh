# gitGet.sh
Carve/download files from public facing .git/ where directory listing is disabled

Still unfinished. At the moment only downloads from the root dir of a host (target.host/.git/) also would require a lot more of error checking etc.

Carving is based on the standard files refs/heads/master and logs/refs/heads/master, also polls for some other standard files first, then carves the object based on these two masters.

Unfinished and tested only on one CTF, where we had the difficulty of having to do too much manual labour :D
