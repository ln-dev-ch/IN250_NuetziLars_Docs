
## Git Commits
Has:
Parent - Hash Value of Parent
Author - Specified User from Git Config
Message - git commit -m "Message" content

## Chain
Chain of commits is formed by:
1. Hashing Snapshot of commit
2. Using hash as parent of next commit

## Hashing
Use a algorithm to change initial data to a hash value
Git uses SHA256
Advantages: Hashvalues vary wildly even with minimal changes of data