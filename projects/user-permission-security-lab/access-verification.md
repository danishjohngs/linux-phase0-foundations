
---

## access-verification.md

```markdown
## Access Validation

### dev1 Write Access (Expected: Success)

su - dev1
echo "hello from dev1" >> /project/secret.txt
```

### Result: Successful write.
--- 

### Restrict Group Write
```
sudo chmod 640 /project/secret.txt
```
### dev2 Write Attempt (Expected: Permission Denied)
```
su - dev2
echo "hack attempt" >> /project/secret.txt
```


### Result:
Permission denied
