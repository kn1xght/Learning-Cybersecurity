# LINUX FUNDAMENTALS 1
**Date:** 2025-10-11

I was surprised to learn that Linux powers many things, examples being: PoS systems that I have personally used heavily when I worked in service jobs. Moreover, I was also unaware it’s used in critical infrastructures such as traffic light controllers or industrial sensors.

Similar to how different Windows versions exist (7, 8, and 10), there are many different versions/distributions of Linux too. Notable ones are **Ubuntu**, **Debian**, and **Kali**. Depending on your role, you choose the one that suits the job best: **Ubuntu/Debian** for more general/blue-team roles, and **Kali** for offensive/pentesting roles.

The first release of Linux took place in **1991**.

The **major** advantage of using something like Ubuntu is how lightweight it is. Of course, this also has its disadvantages: often there is no GUI (Graphical User Interface). A large part of interacting with these systems is using the **terminal**, which is purely text-based.

---

### Basic Commands
- `echo` — outputs any text that we provide  
- `whoami` — finds out which user we’re currently logged in as  
- `ls` — list directory contents  
- `cd` — change directory  
- `cat` — display/concatenate file contents  
- `pwd` — print working directory  

### Intermediate Commands
- `find` — more sophisticated search compared to hopping around with `cd`/`ls`  
- `grep` — targeted text search (more focused than just viewing with `cat`)  

### Linux Operators (Redirection/Chaining)
- `&` — run a command in the background of your terminal  
- `&&` — combine multiple commands on one line; run the next only if the previous succeeds  
- `>` — redirect command output to a file (overwrites the file)  
- `>>` — redirect command output to a file but **append** instead of overwriting  

---

### Takeaway

Getting a feel for how Linux fits together and why it’s used across so many systems. Even the simple stuff like navigation and basic commands already shows how direct and efficient it is compared to other operating systems.