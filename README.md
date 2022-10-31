# MAN-IN-THE-MIDDLE-ATTACK
Kali Linux with ettercap tool

step1- Install Kali linux in Virtual Box

step2- Open ettercap tool (pre-installed in within linux system)

![image](https://user-images.githubusercontent.com/106810794/198945591-d6771735-6e84-4115-b025-98e25a26139e.png)

step3- Select eth0 because our machine is connected with ethernet. click ok

step4- Go to search bar and find some hostId it is besically some ip address that connected with same router.

step5- Select Target 1 as router gateway , Target 2 as victim machine ip address.

step6- Now you need to change some configuration within linux system.

![image](https://user-images.githubusercontent.com/106810794/198947020-140a2352-c805-4ed2-a630-ff4ad77f1f2e.png)

step7- Open wireshark to see, how ARP going to environment to confuse others ip addresses. when to perform MITM attack after that you will be able to see.

step8- Now go to MITM menu right-up, will see ARP poisoning then select it. 

step9- check sniff remote connections then click ok.

![image](https://user-images.githubusercontent.com/106810794/198947385-93ec6281-6397-4e15-a74e-a63f8938491c.png)
Here you are able to see ARP is going to network traffic to confuse others ip addresses.

step10- You have done your work!.Now wait for victime machine to perform any action on http link.

Victim Machine enetring username and password on a http website - 
![Screenshot (163)](https://user-images.githubusercontent.com/106810794/198947868-cdbe36c3-a36e-4679-bf71-34d5b77886ee.png)

Attacker are able to see victime machine actions here - 


