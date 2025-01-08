```
ssh-keygen -t rsa
#or
ssh keygen -t ed25519
# Than needs to add ssh key to the account 
gh ssh-key add ~/.ssh/id_ed25519.pub --title "az400-example"
```