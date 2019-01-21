---
layout: essay
type: essay
title: Telnet for Dummies
# All dates must be YYYY-MM-DD format!
date: 2018-09-22
labels:
  - Telnet
  - Command Line
  - Data Networks
---


What is Telnet?

Telnet is a network protocol used via the command line to establish a connection on the internet(makeuseof). Since it runs from one’s command line, it is not the best for actually viewing website content. But is better suited testing for open ports (acronis) and studying networks. If a user makes a connection to a website via telnet, telnet will return the website’s page(s), but the website will be represented completely in text. So HTML tags and everything one can see by using “View Source” in a browser will be displayed, rather than a graphical webpage. 

How to Use Telnet

In order to use Telnet to connect to the internet, the first step is locating and opening the terminal or command line on the computer. The easiest Telnet command is the following: telnet www.somewebsite.com, where wwww.somewebsite.com is the website of the user’s choosing. To take this command to the next level, the user can add a port number of the website url. For example, telnet www.quora.com 80 will connect the user to Quora’s website via port 80. 
	
When connecting via ports, each port is unique. Port 80, for example, is used for HTTP connections (techopedia). Port 443 is used for HTTPS, or secure HTTP (web.mit.edu). Telnet can therefore be used to check other open ports, just by adding a port number after the url in the command (acronis). 
	
Another way to use Telnet, especially when testing for open ports, is to specify an IP (Internet Protocol) address instead of a url (acronis). For example, let there be an IP address 128.0.1.2, the command telnet 128.0.1.2 443 will send a request to connect to the website connected to said IP address via HTTPS (acronis). If such an address exists for a website, and the website accepts HTTPS, the user will get a response header and body of the website. Otherwise, the user may get an error stating an unsuccessful connection. Other ports can be tested, such as SMTP, which runs on port 25 (acronis).
	
Lastly, Telnet has flags, or options, that can be added on. As with most command line commands, these flags generally go after the initial command, followed by any necessary parameters. For example, -4 is an option that forces telnet to strictly use IPv4 addresses. The command would look like the following: telnet -4 [some IP address or URL].There is also a tracefile option, noted by -n. There is a lengthy list of Telnet options, along with their descriptions and required parameters in the man page for Telnet. The man page for options can be found by the following command: man telnet.
