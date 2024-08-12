# WITH-Cyber

Hosted by SJSU and the WITHCyber team from CSUSB, CyberGuardians: Navigating the AI-Enhanced Future was a free summer camp that gave rising high school seniors the opportunity to delve into the realm of cybersecurity. I was truly grateful for the opportunity to be a part of this program, which helped me to explore my passion in computer science as well as to gain insight into professional careers in cybersecurity. 

In this camp, I had a lot of fun exploring the different roles in cybersecurity, ranging from cyber defense analyst, system administrator, and cyber defense forensics analyst, to secure software assessor and exploitation analyst etc. The role that interested me in particular was the cyber defense forensics analyst role. Growing up, I've always taken a liking to detective shows, and I found the process of finding clues and making deductions to be the most entertaining. To my surprise, here at the camp, I was able to do the same with the raspberry pi we were each given. In the cyber defense forensics analyst course, we were taught about **steganography**, which involved communicating in a way that hid the existence of the communication. We were then introduced to **steghide commands**, which helped with extracting and embedding files into one another. The commands for steghide involved the following:
<br/>
cf: cover file (what the hidden contents are hiding in)<br/>
ef: embed file (the hidden contents)<br/>

embedding: steghide embed -cf image.jpg -ef secret.txt -p "yourpassword"<br/>
extracting: steghide extract -sf image.jpg<br/>
  -sf: stego file(img containing hidden file)<br/>
  -xf: extract file(output file where hidden data will be saved)<br/>

We also learned about important concepts in cyersecurity, such as the **CIA triad**, which was **confidentiality, integrity, and availability**. Confidentiality meant protecting information from others, integrity meant protecting from modification, and availability meant having the information be easily accessible. Another important concept was learning about the different kinds of malware, including ransomware(blackmail), spyware(steal data), adware(spam w/ ads), worms(spread across computers), trojans(sneak malware onto PC), botnets(turn PC into a zombie),etc.
