# CodePathWeek9

# Honeypots Deployed
#   I deployed two additional honeypots after deploying the Dionaea honeypot for the assignment.
#   These were the Shockpot honeypot and the ElasticHoney honeypot.
#   Shockpot is designed to detect and trap attempts at exploiting the Shellshock vulnerability (CVE-2014-6271)
#   ElasticHoney is, as stated on the git hub, a "simple elasticsearch honeypot designed to catch attackers exploiting RCE      vulnerabilities in elasticsearch."

# Issues
#   I didn't run into any major issues. The small issues I did have were primarily due to mistyping terminal commands as well as getting acquainted with spinning up and launching VMs from a command line. I have tiny bit of previous experience with AWS, however I did all of that through the GUI in the browser. One example was that I accidently deployed two MHN sensors on the same VM and which I then deleted and started over
#   The first time I went through the assignment, I did not record the process. I went back through the initial steps with Licecap to show the steps that I took, and I have also uploaded a screenshot from my original honeypots before I took them down.

# Summary of Data Collected
#   I let my three honeypots run from the evening of 11/16 to the morning of 11/20. After initializing the dionaea honeypot during the assignment instructions, I ran a full port scan against it using nmap. I let this run for about 20 or 30 minutes before force quitting. This stacked up about 5,500 hits. However, by the morning of 11/20, there were a total of 14,833 hits. During this time, dionaea failed to gather any malware samples.
#   Shockpot detected the second most number of hits at 28 and ElasticHoney picked up 4. 
#   The attacks came from all over the world, and sometimes at quite a high rate. By the time of shutting down the sensors, the majority of hits in the final 24 hour period came from the US, the Uk, France, and Russia.

# Unresolved Questions
#   After having finished this assignment, the questions that I have are about how these honey pots work at the level of the source code. This assignment, like many of the others, has pushed me to the limits of my knowledge, which, while an uncertain place to be, is what I seek in the exercises and challenges that I've been doing to get better at cyber security. I think having practial knowledge of deploying honeypots such as these as well as how they work at a high level is a good place to start for understanding how they work at lower levels.
