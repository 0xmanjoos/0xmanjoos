![god](https://media1.tenor.com/images/bbd72681f518f79ad7e74edbf6f14379/tenor.gif?itemid=17454568)

## Profiles

## personal site
https://0xmanjoos.github.io

### Pwnable.tw
[![pwnable.tw](https://www.gravatar.com/avatar/41bde45d800f779cd439358d164097cf?size=120&d=mp)](https://pwnable.tw/user/28923)


### Tryhackme
[ ![tryhackme](./icon/jondoe.png) ](https://tryhackme.com/p/jondoe)


### Hackthebox
[ ![hackthebox](https://www.hackthebox.eu/badge/image/361358)](https://www.hackthebox.eu/home/users/profile/361358)

<details>
<summary>My thoughts on Exploit Development</summary>
<br>
<b>

```
+-----------------------------------------------------------------------+
|                         Exploit Development                           |
+-----------------------------------------------------------------------+

why?

i ask myself this question a lot, it just pops up in my head from time to time

why learn exploit development?
why slam your head against the wall day after day attempting to understand memory exploitation?
why not just follow in everybody else's footsteps and attack the much simpler web app?
Heres a list I created explaining my though process, a quick heads up, im not skilled in any sense of
that word, im not here to judge you, to put you below me, or to flex my superior interests, im just
a guy with an opinion, anyways, here goes.

1. You are unique, specialized, and valuable. There will always be a better web app pentester out
there, now that statement goes for exploit development as well, im not so niave to think that im 
going to be the best there ever was. I am just simply stating the fact that knowing, understanding, 
and taking the time to learn, play and create exploits is extremely unique. The majority will have 
given up and chosen to fuzz some directories or enter obscure obfuscated javascript into some input box
somewhere. If you decide to stick with exploit development, it will be exponentially harder, but you will
be much much more valuable. 
if you're good at it that is..

2. Power. im a retard so i love the thought of being powerful, and dangerous. That is the mindset
of a child, i am fully aware. Now you may be thinking, "haha little kid playing with linux binaries
haha who the fuck does he think he is?". I get that, the voice in my head tells me that too, im just
playing with miniature binaries that are basically meant to be exploitable, thats the least practical
thing anyones every heard of. At least with web app pentesting you are able to learn practical
knowledge right?

Wrong... kind of?

I will admit that 100 percent of all binary exploitation challenges are impractical, the only practical
thing about them is that they are practically useless. But thats not the point, the point was to LEARN
something, the point was to build on your knowledge of exploitation scenarios and techniques.
To allow you to stumble upon a vulnerability and have the capability to exploit it.
The point of binary exploitation(to me at least) is to be able to play with practical exploitation
scenarios with minimally sized binaries, without needing to fuzz for the vulnerability(some could see
as bad), on an easy to use operating system!

Even linux exploitation is worth it!, you might be thinking that ive gone insane but hear me out here.
To me, an 0day is an 0day, the recent sudo heap vulnerability was huge, it got everyones attention due
to the severity of it, and that was a linux exploit. No matter the operating system, no matter the
program, enviroment, or technique. Any exploit that allows arbitrary code execution will be powerful.

Now lets get back into why exploit development over web hacking?
Like i said, the main goal of everything is to get code execution right?
Web app are MUCH easier to get code execution out of, the difference in skill is drastically different!
if web is 50% easier than exploit development
and you can find for RCE's with half the time and half the effort then why learn exploit development??

One reason, and one reason only...

A target i am attempting to pwn will not be running a web server on their computer :)
Like i said, im a naive and incompetent child, i have the mindset of one as well, but thats just
how i think, this is my thought process.

Lets say for example, browser exploitation, that is a piece of (practically)exploitable software
Imagine what you could do, with a browser exploit, i, personally, have thought up a few scenarios:

1. Sell it, get rid of it in exchange for money, maybe zerodium, some shady third party, or a nation state

2. Use it in collaboration with some malware devs in china or russia, and distribute their malware with it

3. Hoard it, save it, keep it and maybe one day somebody will piss you off enough to the point where
you feel the need to unleash it

4. Be a good samaritan and either sell it to whichever company owns the software, or publicly release it
and their lawyers swarm you.

What im trying to get at, is that in terms of an exploit, it is essentially a nuclear weapon
Even if you were to achieve an RCE on a web server, given if they were a large enough corporation they
would have containerized the entire thing, built it all on docker or kubernetes, no way you'd be able
to walk away with anything. Their EDR's would pinpoint you before you even got the chance to enumerate

Would you rather learn how to make a weapon capable of taking on anything in the world, or learning how
to pierce the upper layer to a multi layered corporation, unable to do anything else but squirm?

Yea, doesnt sound so enticing does it?

I also hear this question being asked a lot, "is memory corruption dying?". You obviously know my answer
to this question, but let me give you some evidence to back this up. The use of low level languages like
c will never die. There will always be a demand for efficient memory management and c's simplicity, maturity,
and it's community has grown to the point where I personally believe a new c programming language will not be
possible.

This is due to the nature of something being "low level", the need
for operating systems, fast and efficient compilers/engines, custom memory management, and low
level data maniplutation will never end. Some examples of this sophisticated, mature, and efficient 
system will always hold up is that of dynamic memory optimization. Linux has taken massive strides to 
optimize ptmalloc's performance and reduce overhead. The same cannot be said for windows, though who knows 
what their doing over at Microsoft closed source incorporated. No fun allowed in that operating system!!, its 
only for lame people who dont care about efficiency!!

Obviously, these optimizations require security, and a valid argument against my point is, "modern computer systems
are reaching the point to where these once heavy and bloated security implementations cause little to no overhead".
I agree with this statement, the faster and stronger our systems become, the less need there is for efficiency, and so
more binary protections will be introduced. I believe that there will always be a new technique, to bypass a new mitigation.
Thats the way its been for 20 to 30 years, and i believe that it will stay that way. Were long past the days of a simple
stack overflow, and everybody who is interested in this field knows that. Of course, the security researchers that have been
in the loop over the years will be able to catch up and learn these new techniques, but that isnt the same for someone
just starting out in the field. The more mitigations, the higher the bar of entry becomes, and I think that this is a valid
point.

Another problem with memory corruption exploitation i hear getting tossed around is, "there will reach a point in time where
zero day vulnerabilities are no longer worth it any more, where more human intelligence options become more worthwhile". 
This is the dumbest thing i have ever heard in my life. Zerodays are essentially atomic bombs in the cyber space, that is like
saying, "oh yea, one day hostile nation states like north korea will no longer create nuclear missiles because it costs too much".

????????

dumbest thing ive ever heard in my life, that is null and void. I 100 percent firmly believe in the fact that nation states will
be willing to spend that kind of money for targeted attacks. "Human Intelligence" is going to get you nowhere if you are attacking
a high profile target. Man its like saying, yo you got ur 0day?, nah man i didnt buy it, too costly. Lets just shoot bill gates an
email asking him to click a link eh?, OH GREAT IDEA, WONDERFUL IDEA YOURE THE BRIGHTEST MIND OF THE 20th CENTURY!

3. Last and final reason, this one is the most important out of ALL OF THESE
it is fun, it is just plain and simple fun. I am having the most fun freaking out over some strange
behaviour that is going on within a binary. I enjoy that feeling of finally comprehending the
incomprehensible, it is the greatest feeling in the world. The main reason you should do something
is that you enjoy it, if you enjoy something, you will obviously find reasons in why that thing you
enjoy doing so much is superior to everything else. It is similar to people's favorite linux
distributions, when it comes down to it, there is literally no difference. It all just comes down to
reliability and preference, if you love doing something then do it, that is all.

EOF
```
</b>
</details>

<details>
<summary>Programming Languages</summary>
<br>
  
<img alt="C++" src="https://img.shields.io/badge/c++%20-%2300599C.svg?&style=for-the-badge&logo=c%2B%2B&ogoColor=white"/>
  
<img alt="Python" src="https://img.shields.io/badge/python%20-%2314354C.svg?&style=for-the-badge&logo=python&logoColor=white"/>

<img alt="Go" src="https://img.shields.io/badge/go-%2300ADD8.svg?&style=for-the-badge&logo=go&logoColor=white"/>

<img alt="C" src="https://img.shields.io/badge/c%20-%2300599C.svg?&style=for-the-badge&logo=c&logoColor=white"/>

</details>

<details>
<summary>Preferred OS </summary>
<br>
<img src="https://img.shields.io/badge/Manjaro%20-grey?style=for-the-badge&logo=Manjaro">
<img src="https://img.shields.io/badge/Windows-0078D6?style=for-the-badge&logo=windows&logoColor=white" />
</details>

<details>
<summary>Interests</summary>
<br>
<b>
  
Exploit Development
  
Reverse Engineering

Computer Science

Malware Development

</b>
</details>
