# Day 3 - Linux Permissions 

##  Objective
Learn file permissions and how to control access using chmod.

---

##  What are Permissions?

In Linux, every file has 3 types of permissions:

- Read (r)
- Write (w)
- Execute (x)

---

##  Types of Users

- Owner (u)
- Group (g)
- Others (o)

---

##  chmod Command

Used to change file permissions.

---

##  Numeric Method

Each permission has a number:

- r = 4
- w = 2
- x = 1

Examples:

chmod 777 file.txt → full access to everyone  
chmod 755 file.txt → owner full, others read + execute  
chmod 644 file.txt → owner can edit, others read only  

---

##  Why NOT 777?

- Anyone can read, write, and execute
- Very unsafe in real systems
- Can lead to hacking or data loss

---

##  What I Learned

- How permissions work
- How to use chmod
- Why security is important

---

##  Status
Day 3 Completed 
