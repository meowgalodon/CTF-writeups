# where are the robots - **picoCTF**


Points: 100


# **Problem Statement**


Can you find the robots                         https://jupiter.challenges.picoctf.org/problem/56830/ (link) or http://jupiter.challenges.picoctf.org:56830



# **Hints :bulb:**


What part of the website could tell you where the creator doesn't want you to look?


# **Solutions** 

Once we open the link, we are greeted with a seemingly basic website. The title of the problem suggests to look for a robots.txt file. A robots.txt file is a text file that blocks automatic web robots from running. A common mistake people make is they put secret information in files listed in the robots.txt file. When we look for this file by going to 
https://jupiter.challenges.picoctf.org/problem/56830/robots.txt, we see this list:

User-agent: *

Disallow: /1bb4c.html


By going to https://jupiter.challenges.picoctf.org/problem/56830/1bb4c.html, we finally see the flag.

# **Flag** 🚩


picoCTF{ca1cu1at1ng_Mach1n3s_1bb4c}


          
