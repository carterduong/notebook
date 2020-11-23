~~~
> lsof -i :<port>
> kill -9 <port>
~~~
Kill process on `<port>` number

~~~
> rsync -a --progress <source-directory> username@remote_host:<destination-directory>
~~~
Sync folders in archive mode.

~~~
> ssh-keygen -t rsa -f ~/.ssh/<key-name>
~~~
Generate a public key (`<key-name>.pub`) and private key (`<key-name>`)

~~~
> ssh-add -K ~/.ssh/<private-key>
~~~
Add a private key to the ssh-agent
