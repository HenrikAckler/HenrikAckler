# portfolio website 🖼️
I wanted some practice in simple, from scratch website creation, and I wanted a place to store some project discussions. So I made [this portfolio website](https://henrikackler.github.io/portfolio/).

# whoami ❓

I'm Henrik, though I often go by 'Hank'. Professionally/academically, I'm a Undergraduate at Boise State University's Department of Computer Science, looking to graduate spring of '27. I'm currently looking to get an internship in software development/engineering for the summer of 2026, where I can tackle new challenges and learn new things while contributing to a team effort.

Outside of work and school, I'm not much different. I like to learn, I like to tinker, and I like to endlessly find new ways to optimize. Free time is often spent looking into assorted STEM fields, discovering applications of algorithms everywhere from Shazam to Factorio, and trying to explore concepts way over my head to see how far I can go. If you have something interesting you're doing in Computer Science or elsewhere, reach out to me on [LinkedIn](https://www.linkedin.com/in/henrikackler/) 📧.

## Why is your GitHub bare? 🏜️

I don't think anyone actually cares that I don't have many published projects, but it bears covering. I put my side projects on Github if I'm really learning from them, or if I think I want to share. Personal projects are about growth to me. For example, my [ASCII Art](https://github.com/HenrikAckler/asciiArt) project. I published it because of how much I learned, and how important it was early in my learning journey. Is it good? No, not really, but doing it made everything I wrote after that better, and it's a project I wish to revisit at a later date.

And while most things don't turn into my next greatest learning journey, at least daily I open my IDE, or CAD, or shell, or even just a new note page on my tablet, and I see where an idea takes me.

## Favorite Projects 🛠️

### Edgerton-style Flash
For some reason, I decided to spend a summer break during high school attempting to replicate the results of [Harold Edgerton](https://www.bbc.com/future/article/20140722-the-man-who-froze-the-world). I wanted to produce a flash of light so fast I could freeze a bullet in motion, and to do that I needed to dump an absurd amount of light for no more than and no less than one millionth of a second. Edgerton did this using upwards of 15kv. I was in highschool and wanted to see graduation, so I decided I would change my strategy.

It was not easy. I was a high school student with a few weeks of E&M instruction trying to fight all manner of electrical pitfalls with components mostly older than me sold for cents at a local nonprofit. If I was too close to the wall, the AC wall power would mess up the signals. If a component wasn't oriented right, the interference it generated would break the circuit. If I used "white" LED's instead of RGB, the phosphor coating would ruin my timing. If I used too much solder on a critical timing component, the parasitic capacitance of the solder blob would wreck my rise/fall times. The list went on. To this day I'm not sure how I pulled it off, but I did. 

As it turns out, LED's can take much higher voltages than rated for a very brief period, and due to the nonlinear I-V curve, that caused a massive increase in output. In the end, I was dumping kilowatts into an LED strip designed to be ran under 50w. The flash was so fast it was barely visible, but the heat on any skin close to the LED's was there, and using a light sensor and an oscilliscope I could confirm it. In around 50 nano seconds, the light levels skyrocketed to full intensity, holding for nearly exactly a millionth of a second, before plummeting to nothing almost as fast as they appeared. Not many pictures or writings from that project survived, but my oscilliscope victory picture below lives on.

And in the end a difficult school year began, and COVID followed, components were lost and damaged, and I never froze a bullet in time. But that's okay, because the second I started honestly working on the problem it was no longer about the bullet.
<img width="1720" height="1290" alt="osciliscope img showing 1 microsecond pulse" src="https://github.com/user-attachments/assets/e8ed1646-1f41-4d1f-a43f-bddf9a453d77" />

### ASCII Art

This [program](https://github.com/HenrikAckler/asciiArt) was one of my favorite learning experiences, and one I hope to return to when I've learned more. This project introduced me to bit manipulation, type conversion, String optimization, direct pixel access in images, and program structure. I did know from the start that this was not a good task to run on a single thread on the CPU, but I wanted to see where it would go.

There are two places I think this program needs to go for me to make progress. First of all, ideally I eventually make the leap to GPU or at least parralelized computation. Secondly, I need to make the data structures I use for this play to my advantage. I believe I'm paying a very hefty performance toll in even RAM access costs, nevermind file access. If I don't fix this, I'm pretty sure any reasonable performance increase will be lost to cache thrashing and memory latency. 

---

I hope the read was interesting. I'll add more to this page later, but for now feel free to browse what I have here, or reach out if you'd like to chat. 👋
