# Generate SSH Key

Mostly follow the github docs.

## Steps:

1. open git bash
2. ssh-keygen -t ed25519 -C "your_email@example.com"
3. It ask question for name and location
4. Start the ssh-agent ( set it to automatic )
5. Add private key to ssd-add
6. Check is key added by ssh-add -l
7. Cat keyname.pub file
8. Add the copied key to github ssh setting
9. Make github ~/.ssh/config or C:\Users\anike\.ssh\config if not exists it is needed when you have to account for definig different hosts
10. Define hosts and other configurations in it.
