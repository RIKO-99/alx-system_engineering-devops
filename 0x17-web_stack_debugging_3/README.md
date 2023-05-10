# alx-system_engineering-devops
When debugging, sometimes logs are not enough. Either because the software is breaking in a way that was not expected and the error is not being logged, or because logs are not providing enough information. In this case, WE need to go down the stack!
Wordpress is usually run on LAMP (Linux, Apache, MySQL, and PHP), which is a very widely used set of tools.

The web stack that am debugging today is a Wordpress website running on a LAMP stack.


### project Requirments

Using strace, find out why Apache is returning a 500 error. Once you find the issue, fix it and then automate it using Puppet (instead of using Bash as you were previously doing).

Hint:

strace can attach to a current running process
You can use tmux to run strace in one window and curl in another one
Requirements:

Your 0-strace_is_your_friend.pp file must contain Puppet code
You can use whatever Puppet resource type you want for you fix

files will be interpreted on Ubuntu 14.04 LTS virtual machine orchestration.
Puppet manifests must pass puppet-lint version 2.1.1 without any errors.
