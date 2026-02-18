# Linux Filesystem Architecture

Linux uses a **hierarchical directory structure** starting from the root directory `/`.

## Key Directories

- `/home` → user personal data  
- `/root` → root user home  
- `/etc` → system configuration files  
- `/var/log` → logs for services and authentication  
- `/tmp` → temporary writable storage  

## Security Importance

Separation between:

- system configuration  
- user data  
- logs  

prevents accidental or malicious system damage.

Understanding this layout is essential for:

- server hardening  
- log forensics  
- cloud instance management
