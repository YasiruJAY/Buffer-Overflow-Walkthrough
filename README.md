# Buffer-Overflow-Walkthrough
A buffer overflow exploitation on a real life software.

This document is an in-detail writeup of how to exploit a buffer overflow vulnerability in BlazeDVD player, and execute a payload that allows an attacker to gain access to the victim's root shell. 

Note: This is NOT a zero-day vulnerability. An exploit for this vulnerability (CVE-2006-6199) is already available on exploit DB (Link: https://www.exploit-db.com/exploits/26889).

This writeup explains a modified version of the exploit available in exploitDB, with every step explained in great detail.
