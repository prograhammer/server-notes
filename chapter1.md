# SSH - Part1

### Create A Local Key
Create an SSH key on your local computer:

```
# Change directory to or create a .ssh directory for your user
cd ~/.ssh

# Generate an SSH key pair
ssh-keygen -t rsa -b 4096 -C prograhammer@gmail.com -f id_rsa
```

Notes:

- **-t rsa** - Create an RSA type key pair.
- **-b 4096** - Use 4096 bit encryption.
- **-C prograhammer@gmail.com** - Comments go here, such as an email or name.
- **-f id_rsa** - The name of the SSH identity files. 
- The two files created would be id_rsa and id_rsa.pub. The private key file would stay on your local computer and not given out. However some apps that you install locally may ask for the location of your private key file so they can "act on your behalf". In most all cases, the public key is used to give out to anyone who wants to establish secure SSH communication with you.


