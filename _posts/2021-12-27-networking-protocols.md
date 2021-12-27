---
layout: post
title: Networking Protocols
subtitle: Popular rules that allow and secure communication over network
cover-img: /assets/img/protocol-cover.jpg
thumbnail-img: /assets/img/protocol-cover.jpg
share-img: /assets/img/protocol-cover.jpg
tags: [informationsecurity, cybersecurity, networking, protocols, security+]
---

Protocol refers to the rules required by different applications for the exchange of data, where the application can perform actions such as running commands on remote systems, sending and receiving emails, and downloading files from the internet.
Each application has a special port number that it uses for communication. You can think of ports as being TV channels: if we want to watch sport, we go to the sports channels; if we want to watch the news, we go to the news channel.

There are two types of ports: **Transmission Control Protocol (TCP)** and **User Datagram Protocol (UDP)**. The main difference between the two is that TCP is connection-oriented as it uses a three-way handshake, and UDP is faster but less reliable as it is connectionless. 

Now, let's take a deep dive into the popular protocols along with the ports, for ease to understand we would divide these into Inseucre and Secure Protocols

## Insecure Protocols

- File Transfer Protocol(FTP): As the name suggests, the most common function is to transfer files. Port: 21.
- Hyper Text Transfer Protocol(HTTP): This is used to access websites, no matter whether you are using Internet Explorer, Chrome, Firefox, or Microsoft Edge. Port: 80
- Network Time Protocol(NTP): One of the important protocol in networking which ensures clock times of computers and servers are synchronized. Port: 123
- Light-weight Directory Access Protocol(LDAP): Protocol which manages, creates and stores objects in directory service. Port: 389
- Simple Mail Transport Protocol(SMTP): This is used to transfer files between mail servers. Port: 25
- Post Office Protocol(POP): Email client protocol which pulls the mails from mail server. Port: 110
- Dynamic Host Configuartion Protocol(DHCP): This allocates IP addresses dynamically to computers. Port: 67/68

## Secure Protocols

- Secure Shell(SSH): It is commonly used when you want remote access to network devices. It can be used as a command-line tool or in a Graphical User Interface (GUI), but it is not browser-based. Port: 22
- DNSSEC: Protocol that prevents someone gaining access to DNS records. Port: 53
- Light-weight Directory Access Protocol Secure(LDAPS): : When objects are created in directory services, they are securely managed by LDAPS. LDAPS creates and stores objects in X500 format and uses three parameters: DC for domain, OU for organization unit, and CN for anything else. Port: 389
- Hyper Text Transfer Protocol Secure(HTTPS):  This can be used to secure a web page but is more commonly used when making a purchase on a website, where you will be diverted to a secure server that uses HTTPS so that your session is secure and you can then enter your credit or debit card details. Port: 443
- Transport Layer Security(TLS/SSL): TLS is used to protect data in transit and is an upgraded version of SSL that is used to encrypt communications on the internet, such as email or internet faxing, and transfer data securely. Port: 443
- IPSec: IPSec can be used with L2TP/IPSec to provide a VPN session. Port: 500

These protocols might be helpful to you if you are going to appear for Network/IT Security Certifications and in general as well. Must rememeber to keep the ports in mind as protocols have a good relationship with ports and the exams love to question the candidate about them.

Thanks for reading.

Cheers :)
