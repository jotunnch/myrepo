# myrepo
testing my setup

This line here is from THE RSTUDIO

Checking to see how ssh keys working.

Passphrase asked for once.
Twice? Yes, it's still asking for it :/

I think if I do the ssh-agent add keys to it, then it will work.
Doing this in the shell.
`eval $(ssh-agent -s)`
`ssh-add ~/.ssh/id_rsa`

Still asked for it after adding this.
Didn't help.

Tried making a symbolic link. Restarted Rstudio.
Didn't help.