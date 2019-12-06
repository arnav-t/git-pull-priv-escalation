# `git pull` privilege escalation
Escalate privileges if `git pull` is allowed in sudoers file.  
## Modifying the payload
The payload script is in `slave/.git/hooks/post-merge`. 
## Running the payload
If `sudo git pull` is called on the slave repository, the payload will run with full root privileges.
