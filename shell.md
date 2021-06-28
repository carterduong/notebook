~~~
> lsof -i :<port>
> kill -9 <process-id>
~~~
Kill a process on a specific `<port>` number

---

~~~
> rsync -a --progress <source-directory> username@remote_host:<destination-directory>
~~~
Sync a remote folder in archive mode

---

~~~
> ssh-keygen -t rsa -f ~/.ssh/<key-name>
~~~
Generate a public key (`<key-name>.pub`) and private key (`<key-name>`)

---

~~~
> ssh-add -K ~/.ssh/<private-key>
~~~
Add a private key to `ssh-agent`
