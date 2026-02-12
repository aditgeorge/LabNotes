Get PAT (Personal Access Token)
Github > Settings > Developer Settings > Personal Access Tokens > New classic PAT > Copy the PAT

Install Git
sudo apt install git
git config --global credential.helper store

Clone/Pull
when you pull a private repo or try to push, you will be prompted the id and password
id is your github username and password is the personal access token.
the PAT will be stored as plain text, a better alternative is a keyring (need to research and implement)