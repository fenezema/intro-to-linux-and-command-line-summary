# Getting to Know

## Files, Pipes, and Permissions
This sections will mostly talk about how we interact with files, the editors, what pipes do, and permissions.

### Files
We can interact with files in so many ways. But, the easiest one would be using editor. There are so many editors out there that we can use, like nano, pluma, or even gedit. But most of them will be highly dependent on using GUI. But if we want to stay in Terminal, we might want to use the holy molly `VIM`. There are many sides of poeple that side with Vim and the other way around. I won't say that it is mandatory to at least understand Vim, but it's super helpful if we actually ended up understand and able to use Vim. 

The reason I'm saying that we're not mandatory to understand Vim is due what job did you do. If you happens to often remote connect a server, or doing ssh, you definitely want to learn Vim. On contrary, if you just doing some development, and your operation system always has a Desktop Environment on, then any other editors will works just fine. But again, there are no harm in learing Vim

### Pipes
Pipes is where things get interesting. Often we only do things once at a time. But with pipes, we can use the result of the first command, and pipe it to another command

The common example of this is by using `grep`

Supposed that we are running some python script that actually print a lot of things. We can then pipe it down, and say, `grep` the only thing we want. 

### Permissions
As previously mention. Every files and directories will have its own set of permissions that will resulting in different behaviour for different users that can be seen via `ls -la`

One way to change permissions for files or directories is by using the command `chmod <sets of permissions>`