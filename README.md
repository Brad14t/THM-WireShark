# THM-WireShark & Nmap

This will be my process with the Try Hack Me `WireShark: The Basics, WireShark: Packet Operations, and WireShark: Traffic Analysis`


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

**6. What is the TTL value?**

I expanded the `internet protocal` tab and found the answer below.

<img width="868" height="259" alt="Screenshot 2025-08-26 133548" src="https://github.com/user-attachments/assets/9ca95050-84f1-4a00-9317-a0acf3521905" />

**7. What is the TCP payload size?**

First I opened the TCP drop down and scrolled down.

<img width="412" height="116" alt="Screenshot 2025-08-27 094857" src="https://github.com/user-attachments/assets/68f7919d-9b9c-44b3-8b9d-c17415b0b436" />

**8. What is the e-tag value? (For example: 82ecb-6321-9e904585)**

To find this I expanded the HTTP drop down and the answer was there.

<img width="464" height="165" alt="Screenshot 2025-08-27 095445" src="https://github.com/user-attachments/assets/26c18232-e5b5-4e74-9790-d5c06d0ad30a" />

**9. Search the "r4w" string in packet details. What is the name of artist 1?**

First I ctrl + f and search `r4w` then double click the first result. 

<img width="1298" height="101" alt="Screenshot 2025-08-27 104127" src="https://github.com/user-attachments/assets/f223da91-1a07-4b90-b813-893bcf7e578f" />

Then I scrolled through line based text and found the answer there.

<img width="1038" height="247" alt="Screenshot 2025-08-27 104113" src="https://github.com/user-attachments/assets/2d6a1e6e-b057-4686-ad4c-942a25d56878" />

**10. Go to packet 12 and read the packet comments. What is the answer? Note: use md5sum <filename> terminal command to get MD5 hash**

First I go to packet 12 and see there is a comment, taking me somewhere else.

<img width="1118" height="418" alt="Screenshot 2025-08-27 104615" src="https://github.com/user-attachments/assets/656e7be8-58fd-411d-ac11-58b6db179a18" />

Then I went to the packet requested, right clicked the jpeg section, then select export packet bytes.

<img width="378" height="148" alt="Screenshot 2025-08-27 105146" src="https://github.com/user-attachments/assets/d39c299a-7019-4a80-9804-4b35ce9d7040" />

Once I save the file to my desktop, I run the command `md5sum jpeg` to get the md5 hash.

<img width="1060" height="287" alt="Screenshot 2025-08-27 105637" src="https://github.com/user-attachments/assets/85f73b1a-8549-471a-83d3-26d2fc608f4d" />

Then I can open the txt file and see the answer.

<img width="287" height="330" alt="Screenshot 2025-08-27 110034" src="https://github.com/user-attachments/assets/933b9da6-8702-46eb-ae33-05bf82244407" />

<img width="591" height="279" alt="Screenshot 2025-08-27 110206" src="https://github.com/user-attachments/assets/3cde001b-df7f-46b7-8c8e-124a05d97a16" />

<img width="1444" height="223" alt="Screenshot 2025-08-27 110546" src="https://github.com/user-attachments/assets/ede37828-370e-40b3-9361-cfa73ac51fce" />

**11. Look at the expert info section. What is the number of warnings?**

I first go to the analys tab at the top and select Expert information.

<img width="529" height="600" alt="Screenshot 2025-08-27 110911" src="https://github.com/user-attachments/assets/e61ee4c7-630b-45cb-b991-65ee4c055249" />

Then I sleect warnings, and I can see the amount to the right.

<img width="1358" height="119" alt="Screenshot 2025-08-27 111043" src="https://github.com/user-attachments/assets/69379ea1-877f-4153-af2c-101aa6a73d5b" />

**12.Go to packet number 4. Right-click on the "Hypertext Transfer Protocol" and apply it as a filter. Now, look at the filter pane. What is the filter query?**

Right click packet 4and apply it as filter and I see HTTP

<img width="594" height="398" alt="Screenshot 2025-08-27 123151" src="https://github.com/user-attachments/assets/ae379c0f-216b-4141-828c-9f6efc69af5b" />

<img width="202" height="170" alt="Screenshot 2025-08-27 123316" src="https://github.com/user-attachments/assets/81e67b5f-9284-4c3b-b514-3881fe384f56" />

**13. What is the number of displayed packets?**

For this I can see the number at the bottom.

<img width="420" height="41" alt="Screenshot 2025-08-27 123629" src="https://github.com/user-attachments/assets/331d813d-ed48-4597-be72-1a0e6e4e9e41" />

**14. Go to packet number 33790, follow the HTTP stream, and look carefully at the responses. Looking at the web server's response, what is the total number of artists?**

After going to the packet and following the HTTP stream

<img width="1031" height="240" alt="Screenshot 2025-08-27 125643" src="https://github.com/user-attachments/assets/f1e17d79-2ded-4d49-afda-6b9cda031a29" />

I can search for `artist=#` and I see their are no results for artist=4 so I have 3.

<img width="1240" height="226" alt="Screenshot 2025-08-27 125705" src="https://github.com/user-attachments/assets/61493a75-e71d-4126-af76-3b259e32b0ef" />

<img width="1003" height="458" alt="Screenshot 2025-08-27 125718" src="https://github.com/user-attachments/assets/2a59963b-f9b7-4f51-b327-37ff14b1f5c6" />

**15. What is the name of the second artist?**

I can search `artist=2` and find the name next to it.

<img width="1129" height="116" alt="Screenshot 2025-08-27 130027" src="https://github.com/user-attachments/assets/8da3672d-b201-4669-ad68-003a3a59af2a" />

<img width="1089" height="416" alt="Screenshot 2025-08-27 130057" src="https://github.com/user-attachments/assets/215e335c-bd18-4058-97f8-22d232ccdf62" />

**16. Investigate the resolved addresses. What is the IP address of the hostname starts with "bbc"?**

First I selected the statistics tab then look up bbc.

<img width="360" height="116" alt="Screenshot 2025-08-27 150143" src="https://github.com/user-attachments/assets/6d217d6d-bd8b-4e0c-b355-16090297b966" />

<img width="876" height="140" alt="Screenshot 2025-08-27 150210" src="https://github.com/user-attachments/assets/fd0c51ae-7d17-4e9e-95e7-6dcc4bdcdf9c" />

**17. What is the number of IPv4 conversations?**

First in the statistics tab I opened the conversations, and see the iPv4 conversations

<img width="511" height="183" alt="Screenshot 2025-08-27 150331" src="https://github.com/user-attachments/assets/4e97a278-3ed2-402e-899c-1aef85c77987" />

<img width="763" height="117" alt="Screenshot 2025-08-27 150356" src="https://github.com/user-attachments/assets/420487e5-1cae-4fc7-9041-48972852d33b" />

**18. How many bytes (k) were transferred from the "Micro-St" MAC address?**

In the statistics tab I select endpoints, then select name resolution.

<img width="346" height="204" alt="Screenshot 2025-08-27 150916" src="https://github.com/user-attachments/assets/6b2638bf-a2af-4e02-97f5-57bc59fd6fae" />

<img width="677" height="371" alt="Screenshot 2025-08-27 151042" src="https://github.com/user-attachments/assets/045f2175-bfba-4fc4-8190-43d0d78d540f" />

**19. What is the number of IP addresses linked with "Kansas City"?**

In the same endpoints tab I select Ipv4 then sort by city.

<img width="868" height="468" alt="Screenshot 2025-08-27 151256" src="https://github.com/user-attachments/assets/a4407332-8dd0-4efe-9509-335bdbab6218" />

**20. Which IP address is linked with "Blicnet" AS Organisation?**

First thing is I searched the packets for Blicnet, double clicked the packet and saw the destination ip needed.

<img width="1081" height="92" alt="Screenshot 2025-08-27 151713" src="https://github.com/user-attachments/assets/4b1ed581-1202-4d73-bfb7-0b22007dac4d" />

<img width="1015" height="145" alt="Screenshot 2025-08-27 151702" src="https://github.com/user-attachments/assets/b191e3a6-a3f0-4f78-aafa-e8ebda215228" />

**21. What is the most used IPv4 destination address?**

First in the statistics tab, I select ipv4 then all addresses, then filter from most to least.

<img width="529" height="232" alt="Screenshot 2025-08-27 152528" src="https://github.com/user-attachments/assets/3cf24d4a-e48b-42eb-96b6-29229d767151" />

<img width="265" height="116" alt="Screenshot 2025-08-27 152533" src="https://github.com/user-attachments/assets/2f584896-c1b9-4400-b3c5-5d9f91852ac9" />

**22. What is the max service request-response time of the DNS packets?**

First I go to the statistics page and select DNS

<img width="364" height="571" alt="Screenshot 2025-08-27 152959" src="https://github.com/user-attachments/assets/2eafe152-98a2-45c3-9434-7c41782fc98e" />

Then look under the service stats

<img width="784" height="96" alt="Screenshot 2025-08-27 153135" src="https://github.com/user-attachments/assets/58d34f1d-e000-46a2-8370-7a9fbaadbe59" />

**23. What is the number of HTTP Requests accomplished by "rad[.]msn[.]com?**

First in the stats tab select HTTP then requests

<img width="412" height="81" alt="Screenshot 2025-08-27 153824" src="https://github.com/user-attachments/assets/1e6aa26a-5dbb-4857-898d-83b17dde5e49" />

Then find rad.msn.com and go to the right and see the quantity.

<img width="244" height="47" alt="Screenshot 2025-08-27 153801" src="https://github.com/user-attachments/assets/1e49cfb6-2f8b-4e2d-b7a9-e212d567bf89" />

<img width="67" height="66" alt="Screenshot 2025-08-27 153753" src="https://github.com/user-attachments/assets/4f3cde09-b215-4fa3-a71c-e2386a734e18" />

**24. What is the number of IP packets?**

I used the `ip` command and saw the number of displayed packets.

<img width="899" height="729" alt="Screenshot 2025-08-28 085005" src="https://github.com/user-attachments/assets/4b742578-6661-40f5-a509-802fa2ec8e88" />

**25. What is the number of packets with a "TTL value less than 10"?**

I used `ip.ttl < 10`

<img width="810" height="726" alt="Screenshot 2025-08-28 085205" src="https://github.com/user-attachments/assets/012c655c-99ab-4d1f-a470-2fd49984893c" />

**26. What is the number of packets which uses "TCP port 4444"?**

`tcp.port == 4444`

<img width="816" height="728" alt="Screenshot 2025-08-28 085334" src="https://github.com/user-attachments/assets/fce88e39-c13c-40d5-bef4-1d75daa3a55a" />

**27. What is the number of "HTTP GET" requests sent to port "80"?**

`http.request.method == "GET" && tcp.port == 80`

<img width="821" height="736" alt="Screenshot 2025-08-28 085946" src="https://github.com/user-attachments/assets/523229ea-94ff-43b9-8778-6989ae23f899" />

**28. What is the number of "type A DNS Queries"?**

First I start by trying to find a query, I select the analyse tab then Display filter expression.

<img width="346" height="148" alt="Screenshot 2025-08-28 090551" src="https://github.com/user-attachments/assets/6a3541f0-f340-459d-9d93-e0b6ef616a44" />

I searched dns, and scrolled through till I found `dns.qry.type` and this allows me to select only type a.

<img width="825" height="846" alt="Screenshot 2025-08-28 090643" src="https://github.com/user-attachments/assets/2bba545d-288b-4194-8848-f1ab0d64a888" />

This wont give the correct answer, I am needing responses only. So I go back and make another query, by searching dns and scrolling through the options.

I found the one I beleive is correct, it is `dns.flag.response`

<img width="823" height="831" alt="Screenshot 2025-08-28 091159" src="https://github.com/user-attachments/assets/04433b3d-5dac-4ca3-8cef-abd1b9c91fc3" />

Add both together to a full query of `dns.qry.type ==1 && dns.flag.response == 1`

<img width="1505" height="779" alt="Screenshot 2025-08-28 091419" src="https://github.com/user-attachments/assets/c9588386-1cee-4b4a-b3e1-d499b18c40ff" />

**29. Find all Microsoft IIS servers. What is the number of packets that did not originate from "port 80"?**

First I want to find all packets with Microsoft

`http.server contains "Microsoft"`, now that I have all the packets with the Microsoft server, I need a query to find the packets that dont originate from port 80.

full command I used `http.server contains "Microsoft" && tcp.srcport != 80`

<img width="1516" height="768" alt="Screenshot 2025-08-28 094432" src="https://github.com/user-attachments/assets/174d83e8-c0d2-4247-9510-19c8f946a540" />

**30. Find all Microsoft IIS servers. What is the number of packets that have "version 7.5"?**

After looking at the packets and testing queries I landed on this one.

`http.server contains "Microsoft" && http.server matches "7.5"`

<img width="1517" height="780" alt="Screenshot 2025-08-28 095349" src="https://github.com/user-attachments/assets/cfde55bc-0428-4a1f-9370-ef545fad8123" />

**31. What is the total number of packets that use ports 3333, 4444 or 9999?**

`tcp.port in {3333 4444 9999}`

<img width="1512" height="780" alt="Screenshot 2025-08-28 095650" src="https://github.com/user-attachments/assets/cb90370e-10dd-4251-bc6e-d887ae77cb44" />

**32. What is the number of packets with "even TTL numbers"?**

First thing is to translate the packets into strings, this can be done by `string(ip.ttl)`

Then I want the packets to match only even numbers by adding `matches "[02468]$"` this matches only the regex numbers of even numbers, the $ is the anchor saying it needs to end in that even number range.

<img width="1495" height="784" alt="Screenshot 2025-08-28 100511" src="https://github.com/user-attachments/assets/70262306-4749-48ed-bb42-559b57b0d4c0" />

**33. Change the profile to "Checksum Control". What is the number of "Bad TCP Checksum" packets?**

First I select edit, then configuration profiles, then select checksum control.

<img width="366" height="802" alt="Screenshot 2025-08-28 100715" src="https://github.com/user-attachments/assets/f6d305c1-ff63-42dd-b533-3659a0827e3c" />

<img width="861" height="624" alt="Screenshot 2025-08-28 100731" src="https://github.com/user-attachments/assets/97c12604-3f68-4bfe-af99-d04dab3b80fa" />

Then I craft a query by looking up `dns.checksum`

<img width="819" height="782" alt="Screenshot 2025-08-28 100939" src="https://github.com/user-attachments/assets/78bb2ec1-175b-4e89-b3e8-8f0b6e4212df" />

<img width="1381" height="778" alt="Screenshot 2025-08-28 101035" src="https://github.com/user-attachments/assets/ce7d4a63-e830-4a63-ab36-45c5f5f971c5" />

**34. Use the existing filtering button to filter the traffic. What is the number of displayed packets?**

Using the same profile config, use the existing filter gives me the answer.

<img width="963" height="394" alt="Screenshot 2025-08-28 101211" src="https://github.com/user-attachments/assets/47647a99-1f59-4a14-b28f-c06554594c1e" />

<img width="1265" height="470" alt="Screenshot 2025-08-28 101256" src="https://github.com/user-attachments/assets/71138334-5237-4e5d-bbca-6e62e9a521b0" />

# NMAP Notes

**Most common nmap scans:** `TCP connect scans, SYN scans, UDP scans`

**Below are the base filters to probe Nmap scan behaviour on the network:**

Global search - `tcp` `udp`

SYN Flag only: 

`tcp.flags == 2` - will only match packets where only the SYN flag is set and no other flags are set. This is typical of the initial SYN packet sent by a client to establish a connection. (SYN flag is the ONLY flag)

`tcp.flags.syn == 1` -  will match any packet where the SYN flag is set, regardless of the state of other flags (e.g., it would match a SYN-ACK packet where both SYN and ACK flags are set).

`tcp.flags == 16` - ACK flag is the only flag

`tcp.flags.ack == 1` - will match any packet with the ACK flag set.


