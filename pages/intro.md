# Intro to

## Linux
Before going through Linux, there are some topic that need to be introduce as well. Again, this part is just another super brief introductory. No technical sections. Just a bit (a very tiny bit) of history lesson.

Again, this section is based on this amazing [page](https://btholt.github.io/complete-intro-to-linux-and-the-cli/what-is-linux).

Feel free to jump right into the mentioned page above, or simply read the more oversimplified version here

### Unix != Linux
If we ever going to talk about Linux, it won't get far from the inspiration itself, Unix. This also why every distro (will be explain later) that built on Linux kernel are called `Unix-like` Operation System. 

Unix was created by Bell Labs in the 70s with some philosophy in mind, which is a sort of digital minimalism when it comes to coding. The idea is, instead of making one super specialized tool or program, make it into smaller parts and add another `feature` when needed.

But bear in mind. Unix is not a free OS, and at that time, Linus Torvalds (yes, that Mr. Linus Torvalds) was a bit unsatisfied, due that there are no open-source, free implementation of Unix, and so, he decided to make one instead, that inspired by the Unix itself. That is why, every distro that adopting the Linux kernel are called `Unix-like` OS.

By today, there are many, many OS that implement the Linux kernel. Most of servers run on Linux. Even Android is based on Linux. Linux has been a very big part of our lifes now.

### Why Linux?
So people will ask, why Linux?
1. It's free. As mentioned above. It was built with Open-source in mind. Everyone can use, and modified (make a fork, and add another code on top of it) to suit oneself need. 
2. It's well maintained. Simply because how famous and wide adaptation that makes people/engineers from all over the world constantly contribute and maintain the Linux kernel. In out humble own opinion, the open source nature itself also take parts in why it's well maintained.
3. It will possibly run anywhere. Not only it runs well on x86 CPU Architecture, but it also runs on Arm CPU Architecture. In other words, chances that we have some devices, or old laptops you might ask, we can run Linux on it.
4. The tools are there. Simply because with so many engineers out there. There are tools and apps for use already. No need to create one yourself (you may if you will)
5. The community is **HUUUUUGEEEEE**. You ran at problems? No worries, StackOverflow, or even Quora will probably have the answers you need. When you ran at problems, chances that other people might have already suffers from it, so the needed answers are probably fly around online, looking to be found *wink-wink*

### Distro
As mentioned above, we can think distro/distribution (we will call it distro starting from this point) as a variant that built on top of the Linux kernel itsefl. There are of course, many distro out there that maintained by many people, or in some cases, like Ubuntu, that backed by a company called Canonical, or even Fedora, that backed by Red Hat and included in their RHEL collections, that stands for Red Hat Enterprise Linux. 

But then, we know that sometimes, other distro is built based on other distro, like MintOS, or ElementaryOS that build based on Ubuntu. We can call those *downstream distro*, or we might say it is a *derivative distro* of *other distro*. Either way, those are how we called distros that built based on other distro. Even Ubuntu itself is a derivative of another distro that has been around for years (you can say the mother distro if you will), Debian.

But why with all the choices we might ask? Simply put, every distro has it own purpose. General purpose distro like Ubuntu, MintOS, ElementaryOS, or Fedora are there for general user to use(even though, like Ubuntu or Fedora, has their own version that spesifically build for servers, while for the Desktop experience, they are commonly called **<distro name> Desktop/Workstation**). But there are also other distro that spesifically build for other purpose, like Kali, or ParrotOS that focus on Network Security and Penetration Testing. They can still do any general purpose function, like making notes, etc, but the build in tools/apps that reserved in that distros are for PenTest and NetSec.

Without further ado, here are some examples of distros (that also has been mentioned above):
1. Debian
2. Ubuntu
3. MintOS
4. CentOS
5. Fedora
6. ElementaryOS
7. Kali
8. ParrotOS, etc

**KEY TAKEAWAYS:**
- UNIX
- UNIX-like
- UNIX != Linux
- Distro
- Linus Torvalds