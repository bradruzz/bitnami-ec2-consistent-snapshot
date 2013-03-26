# bitnami-ec2-consistent-snapshot
Stops mysql and creates an EBS snapshot once per week on Bitnami's AWS LAMP stack.

## Why
Regularly back up an entire system.

## How
[ec2-consistent-snapshot](https://github.com/alestic/ec2-consistent-snapshot) & cron.

## Install
`vpkg install snapshot\  
	--recipe-url "https://raw.github.com/jessetane/bitnami-ec2-consistent-snapshot/master/.vpkg"`

## License
[WTFPL](http://www.wtfpl.net/txt/copying/)
