![Screenshot_20220429-011602-550](https://user-images.githubusercontent.com/99580833/165893711-ec3d2a6c-80f0-4163-b96f-d2bbfb2f48a7.png)



***THIS IS FOR EDUCATIONAL PURPOSES ONLY I DO NOT CLAIM ANY RESPONSIBILITY FOR WHAT YOU DO***
***I BASED THESE PORTALS OFF OF MY FAVORITE FOODS***





# portals
Some captive portals for the WiFi Pineapple Mark Seven


Open a terminal in your wifi pineapple and run ssh

service sshd start

SSHing into your pineapple from your linux terminal typically goes like this

ssh root@pineapple ip -p 22


To push the files into your pineapple you use scp they go in the portals directory
you can delete the portals directory in the pineapple and rename the folder cvmportals to portals and push the files from your system that way

in the pineapple 

rm -rf portals

in your system

sudo mv cvmportals portals

in your system

scp -r pathtoportals root@pineapple ip:/root 

***YOU NEED THE EVIL PORTAL MODULE INSTALLED ON YOUR PINEAPPLE TO USE THESE PORTAL***

AS ALWAYS ENJOY


