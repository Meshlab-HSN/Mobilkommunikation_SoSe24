# Add your public SSH keys in the table (to be used for the remote connection from Laptop/Tablet to the Linux VM @server_bob)

1. Generate s ssk key pair (public & private key) on your local machine by typing via command line `ssh-keygen -t ed25519` or `ssh-keygen -t rsa -b 4096` (...the keys should look like something like this: `ssh-ed25519 .....== user@userPC`)
2. Add the content of your fresh generated public part of the ssh key-pair as pull-request to the table below
   
*Your IP address is always `172.20.1.X/24` with `X = 30 + <team number>`*
<br/>

**Choose & Commit**

| Team |  VM IP	      | Student Name             |  public ssh key         |
| :--: | :------------: | :----------------------: | :---------------------- |
|1.|-|Laura Komma| ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABAQDQn5C3Fs+lN1dwqDq70wY5EtiVteh1XipEgOeY5N6sJcGmiIvffyyc8pbQJr5bikM88wrRzmD0JEh+EMovdbFhdDx5AnwsRS3TDsc1qmmnEHWnMRE1zw1t3l1ewTBvp9tVlWiIc4pdmCryLw3j5f6hxqne2DWJnX/RHkfEG5Q9mVSk0UQhGtjyv+dB9Gn6GtuCaPW+UsROoyr2PiOKTLIoD+++h0WBlWpPY3U1hj5UT3fS1tb3byOB29Km8EaJKCHXjQWvR7bIs84n2b3qrH7yyS86tOKUa8oepYqkMySf+L11fwLhVEAiWXK2/WEelPH01RjawHqJKvooefziybgX|
|1.|-|Jonas Stephan|ssh-rsa AAAAB3NzaC1yc2EAAAADAQABAAABgQDSn8t/iBdyH0g2sb/Z2sYGNgYSG0AgH5Oxs0/hZn1SdEHlLvQMbMJNKwb/y6ilhyAaj0XDcWbSsUMHfgBGbJzUsItuZMYi2JziYeb5gNS3rMsz7PmDHvjN/8nuzUvA6v8XfDUsvDzWGrdlYrRVGwF4dAYJ+run8z8IGbjRY8CZumJPzCiit8Mdh7yFs/hzKMF35Sq/Pvq5FoCHyCiJaYqmYAVZL7rcbOTyPKVVYDAd8HWVXPiGkP3mCqJLu5eWWSy0dIA0KYkaDs9mHOyTqlv3384l3upR+LmsoL/ZNHSxG5Yevnh+kcz+UuHxDHLMY0+0Cvm3al1JNNRj73q2LhofRlzdVDVTZDOnvYY4rYvpWBaje9bO13+5jNFmvJjscg8sEkXd4qjUGtlJSZ6layPPQvj3S/cC0UZyih+mKiMIPMBrQOzDoZnrqb9tWWQIh0cMBOMv6wuTGnbEANniaJjHn4O/JZG30eiDJbXM7t6O5CIffdPIPbLOMUXJN282hMU= jonas@LAPTOP-14877C8V|
