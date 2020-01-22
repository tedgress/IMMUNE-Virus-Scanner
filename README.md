# IMMUNE-Virus-Scanner
Another layer of protection to put on your system

IMMUNE keeps hashes in a hash library of every file on the system. It cycles through the hashes to mak esure they don't change. 
Since the majority of files on a system are static, such as executables, dlls, config files, even user files like documents and videos,
IMMUNE can assume that when there is a drastic change to a file either the file is ok and being legitametly changed or there is malware. 
This works because when infected, a virus tends to spread rapdily. This sets a flag for IMMUNE.

The second part of IMMUNE's toolskit is when it identifies a potentially infect file, it examines the file and any other files that are 
flagged and compares their code. The chance that the two or three or more has common code signature is slim to none. In that chance 
that they have common code, it is likely that that code is viral code. 
