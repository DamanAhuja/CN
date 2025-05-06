# CN Practicals
## 1st File - Q2,3,4(Bus)
## 2nd File - Q4
## 3rd File - Q5,6,7,8,9

## Q5 
en

conf t

hostname sh

banner motd $

line con 0

password ABC123

login

enable secret ABC@123

exit

exit

en

sh run

## Q6
en

conf t

hostname r1

banner motd $

line con 0

password ABC123

login

enable password cisco

enable secret ABC@123

service password encryption

exit

exit

en
