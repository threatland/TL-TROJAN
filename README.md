# TL-TROJAN #

Welcome to the TL-TROJAN repo. This collection contains source files for a
variety of Trojans.

Files in this collection have been gathered via distributed trawling of the 
internet, and deduplicated where applicable.

## Disclaimer ##

The files contained in this repo are for research purposes only. They are 
provided as-is and have no guarantee of functionality.

## What is a Trojan? ##

A Trojan is a program that infects a victim machine and gives control to an 
attacker by misleading a user into downloading it as a legitimate file. 
Modern trojans are loaded by other programs and gain persistence on the system 
allowing a malicious party to spy on the user, damage the system, steal 
sensitive information, or add the computer to a botnet.

### What is a RAT? ###

A RAT, or Remote Access Tool/Trojan, is a type of malware that gives Administrative 
control to another user, and provides a covert backdoor to the system. This 
allows the remote user to do anything from keylogging, taking screenshots, 
changing network settings, or spy on the user via their webcam or microphone.

### What is a Stealer? ###

A Stealer is a type of malware that is explicitly used to steal information from 
a user, such as bank info, logins, and other sensitive files. Stealers are typically 
a bit less sophisticated than other malware, and often times not include some of 
the more advanced persistence techiques of other malware. 

## Mitigations ##

Mitigations vary from system to system, but the core security principles apply 
to each of them. Having a good antivirus, and using proper care when downloading 
files from unknown sources will prevent a large number of attacks on users.

## Navigating the Repo ##

The repo is divided into several folders, containing specific categories of 
activity.

Zip files may have the same or similar names, so each filename contains an 
identifier based on the first 6 characters of the SHA1 hash of the file. 
The formula is:

    FILENAME.SHA1.EXTENSION

Non Zip files may contain this naming pattern as well.

## Collection Highlights ## 

There are many versions of the Azorult Stealer in TL.STEALER/TL.Azorult.

## Contributing ## 

Contributions to this repo are welcome. Simply fork this repo, open a pull 
request and consult with the repo maintainers about it. 

### Guidelines ###

- Please submit larger files (> 5 MB) as a zip file in order to make cloning this a reasonable exercise.
- Please try and follow our naming convention for zip files in order to deduplicate and identify hashes. 

Files are subject to rejection if they do not meet our guidelines.

### We will NOT accept the following ###

- Combolists
- Database dumps
- Any credentials for active sites or devices, user, admin or otherwise
