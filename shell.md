Kill a process on a specific `<port>` number
~~~
> lsof -i :<port>
> kill -9 <process-id>
~~~

Sync a remote folder in archive mode
~~~
> rsync -a --progress <source-directory> username@remote_host:<destination-directory>
~~~

Generate a public key (`<key-name>.pub`) and private key (`<key-name>`)
~~~
> ssh-keygen -t rsa -f ~/.ssh/<key-name>
~~~

Add a private key to `ssh-agent`
~~~
> ssh-add -K ~/.ssh/<private-key>
~~~
