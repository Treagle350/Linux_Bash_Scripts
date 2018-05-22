# Linux_Bash_Scripts
A set of linux scripts that run various programs

## Dependencies :
```
sudo apt-get update && sudo apt-get install git build-essential autoconf automake libtool libcurl4-gnutls-dev
```
## Downloading the repository :
```
git clone https://github.com/Treagle350/Linux_Bash_Scripts.git
```
## Executing the scripts :
```
./assignment_1
./assignment_2
./assignment_3
```
## Description :
Assignment_1 is a script that copies 2 repositories from github, but checks if these folders exist on the device beforehand. 
After this the user will be asked if they want to update them or just cancel the script.

Assignment_2 is a script which copies an entire directory to a remote device using scp.
(Don't forget to change the variables to suit your application)

Assignment_3 is a script which automatically sets up ssh keys between a local device and a remote device.
(Don't forget to change the variables to suit your application)
Also passwords need to be entered when specified. 
Whenever the script stops just type "exit" in the terminal to end the ssh session with the raspberry pi and let the script continue.
