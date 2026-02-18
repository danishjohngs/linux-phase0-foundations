# Users, Groups, and Permissions

Linux is a **multi-user secure operating system**.

## Ownership Model

Each file has:

- user owner  
- group owner  
- permission bits  

Format:
user:group


## Permission Bits

- `r` → read  
- `w` → write  
- `x` → execute  

Example:
chmod 660 file


Owner and group can read/write, others denied.

## Security Principle

**Least privilege** ensures:

- minimal access  
- reduced attack surface  
- controlled collaboration
