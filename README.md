# zaydabushamma.md


CWE-276: Incorrect Default Permissions

Although the likelyhood of of this occuring is medium instead of high the outcome can lead to destruction and
all types of cybersecurity related issue. Random individuals 
are able to view, execute, and change any type of information including passwords, obtain secret keys, impersonate 
users and much more. CWE-276(incorrect default permissions is giving unauthorized users permissions to modify a file
wheater it be on purpose or an accident. It may not be an accident or on purpose but the default permissions were putting
the files at risk and needed to be changed from unwanted visitors. There are many types of CWE's relating to incorrect permissions 
such as Incorrect Execution-Assigned Permissions, Insecure Inherited Permissions and Access to Critical Private Variable via Public
Method. Although this CWE is related to once a file was installed on a system the permissions given to that file automatically(default) 
are allowing anyone to modify the files which can cause issues and keep data from files unprotected from attackers or maliciousware. 

CWE-732: Incorrect Permission Assignment for Critical Resource is the parent of this CWE and is a lot more dangerous with the likelyhood
being very high and its related to a database instead of files and each file in database was sensitive that actors contained and had 
harmful intentions. An example of CWE-276 would be CVE-1999-0426 when /dev/kmem in linux not updated to the most recent version might have 
an insecure default permissions set and will allow unintended users for IP spoofing. Some programs are designed to forcefully take control
of your system to download unwanted programs and maybe even load maliciousware. Once a program was installed on my system the default permission
was to allow it to have full read write and execute permissions and it did all that without informing the system or administator. Dolnloading and installing random programs 
and launch the program without wanting to be launched, any program of file needing full permissions should be completely necessary or the developer is not trusted
and have bad intensions of being on your system.

Using the chmod you can add, remove, allow executable permissions and much more for groups, owners and others. You may also go into your local disk c: 
and into properties, then on the security tab choose which party recieves which permissions. You may also want to check each individual file, its importance and
if it should recieve the permissions its been given. As new files and programs are installed the default permissions should continiously be checked to see if any 
files are modified with a harmful intent.



























