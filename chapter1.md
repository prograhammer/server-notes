# SSH - Part1

### Creat A Local Key
Create an SSH key on your local computer:

```
# Navigate to or create a .ssh directory for your user
cd ~/.ssh

# Generate an SSH key pair
ssh-keygen -t rsa -b 4096 -C prograhammer@gmail.com -f id_myidentity
```
