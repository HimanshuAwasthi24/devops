# Steps to setup vm
## Manual
**By following this video you can setup the vm's manually of ubuntu & centos**
[Watch the video on YouTube](https://www.youtube.com/watch?v=4j2juiMJIhg&t=350s)

## Automatic
1. Open gitbash and run following commands.</br>
```gitbash
#Creating three directories
mkdir -p vagrant-vms/{ubuntu,centos}

#changed direcotry to ubuntu to setup ubuntu vm
cd vagrant-vms/ubuntu/
vagrant init ubuntu/jammy64
vagrant up
vagrant ssh
exit

#Changed directory to centos to setup centos vm
cd ../centos
vagrant init eurolinux-vagrant/centos-stream-9
vagrant up
vagrant ssh
exit
```
