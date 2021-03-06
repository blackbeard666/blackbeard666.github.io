## About me

![](top1_boi.png)
#### CTFtime points can be used for bragging rights, right? Here's me holding the top 1 position in the Philippines for 2020. Despite knowing that hackstreetboys (the real top CTF team in PH) will reclaim their rightful spot for 2021, I will continue to learn and improve my skillset and maybe defend the spot in the process of doing so. 

#### I'm just a student deeply interested in cybersec, especially on the fields of binary exploitation, exploit development, and anything malware related. If I get versed with pwn and reversing, I will apply what I've learned to conduct research regarding exploitation on the Android platform. Still getting started on the field tho, but will fearlessly continue to learn and grow. Aiming to be one of the top tier hackers within and representing the Philippines. *About will be updated sooner or later*

### Progress Logs
#### Since I stopped playing ctfs for a year (laptop broke rip) and only as of mid August that I got a new hand-me-down old model chromebook, I wanted to start learning exploit development seriously this time (even with school kinda being annoying). Thus, I began to set a goal that I do something exploit dev/pwning related everyday and make sure to document what I did. 
 - Sept 01, 2020: `Successfully finished memory corruption labs`
 - Sept 02, 2020: `Finished basic bof + shellcode challenge, stuck at shellcode lab2B`
 - Sept 03, 2020: `Finally wrote working open,read,write shellcode. Process = write shellcode, debug, rewrite shellcode`
 - Sept 04, 2020: `Failed to do something, sorry self`
 - Sept 05, 2020: `Done with shellcode lab :) learned how to create custom shellcode, but still needs improvement`
 - Sept 06, 2020: `Finished format string lecture problems, learned how to do multiple writes with format string vulns, got shell in fmt_lec04. Now have a better understanding on fmt str exploits.`
 - Sept 07, 2020: `Solved lab4C (read strings from stack using fmtstr exploit); partial solve for lab4B`
 - Sept 08, 2020: `Solved lab4B, but not satisfied. Find a way to execute exploit outside gdb`
 - Sept 09, 2020: `found and triggered vulnerability on lab4A, got stuck with figuring out how many bytes are written, came up with an exploit plan but failed to do so. Peeked at a writeup and saw similar plan (maybe consider this a partial solve?)`
 - Sept 10, 2020: `Played around with rop lecture binaries, couldn't do anything because of canaries`
 - Sept 11, 2020: `Got shell with lab5C, simple ret2libc. Partial solve for lab5B (was able to execute /bin/dash but sigabrts prematurely)`
 - Sept 12, 2020: `Productive day, solved baby pwn from csaw quals + 1st python sandbox escape, baby rev from flareon`
 - Sept 13, 2020: `Reverse engineered prehistoric mario chall from ALLESCTF, wrote a bruteforce script for correct box values. Will begin writeups for solved CSAW quals challenges`
 - Sept 14, 2020: `Began initial analysis of RPISEC project 1 binary, tw33tchainz`
 - Sept 15, 2020: `Was able to reverse engineer the custom hash function in order to retrieve secret pass to verify as admin. Enabled debug mode and triggered format string vulnerability in print_menu()`
 - Sept 16, 2020: `Restructured code to connect gdb with running process. Also fixed code to set debug mode on for the challenge. Found a way to hijack control flow. Changed exit@got address to 0x1337 as a test, then entered exit functionality resulted in segfault invalid address 0x1337 :)`
 - Sept 17, 2020: `Popped a shell for project1 :) Format string multiple writes to overwrite exit got to stack then execute shellcode from there. Fucking satisfying.`
 - Sept 18, 2020: `Rootcon CTF quals started, focused on pwn chall only, but got stuck.`
 - Sept 19, 2020: `Continued attempt on previous work but to no avail. Get a glimpse of how hard rootcon ctf is and promise to self to come back stronger for next year. Aside from that, solved three challs (2 pwn/1 rev) from downunder ctf. Continuing to work on chall #3`
 - Sept 20, 2020: `Solved return to revenge chall from DownUnder ctf, learned to bypass baby seccomp`
 - Sept 21, 2020: `Published writeups for solved downunder ctf challenges. Analyzed exploit for revenge chall and echo server`
 - Sept 22, 2020: `Found and triggered vulnerabilities for lab6C. Had to peek at a writeup to know that I needed a partial overwrite to solve the chall (I overcomplicated reversing it and trying to think of the solution when in fact it was that simple)`
 - Sept 23, 2020: `Reversed lab6B, found continuous memory read in hash_pass - can overwrite attempts,results variables. Haven't found a way to exploit it yet. Read some self improvement articles from azerialabs to have motivation/to learn a better learning process`
 - Sept 24, 2020: `Skipped lab6B, stack isn't the same witht the writeups I read i dunno why. It doesn't let me leak the return address, only until the attempts and results variable. Worked on lab6A instead, where I identified the vuln quickly and got it to segfault. Was able to redirect code flow by partial overwrite but no plan from that point. Also started learning how to use git, made my first commit through command line today.`
 - Sept 25, 2020: `Another productive day, solved a lot of challenges from EKOPARTY, then some from darkCTF. Will continue playing as there are 11 ctfs this weekend`
 - Sept 26-27, 2020: `Got pretty busy with ctfs, 11 ctfs in 2 days. Focused mostly on EKOPARTY which I placed 92nd and some Bsides Boston`
 - Sept 28, 2020: `Created writeups for solved challenges, tried to solve DarkCTF pwnables which I haven't got the chance to solve`
 - Sept 29, 2020: `Started learning about SIGROP`
 - Sept 30, 2020: `Understood how to bypass aslr. Created a discord bot to assign a role when a certain emoji is reacted`

## October
 - Oct 1, 2020: `Started learning about heap exploitation, solved my first uaf :)`
 - Oct 2, 2020: `Played around and solved lab7C, but still need to understand heap memory deeper`
 - Oct 3-4, 2020: `Joined in the b01lers bootcamp CTF to test what I learned about memory corruption the past month; satisfied with the results, placed 92nd/500+ teams`
 - Oct 5, 2020: `Created writeups for solved challenges.`
 - Oct 6-7, 2020: `Started reading on heap internals`
 - Oct 8, 2020: `Not much, focused on finishing schoolworks. Reread heap internal articles`
 - Oct 9, 2020: `Solved the stack canary chall from b01lers. Continued reading on heap internals, beginning to understand something somehow`
 - Oct 10-11, 2020: `Focused on playing DamCTF, though I only solved the easy ones.`
 - Oct 12, 2020: `Currently experimenting on what bin freed chunks go to. Results differ from articles I have read, which confuses me. Will read some more and continue tomorrow.`
 - Oct 13, 2020: `I think I finally understand which bins chunks go when they are freed. I'll read some more then start learning how to actually do exploits.`
 - Oct 14, 2020: `Realized some of the articles I read aren't applicable since the glibc version on my device is the one with tcache implemented; so instead of going to their respective bins immediately, chunks are being placed into the tcache bin. Found out after debugging a fastbin technique.`
 - Oct 15-16, 2020: `Got pretty busy with schoolworks didn't have time to learn pwn :(((`
 - Oct 17, 2020: `Focusing on hacktober ctf. Attempted to play the pwn challenge from N1CTF with had the highest amount of solves, it was a heap challenge which I managed to segfault using UAF, but still figuring out the next step/s.`
 - Oct 18, 2020: `Disappointed and feel I wasted my time on hacktober ctf (challs were very guessy asf). Will continue learning heap later tonight.`
 - Oct 19, 2020: `Began installing the needed tools to debug heap challs (pwninit, rust)`
 - Oct 20, 2020: `Successfully installed the needed tools and dependencies, time to start learning heap hacking.`
 - Oct 21, 2020: `Played some syskronCTF challs`
 - Oct 22, 2020: `Figured out how to debug with ld_preload and with the right ld patched into the binary`
 - Oct 23-31, 2020: `Participated in quite a lot of ctfs that happened during this time period. Details to come later.`

## November
 - Nov 1, 2020: `Played in CyberyoddhaCTF and NACTF, solved a lot of challs which are pretty good as an indicator of my current knowledge`
 - Nov 2, 2020: `Solved four android reversing challs from MOBISEC`
 - Nov 3, 2020: `Took a step back in order to reorganize my thoughts`
 - Nov 4-5, 2020: `Attempted to try cttt again but failed. Created writeups for solved NACTF tasks`
 - Nov 6, 2020: `Did a run down of the writeups for the heap challenges from NACTF posted by other people, will begin analysis tomorrow. Started watching heap lecture from pwncollege`
 - Nov 7-8, 2020: `Participated and solved challenges in Sunshine CTF instead of learning heap and doing schoolwork`
 - Nov 9, 2020: `Beginning to have an understanding of the tcache poison technique after reading writeups of NACTF's covid tracker challenge. Writeup to come later.`
 - Nov 10, 2020: `Was able to pop a shell after following HK's writeup. Still have questions regarding on how editing/controlling the fd pointer affects the exploit and how to piece it all together. Might need to reread malloc internals again.`
 - Nov 11-12, 2020: `Continuing analysis for the tcache poison exploit after doing midterms requirements. Still getting clarification on how the exploit works. Learned about __free/__malloc hooks.`
 - Nov 13, 2020: `I FINALLY UNDERSTOOD WHAT'S HAPPENING WITH THE EXPLOIT. EVEN CHANGED THE ORIGINAL CODE TO MAKE IT MUCH BETTER`
 - Nov 14-17, 2020: `Focused on midterms`
 - Nov 18, 2020: `Temporarily done with some midterm exams. Had the time to finish my cttt writeup and do readings on SIGROP exploits`
 - Nov 19-22, 2020: `Finished my mf midterms. Got time to create a sigrop mini writeup + solve two challs from pwnable.tw`
 - Nov 23, 2020: `Added new stuff to my discord bot code. Did a preliminary reverse engineering and created the exploit utilities needed to solve the heap challenge from Bsides Delhi 2020.`
 - Nov 24, 2020: `Studied the exploit for the heap challenge from Bsides Delhi, learned new info regarding libc leaks using the unsorted bin and exploiting double frees. Attempting to reverse hacknote from pwnable.tw`
 - Nov 25-26, 2020: `Experimented with htb academy and tryhackme. Finished 4 modules from academy, was able to hack the invite code to join the main platform`
 - Nov 27, 2020: `Finished some modules from tryhackme and hackthebox academy again. Breezed through the babyheap challs from pwn.college, will continue learning from there and solve all heap assignments.`
 - Nov 28-30, 2020: `Played in the InterIUT CTF with r3dact0r, I wiped the board for the android reversing challs. Got to play with new android reversing tools, excited to use them more often.`

## December
 - December 1, 2020: `Got experience with reversing an android application that uses dynamic code loading. Will attempt to do something related to heap exploitation for every day during this month.`
 - December 2, 2020: `Finished watching the dynamic allocator misuse lecture from pwn college, cleared some questions I had about how the allocator works. Finally properly understood how editing the fd pointer helps in certain exploit scenarios. Solved level 5 heap by controlling fd pointers to bypass authentication.`
 - December 3, 2020: `Solved level6&7 babyheap. Idea was to control the fd pointer of the tcache_chunk[1] so that we can control the pointer value of tcache_chunk[0] thus having the ability to control what the allocator returns to us when we malloc memory`
 - December 4-5: `Mainly focused on days 3 and 4 of the tryhackme advent challenges + some rooms`
 - December 6-31: `CTF galore, tryhackme grind (advent of cyber + some rooms), rushed 1 month worth of due assignments in 5 days. Fun times.`

## January
 - January 1, 2021: `Powerwashed my laptop and reinstalled the tools I need for my ctf setup.`
 - January 2, 2021: `Solved both android challenges from GRIMMCON 2020. After creating writeups, I will attempt to solve the waf (heap) challenge from the same ctf.`
 - January 3, 2021: `Got frida-gadget to work on a device without root. Time to learn android hacking with frida :) Also tried doing one of the fastbin challenges from nightmare, got to play with heap consolidation but will need to study about it more.`
 - January 4, 2021: `Beginning to understand some heap consolidation + chunk metadata stuff. Heap overflows are a powerful primitive to have for heap grooming. TIL that the dup in fastbin dup/tcache dup means duplication.`
 - January 5 - 11, 2021: `Continuous lapse of judgement + experimented with some android re challs`
 - January 12, 2021: `Finally beginning to realize how powerful the poison null byte -> overlapping chunks technique is for heap exploitation.`
 - January 13 - 17, 2021: `Did absolutely nothing then promised myself I would be productive for the rest of the year.`
 - January 18, 2021: `Began doing my final requirements for the first sem first, then did the hacker methodology room from tryhackme.`
 - January 19, 2021: `Finished some of the hardest requirements, had the time to study and do some xss attacks on the owasp room.`
 - January 20, 2021: `4 requirements left to do. Completed the basic pentesting room and learned how to use hydra for brute force attacks.`
 - January 21, 2021: `2 reqs left, maybe 3 if another one gets added tomorrow. Completed the root me room from tryhackme, got to refresh what I learned for file upload vulns and basic privesc. Made some progress with the fetusheap chall.`
 - January 22, 2021: `1 left (or 2 if another requirement gets added). Got user and root flags for the bounty hunter room on thm - was pretty straightforward. I enjoyed the privesc part even if it was easy. Watched motivational + self-discipline videos`
 - January 23, 2021: `Finally finished all of my requirements. Time to start learning hacking again. Day 1 of reading malloc source code until I get decent with my understanding of the dynamic allocator internals.`
 - January 24, 2021: `Did some rooms on tryhackme (networking + lazy admin) was pretty fun to read the exploit details from searchsploit to solve the box, solved the oauth challenge from hacker101 ctf`
 - January 25, 2021: `Completed the ff rooms on tryhackme: Ohsint, Brooklyn99, and BruteIt. They were fairly easy. Did a simple sigrop on 0x41414141 ctf. Other pwn are hard ngl`
 - January 26, 2021: `First time exploiting a vulnerable cronjob on tryhackme, was pretty fun. Worked on some guessy ctf challs (shadowctf), will work on the pwn from 0x41414141 later after class.`
 - January 27, 2021: `Our place had an 8-hour brownout, but I saved a heap challenge to practice beforehand. Pwned the baby heap from fireshellctf 2019 and got to play with tcache poisons a little bit more. I should probably make it a habit to check .bss variables. Got the user flag for the gamingserver room on thm but couldn't escalate privs since I couldn't download files on the free attackbox.`
 - January 28, 2021: `Did the LianYu room on tryhackme, needed some help with the stego enumeration but handled the privesc pretty easily. Solved my first baby android pwn + did some app dev challenges`
 - January 29, 2021: `Lazy day on tryhackme today, only finished the previous rooms that I have not completed due to the attack box expiring (day 24 of the adventofcode2020, last 2 flags for the blue box). Created a content hijacking poc for an android app to get the flag which I'm pretty happy about :)`
 - January 30, 2021: `Learned aboth path variable manipulation on the kenobi box THEN HAD MY FIRST HEAP CHALLENGE SOLVE ON A LIVE CTF (0x41414141 CTF) I'M ON A ROLL LETS FUCKING GO`
 - January 31, 2021: `Exploited a vulnerable icecast server and used mimikatz for post exploit stuff on the Ice room. Did a speedrun on the linux basic rooms (1 and 2, will do 3 tomorrow). Analyzed the exploits for the challenges I have not solved in 0x41414141 ctf. I'm having a good 2021 start :)`

## February
 - February 1, 2021: `Wasn't able to do much on tryhackme today, simply because my exploit doesn't seem to work. For day 1 of learning heap everyday until I get better, I learned about the safe-linking mitigation in glibc 2.32 and how to bypass it. I will still need more readings on it.`
 - February 2, 2021: `Woke up early to do some tryhackme then rooted the tomghost box, using a file read vuln on tomcat and privesc using zip. Wasn't able to do much heap stuff because of some events. Created writeups for some challenges in our discord server`
 - February 3, 2021: `Rooted the startup box on tryhackme. Had no problem uploading and getting a reverse shell but needed some help on the enumeration to get the user and root flags. Learned how to use python http server to transfer files. Practiced the data bank heap chall from bsidesdelhi '18, beginning to get familiar with tcache poisoning. Analyzed an exploit and learned a techinique on restructuring the GOT`
 - February 4, 2021: `Ez finish on the bolt box, halfway done with the crack the hashes challenge. No pwn today, but I prepared some challenges to do tomorrow. Tried learning crypto, ended up regretting it after being stuck on the math needed.`
 - February 5, 2021: `Bruteforced a wp-admin login form to upload a reverse shell, get user and easily privesc on the coldbox machine. Reading writeups to learn better approaches. Began reversing + installed tools to find bugs on [REDACTED] target`
 - February 6, 2021: `Finished the chillhack and source boxes on tryhackme, but will still need to review writeups for better approaches. Solved some challs from trollcat, proud that I solved the heap pwn chall. I'm starting to get the hang of tcache poisoning, need to learn more.`
 - February 7, 2021: `Rooted the chocolatefactory box using command injection + vi privesc. Found a possible vuln on a target I'm researching, but still trying to find a way to exploit it.`
 - February 8, 2021: `I hate that I spent my time doing a stegano box (madness room), I should do boxes without steg involved. Played with a fastbin attack similar to tcache poisoning. Discovered a new approach by overwriting got entries (free@plt -> system@libc) instead of the usual __free_hook. `
 - February 9, 2021: `Finished the allinone box + learned about insecure desiralization on the owasp top 10 room. I feel like I can't properly learn with the free attackbox since of the time constraint I end up rushing things and reading writeups to solve boxes (allinone). Was able to start an exported activity on the target I'm researching, but still no clue how to exploit it. No heap today :( i should probably stay off social media to be productive during the day`.
 - February 10, 2021: `Did the easy LFI box + finally finished the owasp top 10 room. Good stuff, need to learn more and implement solves on ctfs. Practiced the t-express challenge from samsungctf 2020. Got to leak some heap values but it turns out I missed some bugs. I only noticed the uaf but there also was an overflow + negative index access. Need to get better at it.`
 - February 11, 2021: `Didn't learn much from the fowsniff + malware researching room. Followed along faith's writeup on the ghostdiary heap pwn, learned a pretty neat technique which involves heap overflows to create overlapping chunks and creating a fake chunk within an allocated chunk.`
 - February 12, 2021: `Tried the neat base64 trick to transfer files to complete the agent sudo and the crypto101 rooms. Reviewed the security checks in the unlink macro for the heap allocator before heading out to celebrate the lunar new year`
 - February 13, 2021: `Did some misc rooms on tryhackme. Practiced the zero to hero challenge, need more training on exploiting with the poison null byte. Spent the rest of the day trying to do a heap chall from otau but struggle with setting up the heap. Need to learn more on proper heap fengshui`
 - February 14, 2021: `Ez finish on the wgel box. Started enumerating the inferno box, will continue the initial exploit tomorrow since my free attackbox has expired.`
 - February 15, 2021: `Learned how to script basic http auth bypass and got root on the inferno box. Problem is the root flag didn't contain anything in it. Will try again tomorrow. Finally got the heap consolidation + overlapping chunks to work on the heap chall from otau. I still need to study the technique more. Still couldn't complete the exploit since the program crashes when I try to allocate a poisoned chunk from the fastbin.`
 - February 16, 2021: `Redid getting root on inferno, finally got the flag. Started the alice in wonderland box, getting the initial user was pretty easy, but then my attackbox expired and I'll go at it again tomorrow. Putting aside the heap chall I still am stuck on, I just need to review the overflow exploitation part.`
 - February 17, 2021: `I wasn't able to do much again today. Finished the wonderland box, had fun with the path variable manipulation + multiple user privescs. Did some research regarding some target.`
 - February 18, 2021: `Fucking fuck I forgot to add an entry to this day. Was uneventful anyways, solved 6/7 questions on the watcher room pretty fun multiple privesc. Then spent the rest of the night studying a target`
 - February 19, 2021: `Did some challs on tenable ctf. I really need to focus on learning heap while I'm earning moeny to buy a phone to learn android pwn with`
 - February 20, 2021: `I forgot updating my logs again. Did some ctf challs from tenable + darkcon`
 - February 21, 2021: `Did overpass on tryhackme, still not done with root. User was pretty easy though. I fucking forgot to update again`
 - February 22, 2021: `Did not complete a tryhackme room for today since I accidentally shut down my attackbox connection by killing the process running on port 80. Reviewed solutions for crypto/web challs of dark con. Will analyze pwn/rev tomorrow.`
 - February 23, 2021: `Completed the year of the rabbit room, struggled a little bit with the rick roll, but getting user was pretty straightforward. Learned something new about a sudo vuln. Added crypto knowledge by attacking a reused key vulnerability on the RC4 challenge from darkcon`
 - February 24, 2021: `Easy foothold done on the mindgames room, but I needed to read some writeups for the privesc which was pretty cool using openssl engines to pop a root shell. Tried to set up a parrot os vm so that I can try to play thm and htb properly`
 - February 25, 2021: `Learned how to enumerate a simple smb share for anonymous room but it wasn't really needed. Started enumeration for the mr. robot box. Reread the poison null byte technique to understand it more and practiced the children tcache chall from hitcon '18`
 - February 26, 2021: `Continued enumerating the mr. robot room, but no progress. Did ignite instead to keep the streak. I should finish schoolwork first before focusing on hacking stuff. I hate school for this sole reason.`
 - February 27, 2021: `Fucking hate having saturday classes. Lazy day at tryhackme today, bruteforceing + enumerating open ports was quite slow. I broke something in my ubuntu chroot again, time to reinstall`
 - February 28, 2021: `Completed reinstalling a new chroot. Did an easy room on tryhackme. Currently reviewing angr scripts for future reference.`

## March
 - March 1, 2021: `Trying to create a mini ctf challenge to supplement my learning with the how2heap repo; didn't know creating ctf challs could be very tedious. Doing this to have better understanding of heap-based programs (by building then breaking them) and to brush up on my C programming since I want to work with very low-level code soon.`
 - March 2, 2021: `Did an easy tryhackme room before having classes. Gonna reinstall again since pwntools doesn't seem to work plus I think my test ctf challenge is broken. Will read malloc source in the meantime.`
 - March 3, 2021: `Learned new stuff on linux backdoors + new python privesc technique from the jpgchat room. I lack discipline. I should finish schoolworks immediately so that I can focus on learning pwn.`
 - March 4, 2021: `Worked on a guided room on tryhackme (golden eye). Figured out what went wrong on the minictf chall I created, gave it a fix then used it to learn the poison null byte technique. Now I just need to complete the double free part.`
 - March 5, 2021: `Earned the mr.robot badge for finishing the mr.robot room. Was easier than I expected but my problem was the long times it took the admin panel to load. Learned some new things (different versions of the same libc can have different protections enabled + how to debug a sigabrt) with the test ctf chall I created, will continue learning the technique until I fully understand it.`
 - March 6, 2021: `Refreshed my knowledge on python exploit techniques in the peak hill room, started the biohazard room since I had spare time. Finally fully debugged what check free() was raising then adjusted my exploit to pop a shell, it was very satisfying process.`
 - March 7, 2021: `Finished a puzzle-type ctf box (biohazard room) which was pretty good but can be guessy if you don't know what ciphers to use. I didn't do heap today, but I got to work with a shellcode technique which is pretty nice.`
 - March 8, 2021: `Learned new LFI techiniques, log poisoning from the archangel room. It was an easy privesc, I was able to identify a pathvar manipulation vuln. Didn't do heap, played a little bit of bsides sf ctf.`
 - March 9, 2021: `Did the bare minimum for tryhackme. Finally completed the fetusheap chall from OTA, which took quite a while but I learned a lot regarding fastbin techniques.`
 - March 10, 2021: `Had the chance to borrow my mom's laptop so I finished the overpass room on tryhackme using the vm i installed. Also got user on the script kiddie machine on htb but I'm struggling with privesc. Did some htb pwn, no heap today :(`
 - March 11, 2021: `Bare minimum for tryhackme, spent most of my night debugging + studying bad grades from HTB which I eventually flagged. Pretty tricky yet fun, will do a writeup later.`
 - March 12, 2021: `Finished the broker room on tryhackme, enjoyed playing around requests with burp. Preparing to solve hacknote from pwnable.tw but having problems unstripping the libc`
 - March 13, 2021: `Had fun with retracing a hacker's steps from a packet capture then redoing the needed steps to pwn the hacked machine on tryhackme. Solved a slightly tricky heap chall from nahamsec ctf which is pretty nice, I'm improving :)`
 - March 14, 2021: `Finished overpass2, similar approached with the challenge I solved yesterday. Speedrun through some of the challenges on nahamcon.`
 - March 15, 2021: `PWNED MY FIRST HACKTHEBOX MACHINE`
 - March 16, 2021: `Finally finished the overpass series with some help. Will need to go over the notes again`
 - March 17, 2021: `Cleared the easy-medium pwn challs on picoctf.`
 - March 18-23, 2021: `Procrastinated on my prelims exams and requirements. Joined and will be playing with ARESx on upcoming ctfs, but I'm still on trial period (if I'll be able to contribute, they'll let me stay)`
 - March 24, 2021: `Analyzed the stdnoerr's exploit for the killshot challenge on securinets quals, learned new stuff about tcache_perthread_struct and ROP on heap chunks (also how to use the rop functionality on pwntools).`
 - March 25, 2021: `Reviewed some SROP writeups to get more ideas, learned a new trick regarding time.sleep to not mix up payloads. Began initial analysis + writing of exploit helpers for the deathnote chall from securinets`
 - March 26, 2021: `What better way to celebrate my birthday than learning new stuff. Successfully understood the attack for the deathnote chall, easier than I expected - just a new negative index primitive which can be used to alter tcache entries stored in the tcache_perthread_struct.`