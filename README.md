# Cybersecurity-lab1

My mission is to test a sample blog for potential security vulnerabilities by performing a brute force attack.
I used Burp's Intruder tool to complete this task.

### First, I attempt to login with a random username and password

### Finding the username
Secondly, I use a sniper attack to find the username of a registered user on the site.
3104, the length that differs the most, is the field with a successful username. The username is 'agenda'.

### Attempting to login as a user by conducting a brute force attack with simple passwords
Now that I found a registered user, I want to attempt to login as that user with dozens of simple passwords.

![Sniper Attack to find username](https://github.com/Lanelle1398/Cybersecurity-assignments/blob/main/Screen%20Shot%202021-08-23%20at%2011.02.29%20PM.png?raw=true)

Notice that each request returned a 200 status code, until eventually one returned 302. This suggests that the login attempt was successful. The password is 'access'.

### Results

<img src="https://github.com/Lanelle1398/Cybersecurity-assignments/blob/main/Screen%20Shot%202021-08-23%20at%2010.59.01%20PM.png?raw=true" width="650" height="350" />

Disclaimer: This project was perfomed on a practice blog that PortSwigger Academy provided to help individuals learn cybersecurity.  All cybersecurity strategies utilized here were performed in compliance with the CFAA and local computer security laws.
