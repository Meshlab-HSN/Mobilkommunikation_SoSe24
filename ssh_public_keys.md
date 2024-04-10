# Add your public SSH keys in the table (to be used for the remote connection from Laptop/Tablet to the Linux VM @server_bob)

1. Generate s ssk key pair (public & private key) on your local machine by typing via command line `ssh-keygen -t ed25519` or `ssh-keygen -t rsa -b 4096` (...the keys should look like something like this: `ssh-ed25519 .....== user@userPC`)
2. Add the content of your fresh generated public part of the ssh key-pair as pull-request to the table below
   
*Your IP address is always `172.20.1.X/24` with `X = 30 + <team number>`*
<br/>

**Choose & Commit**

| Team |  VM IP	      | Student Name             |  public ssh key         |
| :--: | :------------: | :----------------------: | :---------------------- |
