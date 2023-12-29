# 2012-National-Gallery-DC-Attack-Scenario
Our class project focused on the investigation of Tracy's iPhone for evidence that would assist the case for the theft of stamps at the National Gallery DC. Afterwards, we put our findings together into a comprehencsive report to be given to authorities.


**Table of Contents:**
Case Report: National Gallery DC
Tracy’s iPhone [2012-07-15-National-Gallery]
Table of Contents
Executive Summary
Equipment and Tools
Details of Tracy’s iPhone
Evidence to Establish Personas
Evidence relating to theft of valuable stamps
Evidence relating to defacement of museum art
Plot Timeline
Conclusion
Appendix A: Correspondence Evidence
Appendix B: WiFi and GPS Location Information

**Executive Summary**

On January 21, 2016, Digitech Inc. was called in to assist the National Gallery, Washington D.C. (NGDC) case involving a conspiracy to steal a set of valuable stamps and defacing the museum itself. 

Tracy is the primary suspect in the aforementioned heist conspiracy. 
As part of the investigation, Tracy’s iPhone was taken into custody and imaged for digital forensic purposes. 
Digitech, Inc. was tasked with investigating the forensic evidence to determine those involved as well as their culpability.

As described fully in the report, Digitech, Inc. made the following findings regarding the perpetrators' means, motive, and opportunity.

Evidence shows Tracy and her brother Pat coerced an unknown person (under codename “King”) via email - throne1966@hotmail.com to perform the heist at the National Gallery.
Tracy was motivated to initiate this conspiracy due to a lack of funds to support her daughter’s attendance at Prufrock - an expensive private school.
Tracy conspired to use her friend Carry’s flash mob as a distraction for security at the National Gallery.

**Equipment and Tools**

* Kali Linux
* Autopsy
* SQLLite Browser
* Notepad++/EditPad Pro 8
* Base64 Decoder (https://www.base64decode.org/)
* Microsoft Excel
* Google Maps
* MI Map Tools: GeoPlotter (https://mobisoftinfotech.com/tools/plot-multiple-points-on-map/)

**Details of Tracy’s iPhone**

| Name | Findings | Location in Iphone Image |
|------|----------|--------------------------|
|Model |Iphone 1,2|vol5/logs/Apple/Suipport/general.log|
|Host Name |Tracy Sumtwelve’s iPhone|vol5/logs/lockdownd.log|
|OS Version |iPhone OS 4.2.1 (8C148)|vol5/logs/AppleSupport/general.log|
|Install Time |06/06/2012 12:03:28 -0700|vol5/logs/AppleSupport/general.log|
|User Email |tracysumtwelve@gmail.com<br>coralbluetwo@hotmail.com<br>tracy.sumtwelve@nationalgallerydc.org<br>tracy.sumtwelve@nationalgallerydc.com|vol5/mobile/Library/Mail/IMAP|
|Phone Number |+1 (703) 340-9661|vol5/logs lockdownd.log.1|
|Serial Number |86004482Y7H|vol5/logs/AppleSupport/general.log|
|ICCID |89014103255195342366|vol5/logs/lockdownd.log|
|IMEI |004999010640000|vol4/usr/libexec/lockdownd.log|
|MD5 Hash|34c4888f095dc3241330462923f6fea5|N/A|
|SHA256 Hash |71aed05a86a753dec4ef4033ed7f52d6577ccb534ca0d1e83ffd27683e621607|N/A|

**Evidence to Establish Personas**
This section establishes aliases, phone numbers, emails addresses associated with each person, and relationships between each individual. 
| Tracy (Coral) | |
|---|---|
| Phone Number | +1 (703)340-9961 |
| Personal Email | tracysumtwelve@gmail.com<br>coralbluetwo@gmail.com |
| Work Email | tracy.sumtwelve@nationalgallerydc.org<br>tracy.sumtwelve@nationalgallerydc.com|
| Relationship | Accused, Pat’s sister |

| Pat (Perry) | |
|---|---|
| Phone Number | +1 (571)308-3236 |
| Personal Email | patsumtwelve@gmail.com<br>perrypatsum@yahoo.com |
| Relationship | Tracy’s brother |

| Terry | |
|---|---|
| Phone Number | +1 (703)829-6071 |
| Relationship | Tracy and Joe’s daughter |

| Joe | |
|---|---|
| Phone Number | |
| Personal Email | joe.sum.twelve@gmail.com |
| Relationship | Tracy’s ex-husband; Terry’s father |

| Carry (Cat) | |
|---|---|
| Phone Number | +1 (202)725-2124 |
| Personal Email | carrysum2012@yahoo.com |
| Relationship | Tracy’s friend; Krasnovian defacement conspirator |

| "King" | |
|---|---|
| Personal Email | throne1966@hotmail.com |
| Relationship | Robber (under duress) |

| Spam 1 | |
|---|---|
| Phone Number | +1 (206)910-0932 |
| Relationship | Spam |

| Spam 2 | |
|---|---|
| Personal Email | microsoft@reply.digitalriver.com |
| Relationship | Spam |

**Evidence relating to theft of valuable stamps**

This sub-section provides details regarding the evidence found as it relates to the theft of valuable stamps. 

Per artifact #15, Tracy decides to ask her brother Pat to help her find a new source of funds to support her daughter Terry’s attendance at Prufrock (artifacts #10; #11).

Per artifact #22, Pat blackmailed an unknown person (codename “King”) via email to perform the heist at the National Gallery.

Per artifact #26, under duress, King responded with a list of requisite materials required to perform the heist.

The following three .pdf attachments were uncovered on Tracy’s phone, each of which is a Memorandum of Insurance concerning the stolen stamps and their quoted values.

*Stamp Insurance Memorandum #1*

![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Memorandum%201.png)

*Stamp Insurance Memorandum #2*

![Memorandum 2](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Memorandum%202.png)

*Stamp Insurance Memorandum #3*

![Memorandum 3](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Memorandum%203.png "Stamp Insurance Memorandum #3")

Per image artifacts #15, #10, #16 / images of Lots #25; #26; #27 of Memorandum #1 were found on Tracy’s iPhone.

![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2025.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2026.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2027.jpg)

Per image artifacts #26, #14, #9 / images of Lots #11; #12; #13 of Memorandum #2 were found on Tracy’s iPhone.

![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2011.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2012.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%2013.jpg)

Per image artifacts #13, #24, #30 / images of Lots #1; #2; #3 of Memorandum #3 were found on Tracy’s iPhone.

![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%201.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%202.jpg)
![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Lot%203.jpg)

Total valuation of targeted stamps is $260,000, per the Memoranda of Insurance estimates.


**Evidence relating to defacement of museum art**

No evidence of defacement of art was found on Tracy’s iPhone.

**Plot Timeline**

1. Tracy needed help financially, as she could not afford her daughter’s private school anymore. (Tuesday, July 3, 2012 1:41:51 PM)
2. Tracy and Pat meet at Bubba’s Grill to plan out a way to make money (the heist) from Friday, July 6, 2012 3:02:19 PM to Friday, July 6, 2012 3:18:50 PM
3. Pat sends blackmail to ‘King’ to coerce his participation in their heist conspiracy on Friday, July 6, 2012 11:49:31 AM.
4. “King” replies to Pat confirming his participation, along with a list of materials that will be needed in order for them to complete the heist on Tuesday, July 10, 2012    11:19:00 AM.
5. Pat forwards the list to Tracy, who agrees to acquire the requested  items for the heist on Tuesday, July 10, 2012 3:58:04 PM
6. Tracy then corresponds with Krasnovian connected Carry (Cat) to set up an in person meeting, to discuss a distracting flashmob on Wednesday, July 11, 2012 12:41:45 PM


**Conclusion**

Evidence found on Tracy’s iPhone indicated the following: 

* Tracy needed the money as per her texts with her daughter, she could no longer face the financial burden of sending her daughter to a private school Prufrock.
* Tracy (alias Coral) and her brother Pat (alias Perry) use alternative email addresses to prepare and coordinate a heist to resolve their money problem.
* Based on GPS geolocation data, the planning of the heist primarily occurred in Arlington, Green Valley, and Seminary Hill in Virginia.
* Tracy and Pat blackmailed an unknown person code named ‘King’ into doing the heist, by threatening to tell his or her parole officer of his use, sale, and possession of    drugs.
* King sent Pat a list of materials needed in order to complete the heist.
* Pat then forwarded the list of materials needed to Tracy (Coral), who agreed to acquire the necessary items.
* Tracy sets up a meeting with Carry in order to discuss plans for a flashmob to distract the museum’s security for the heist.
* Joe, Tracy’s ex-husband, discovers the plot through a keylogger on Tracy’s phone and turns the conspiracy over to the police.

**Appendix A: Correspondence Evidence**

|Artifact #| Timestamp | Header Infromation | Key Infromation | Evidence Location |
|---|---|---|---|---|
| 1 | Tuesday, June 12, 2012 9:25:04 PM |+1 (571)308-3236 | “What are you up to this weekend?” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db|
| 2 | Tuesday, June 12, 2012 8:04:50 PM |+1 (650)887-0260 | Phone Call from Unknown Number |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db |
| 3 | Tuesday, June 12, 2012 8:52:14 PM  |+1 (703)829-6191 | Phone Call from Unknown Number | /img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db|
| 4 | Wednesday, June 13th, 20124:29:13 PM |+1 (571)308-3236 | Phone Call to Pat |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db|
| 5 | Wednesday, June 13, 2012 5:30:28 PM |+1 (703)829-6071 | “I’m going out with dad after school for pizza! Thought I’d let you know if you planned to cook.”  |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db|
| 6 | Wednesday, June 13, 2012 6:30:38 PM |+1 (571)308-3236 | “I don’t have any big plans. How about you?” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 7 | Wednesday, June 13, 2012 6:33:46 PM |+1 (703)829-6071 | “Ok sounds good.” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 8 | Tuesday, June 19, 20122:38:59 PM | Email<br>From: perrypatsum@yahoo.com<br>To: coralbluetwo@hotmail.com<br>Subject: Crazydave by the VMs<br>Attachment: Crazydave1.mp3|“Hey Coral,<br>Just got your email. That took longer than expected! Oh well! You’ve got to check out this new song by the VMs. I love the base. Tell me what you think!”|/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/3896FC6F-A083-4D39-B0A2-CE68368D44CA.emlx |
| 9 | Friday, June 22, 2012 5:34:26 PM |+1 (571)245-8517 | Phone Call to Unknown Number |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db |
| 10 | Tuesday, July 3, 2012 1:41:51 PM |+1 (703)829-6071| “Hey honey. I’m not sure if we can afford Prufrock anymore… What do you think about maybe switching to someplace else?” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 11 | Tuesday, July 3, 2012 2:04:32 PM |+1 (703)829-6071 | “moving schools at this point would be the worst! i would rather live with dad and stay at prufrock then change schools :(” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 12 | Thursday, July 5, 2012 6:18:23 PM |+1 (202)725-2124 | “Sounds good let’s shoot for one at Bubba s grill” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 13 | Thursday, July 5, 2012 6:20:26 PM |+1 (202)725-2124 | “Okay that sounds great. See you there” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 14 | Thursday, July 5, 201212:58:41 PM |Email<br>To: Woina.Honril@m57.biz<br>From: coralbluetwo@hotmail.com<br>Subject:<br>Attachments: 000001.doc; 000002.doc| “I didn’t” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/F3F4EB95-52EB-42FC-9279-46DAB24B6E34.emlx |
| 15 | Thursday, July 5, 2012 4:57:32 PM | Notes app | “You need to find help for Prufrock” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Notes/notes.sqlite |
| 16 | Friday, July 6, 2012 3:02:19 PM |+1 (571)308-3236 | “Hey can you give me a call” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 17 | Friday, July 6, 2012 3:08:37 PM |+1 (571)308-3236 | “Sis I’m really busy can we do this later” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 18 | Friday, July 6, 2012 3:11:54 PM |+1 (571)308-3236 | “No pat this is important I need you to call me soon” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 19 | Friday, July 6, 2012 3:13:31 PM |+1 (571)308-3236 | “Ok ok I’ll call in 5” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 20 | Friday, July 6, 2012 3:18:50 PM |+1 (571)308-3236 | Phone Call to Pat |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 21 | Friday, July 6, 2012 4:27:16 PM |+1 (202)725-2124 | “I have a table inside” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db |
| 22 | Friday, July 6, 2012 11:49:31 AM |Email<br>To: throne1966@hotmail.com<br>From: patsumtwelve@gmail.com<br>Subject: can’t pass up|“King,<br>Long time no see. I have a juicy proposition for you. Two weeks from now, me and my associates are planning a heist at the national gallery. Although, we need a helping hand. I know that you are on parole right now and are probably hesitant to participate. Me and your parole officer go years back. He is a very strict fellow. If he were to find out that you were dealing drugs and shooting dope in your veins every night, I feel he wouldn’t be too happy. It’s very easy for a person to phone the feds an anonymous tip that you are on drugs and the location of your stash. All they have to do is give you a drugs test and since you’re on parole, the feds don’t need a search warrant. Well hit me up. You know where to find me.”|/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/9F0508B8-04FB-490E-A7F0-3E23B0E7C59B.emlx |
| 23 | Friday, July 6, 2012 4:27:50 PM |+1 (202)725-2124 | “Okay brt” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db |
| 24 | Saturday, July 7, 2012 7:36:35 PM |+1 (206)910-0932 | “Congratulations, your entry in last months drawing won you a FREE $1,000 Target Giftcard! Enter “703” at www.target.com.trdt.biz to tell us where to ship it”  |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/wireless/Library/CallHistory/call_history.db |
| 25 | Monday, July 9 2012 10:44:11 AM | Email<br>To: coralbluetwo@gmail.com<br>From: tracysumtwelve@gmail.com<br>Subject: things<br>Attachments:| “Somethings” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/8A3BD06F-CDB1-4453-9C69-77E06823F2AE.emlx |
| 26 | Tuesday, July 10, 201211:19:00 AM |Email<br>To: patsumtwelve@gmail.com<br>From: throne1966@hotmail.com<br>Subject: RE: can’t pass up<br>Attachment: needs.txt|“You’re too kind… I got you brotha. I need some tools in order to do this job for you. Here are some requirements that I will need:<br><br>See attachment”<br><br>Attachment: needs.txt<br>“-A rope and javelin (using alternative means to break in)<br><br>-tactical turtlenecks ( what i will be wearing)<br><br>-spray paint (for the cameras)<br><br>-vibram five finger shoes (in order to walk silently)<br><br>-pack of smokes (detecting lasers)<br><br>-smoke grenades (use as a means of escape if caught)”|/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/9F0508B8-04FB-490E-A7F0-3E23B0E7C59B.emlx |
| 27 | Tuesday, July 10, 2012 3:26:19 PM |+1 (571)308-3236 | “hey sis yo friend coral got a email the attachment needs to be changed to pdf let her know” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 28 | Tuesday, July 10, 2012 3:58:04 PM |+1 (571)308-3236 | “Sure thing I’ll get on it” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 29 | Tuesday, July 10, 2012 5:18:38 PM |+1 (703)829-6071 | “Going to lunch. You want to go????!” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 30 | Tuesday, July 10, 2012 6:19:24 PM |+1 (703)829-6071 | “Back at work” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 31 | Tuesday, July 10, 2012 6:58:24 PM |+1 (703)829-6071 | “I’m busy. Maybe this weekend if dad isn’t busy” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 32 | Wednesday, July 11, 2012 4:18:03 AM |Email<br>To: coralbluetwo@hotmail.com<br>From: microsoft@reply.digitalriver.com<br>Subject: Only 30 days left! Start a free Office training course now|“You're halfway through your trial.<br>Increase your productivity at home and work with free Office training.<br><br>Days remaining in your Office 2010 trial: 30<br><br>Become an Office expert.<br><br>Our quick Office training courses help you make home and work tasks more efficient and effective. Learn how to move through<br>Word, Excel, PowerPoint, One Note and Excel like a pro and spendless time at your computer.<br><br>Start a free training course on Office.com.  <br><br>You can train online instantly or download a course to try later.<br><br>Buy Now: http://email.trymicrosoftoffice.com/ct/3093310:831136289:m:3:149047358:F19A8AE722B3382646FB84B7C7BE03E0:r<br><br>See for yourself.<br><br>Watch our short videos to learn even more.<br><br>Watch Now:<br>http://email.trymicrosoftoffice.com/ct/3093313:831136289:m:3:149047358:F19A8AE722B3382646FB84B7C7BE03E0:r”  |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/Mail/POP-coralbluetwo@hotmail.com@pop3.live.com/INBOX.mbox/Messages/01FE9965-A923-40CF-A78A-72CE3BD26571.emlx |
| 33 | Wednesday, July 11, 2012 12:41:45 PM |+1 (202)725-2124 | “I’m almost there where should I meet you?” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 34 | Wednesday, July 11, 2012 12:49:08 PM |+1 (202)725-2124 | “Just meet me out front, I’ll take the tablet in.” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 35 | Thursday, July 12, 2012 5:06:45 PM |+1 (202)725-2124 | “How’s the flashmob going” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |
| 36 | Friday, July 13, 2012 1:02:10 AM |+1 (703)829-6071 | “I really want to go to Dad’s this weekend. He said he’ll take me shopping for school” |/img_tracy-phone-2012-07-15-final.E01/vol_vol5/mobile/Library/SMS/sms.db |

*Image appendix coming*

**Appendix B: WiFi and GPS Location Information**

![Alt](https://github.com/c-asonye/IPhone-Digital-Forensics/blob/main/images/Wifi%20And%20GPS%20Locations.jpg)
Latitude and Longitude coordinates were assembled from consolidated.db and Lat_Lon.csv. The compilation of the data can be found withing the repository
