# EA-1 — Reflection
 
## Activity Description
 
For EA1, I chose to work through Module 1 of TryHackMe's
Cyber Security learning path, a self paced cybersecurity
training platform. The module consisted of three rooms: **Offensive Security Intro**,
**Defensive Security Intro**, and **Search Skills**. Each room combined short reading
sections with hands on tasks that run entirely in browser through TryHackMe's
AttackBox environment, so no local setup was required.
 
The expectation for the platform is that you work through guided scenarios using real
tools against simulated targets. In the Offensive Security Intro room, I used GoBuster
to enumerate hidden directories on a fake banking website and successfully transferred
funds to find the flag. In the Defensive Security Intro room, I worked through a SIEM
dashboard to analyze simulated event logs, identify a malicious IP address, and flag
a security incident. In Search Skills, I practiced using specialized search operators
and OSINT tools to find information that wouldn't come up in a standard Google search.
 
## Technical Decisions
 
The first decision I made was choosing TryHackMe over alternatives like HackTheBox or
picoCTF. TryHackMe made the most sense because it has guided rooms with enough
structure to actually finish something in a weekend without getting stuck for hours
on a single challenge. HackTheBox is more open ended and better suited once you already
have a foundation.
 
Within the rooms, I chose to use the browser based AttackBox rather than connecting
via OpenVPN from my own machine. This was a deliberate tradeoff. The AttackBox is
slower, but it avoided any VPN configuration overhead and let me stay focused on the
actual tasks.
 
In the Offensive Security Intro room, I had to decide how to construct the GoBuster
command correctly since the syntax wasn't fully spelled out. I took time to read the
tool's help output before running it rather than just copying a command blindly, which
ended up being useful when I had to adjust the wordlist path.
 
## Contributions
 
I completed this activity independently. All room selection, pacing, and
troubleshooting decisions were made on my own. Working solo meant there was no one
to ask when something wasn't clicking, which forced me to actually read through the
material rather than just follow along with someone else.
 
## Quality Assessment
 
The Defensive Security Intro room was the most engaging for me. Going through the SIEM
log analysis tied directly into concepts from other classes, where I've been working with
memory forensics and artifact analysis (CPTS 425) both involve digging through data to reconstruct
what happened. Seeing that same investigative mindset applied in a live monitoring
context made the defensive side feel more concrete as a career direction than it had
before.
 
The Offensive Security Intro room was satisfying in a different way. Getting the flag
after running GoBuster and finding the hidden transfer page was a good reminder that
offensive techniques aren't that mysterious but they're systematic. But I think I moved
through it too quickly and didn't take enough notes on what each step was actually doing.
 
If I could redo this, I'd write up short notes after each task instead of waiting until
the end. I'd also push into Module 2 since Linux Fundamentals would have been quick
given the terminal work I've already done this semester. The three rooms gave me enough
to write about, but more rooms would have made the reflection stronger and the time
commitment easier to justify.
 
Overall this pushed me toward defensive security as a potential career direction more
than I expected going in, mostly because of how much the SIEM work overlapped with
things I already find interesting in my coursework.
 
