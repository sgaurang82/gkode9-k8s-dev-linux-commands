
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
## Create empty file
```sh
touch test.txt
```
## Search Content
### Search in list. line ends with ch
```sh
ls -l | grep ch$
```
### Search contenin file. Follwoing will search ab in text file
```sh
grep ab file.txt
```
### Search in list, first line starts with l
```sh
ls -l | grep ^l line starts with l
```

### Search in list, first line starts with l
```sh
ls -l | grep "\->" search arrows
```
###  Search in long listing file list
```sh
ls -li | grep "2 root"
```

## Get current users
```sh
w get 
```

## Process list fully formatted
```sh
ps -f
```
## Process list interactive
```sh
htop
```

## Output error in file. use 2>
```sh
Mkdir 2> stderror.txt
```
## Create file using multiline
```sh
Creating file.
cat >> config.txt <<EOF
key1=value1
key2=value2
EOF
```


--- users 
Adduser interactive

sudo chmod u+x name.sh

Useradd
passwd

woami


ping
curl 
wget -- download files


service ssh status
Service ssh start



                  





