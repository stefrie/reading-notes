#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)
***

#### git: version control, allows us to collaborate on code simultaneously ####
#### GitHub: online code storage for all versions ####
## **git + GitHub = awesome** ##
- All teammates can work on the same files at the same time and not affect each other
- Keep history of each file over time
- Work on code locally, merge with other code

# [Git Tutorial on Udemy](https://blog.udemy.com/git-tutorial-a-comprehensive-guide/) #

## Excerpt ##
### So, what is Git? ###
**Snapshots**
Git is a DVCS that stores data in a file system made up of snapshots. Each time you save a changed version of your project — called commit — Git creates a snapshot of the file and stores a reference to it. If the file has not changed, Git only stores a reference to the already-stored identical version of it.

**Local Operations**

Git mostly relies on local operations because most necessary information can be found in local resources. This allows for process expediency because a project’s history resides on the local disk, eliminating the need to fetch history information from the server, and allowing one to continue work on a project even when not online or on a VPN.

**Tracking Changes**

Every single change applied to any file or directory is tracked by Git. And, as the gatekeeper, Git will always detect file corruption or loss of information in transit.

**Loss of Data**

Git is set up to greatly minimize the possibility of irreversible damage to files, such as accidentally lost data. Git makes it extremely difficult for a snapshot of your file that is committed to be lost.

**States**

Files in Git can reside in three main states: committed, modified and staged:

   ***Committed***

Data is securely stored in a local database

   ***Modified***

File has been changed but not committed to the database

   ***Staged***

Flagged a file's changed version to be committed 

***
#### [Home](../README.md) | [Code 102](../102main.md) | [Code 201](../201main.md) | [Code 301](../301main.md) | [Code 401](../401main.md)