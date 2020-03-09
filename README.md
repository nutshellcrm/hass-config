## Description
The config for the Nutshell Home Assistant instance.

To download the latest config files from the home assistant box, run
`script/download` on the local office network. See 1Password for the SSH keys.
Add the following to your ~/.ssh/config to ensure you can ssh seamlessly to
the box.

```
Host treehouse
IdentityFile ~/.ssh/treehouse
Port 23
User root
```
