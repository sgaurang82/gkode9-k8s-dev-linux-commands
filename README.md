
# Should know linux commands for kubernetes developers

This list of command will work as handy book for windows developer with no exposure to linux.

## Aliasing command to speed up
```sh
alias docker="sudo docker"
```

## To find host and ip address information
```sh
hostname -I
hostname
```

## Display/List network configuration
```sh
ifconfig
```

## Check OS version details
```sh                     
cat /etc/os-release                       
```
## List enviornment variables
```sh
env
```

touch test.txt empty file

grep search content in output
ls -l | grep ch$
Grep ab file.txt search ab in text file

Ls -l | grep ^l line starts with l
Ls -l | grep ch$ lines end with ch

ls -l | grep "\->" search arrows

ls -li | grep "2 root" hard file and first number points to same I node
W get current users

Ps -f command started the process
htop interactive window to see processes

Mkdir 2> stderror.txt outputs error in file

service ssh status
Service ssh start

woami


Ping
Curl 
Wget -- download files

Adduser interactive

sudo chmod u+x name.sh

Useradd
passwd

service ssh status


Creating file.
cat >> config.txt <<EOF
key1=value1
key2=value2
EOF







