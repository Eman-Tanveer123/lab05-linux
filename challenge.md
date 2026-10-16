## Question 1
Answer: I am student. My home folder is /home/student.
Commands: whoami, pwd

## Question 2
Answer: The server name is ubuntu-lab01, and it runs Ubuntu 24.04.3 LTS.
Commands: hostname, cat /etc/os-release

## Question 3
Answer: The server has 1.9Gi total RAM, and 4.0G free disk space.
Commands: free -h, df -h /

## Question 4
Answer: The users that can log in with /bin/bash are root and student.
Commands: grep "/bin/bash" /etc/passwd

## Question 5
Answer: There are 220 processes running right now.
Commands: ps aux | wc -l

## Question 6
Answer: lab5user was created around 06:47 and deleted shortly after during the lab exercises.
Commands: sudo grep lab5user /var/log/auth.log
