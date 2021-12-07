This doesn't work if you don't change the system_ip in the file data\system.properties to the host IP address.

change this

`system_ip=a.b.c.d`

to this:
`system_ip=192.168.1.10`

In this case my local IP address was 192.168.1.10.

Don't forget to make a dhcp lease on your router to get this working.


