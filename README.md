# Mastering Kali Linux for Advanced Penetration Testing - Second Edition
This is the code repository for [Mastering Kali Linux for Advanced Penetration Testing - Second Edition](https://www.packtpub.com/networking-and-servers/mastering-kali-linux-advanced-penetration-testing-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787120235), published by [Packt](https://www.packtpub.com/?utm_source=github). It contains all the supporting project files necessary to work through the book from start to finish.
## About the Book
This book will take you, as a tester or security practitioner through the journey of reconnaissance, vulnerability assessment, exploitation, and post-exploitation activities used by penetration testers and hackers.

We will start off by using a laboratory environment to validate tools and techniques, and using an application that supports a collaborative approach to penetration testing. Further we will get acquainted with passive reconnaissance with open source intelligence and active reconnaissance of the external and internal networks. We will also focus on how to select, use, customize, and interpret the results from a variety of different vulnerability scanners. Specific routes to the target will also be examined, including bypassing physical security and exfiltration of data using different techniques. You will also get to grips with concepts such as social engineering, attacking wireless networks, exploitation of web applications and remote access connections. Later you will learn the practical aspects of attacking user client systems by backdooring executable files. You will focus on the most vulnerable part of the network—directly and bypassing the controls, attacking the end user and maintaining persistence access through social media.

You will also explore approaches to carrying out advanced penetration testing in tightly secured environments, and the book's hands-on approach will help you understand everything you need to know during a Red teaming exercise or penetration testing

## Instructions and Navigation
All of the code is organized into folders. Each folder starts with a number followed by the application name. For example, Chapter02.

All files contain code files.

The code will look like the following:
```
#!/usr/bin/lua
local file = io.open("/etc/passwd", "r")
contents = file:read()
file:close()
print (contents)
```

In order to practice the material presented in this book, you will need virtualization tools
such as VMware or VirtualBox.
You will need to download and configure the Kali Linux operating system and its suite of tools. To ensure that it is up to date and that you have all of the tools, you will need access to an internet connection.
Sadly, not all of the tools on the Kali Linux system will be addressed since there are too many of them. The focus of this book is not to overwhelm the reader with all of the tools and options, but to provide an approach for testing that will give them the opportunity to learn and incorporate new tools as their experiences and knowledge change over time.
Although most of the examples from this book focus on Microsoft Windows, the methodology and most of the tools are transferable to other operating systems, such as Linux and the other flavors of Unix.
Finally, this book applies Kali to complete the attacker's kill chain against target systems. You will need a target operating system. Many of the examples in the book use Microsoft Windows 7 and Windows 2008 R2.

## Related Products
* [Mastering Kali Linux for Web Penetration Testing](https://www.packtpub.com/networking-and-servers/mastering-kali-linux-web-penetration-testing?utm_source=github&utm_medium=repository&utm_campaign=9781784395070)

* [Kali Linux Network Scanning Cookbook - Second Edition](https://www.packtpub.com/networking-and-servers/kali-linux-network-scanning-cookbook-second-edition?utm_source=github&utm_medium=repository&utm_campaign=9781787287907)

* [Kali Linux Intrusion and Exploitation Cookbook](https://www.packtpub.com/networking-and-servers/kali-linux-intrusion-and-exploitation-cookbook?utm_source=github&utm_medium=repository&utm_campaign=9781783982165)
### Download a free PDF

 <i>If you have already purchased a print or Kindle version of this book, you can get a DRM-free PDF version at no cost.<br>Simply click on the link to claim your free PDF.</i>
<p align="center"> <a href="https://packt.link/free-ebook/9781787120235">https://packt.link/free-ebook/9781787120235 </a> </p>