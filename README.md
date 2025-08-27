# THM-WireShark
This will be my process with the WireShark module in Try Hack me.


**1. Read the "capture file comments". What is the flag?**

First I go to the `statistics` tab in the top, scroll down to the comments and find the flag.

<img width="414" height="147" alt="Screenshot 2025-08-26 105851" src="https://github.com/user-attachments/assets/8452a145-5e01-44f2-99f3-87314b55c5e6" />

**2. What is the total number of packets?**

In the same tab as the last question, the answer is provided under the `statistics details`

<img width="694" height="205" alt="Screenshot 2025-08-26 105859" src="https://github.com/user-attachments/assets/2ac930b8-5d97-4dc1-a18e-7d556bbfa0d1" />

**3. What is the SHA256 hash value of the capture file?**

Scrolling up in that same details tab, it shows the SHA256 hash

<img width="820" height="230" alt="Screenshot 2025-08-26 110238" src="https://github.com/user-attachments/assets/0234df7c-9921-43d4-8599-1c3e856d263b" />

**4. View packet number 38. Which markup language is used under the HTTP protocol?**

First I select packet 38, then looking at the sections I see Extensible Markup Language below HTTP.

<img width="426" height="200" alt="Screenshot 2025-08-26 111229" src="https://github.com/user-attachments/assets/dbb90c32-f0ee-4626-b844-42476c801936" />

**5. What is the arrival date of the packet? (Answer format: Month/Day/Year)**

In the same packet, I expanded the `frame` tab and saw the answer there.

<img width="804" height="138" alt="Screenshot 2025-08-26 133341" src="https://github.com/user-attachments/assets/c4e1374a-18b0-4574-9799-7aa6d7b8f911" />

**6.What is the TTL value?**

I expanded the `internet protocal` tab and found the answer below.

<img width="868" height="259" alt="Screenshot 2025-08-26 133548" src="https://github.com/user-attachments/assets/9ca95050-84f1-4a00-9317-a0acf3521905" />



























































