# THIS IS NOT YET READY FOR SPRING 2019 - WILL CHANGE A LOT
# Week-08-SSH-SSL-Certificates
Cryptograhy, Certificates, Digital Signatures, Man-in-the-middle and more

_This is going to be a pretty heavy week when it comes to theory. Most of the exercises will not involve code, but steps necessary to understand and USE the terms below, and see how they are all required to get a secure connection in a browser_
- SSH and SSH Tunnels
- Symmetric Encryption
- Asymmetric Encryption
- Hashing and Hash Digests
- Digital Signatures
- Certificates
- Certificate Authorities and Certificate Trust Hierarchies
- :red_circle: MAC (Message Authentication Code)
- :red_circle: Cipher Suites

## What to Install

[WireShark](https://www.wireshark.org/download.html) if not already done. If you have installed Kali Linux, just continue with the version available here.

#### WireShark SSL-handshake sample we did in the class
[wireshark-sample (TBD)](#)
      
## Wednesday March 20 th.

### What to Read or Watch :information_source:

<!--
- [:tv: Introduction to Cryptographic Keys and Certificates](https://www.youtube.com/watch?v=q9vu6_2r0o4)
- [:tv: What are certificates](https://www.youtube.com/watch?v=LRMBZhdFjDI&t=264s) (Covers more or less the same topics as the next video, I do however recomment both)
- [:tv: What is PIK (public key infrastructure)](https://www.youtube.com/watch?v=5OqgYSXWYQM&t=170s) (watch the first 8 minutes)
- [:tv: Intro to SSH and SSH Keys](https://www.youtube.com/watch?v=mF6J-VQHPxA&t=293s) (This introduces the three scenaious you are expected to set up in the first exercise, and eventually demonstrate at the exam)
-->
- [:book: Understanding the SSH Encryption and Connection Process (30 min.)](https://www.digitalocean.com/community/tutorials/understanding-the-ssh-encryption-and-connection-process)
- [:tv: What is SSH? (4 min.)](https://www.youtube.com/watch?v=tCHldm7QTJo)
- [:tv: Intro to SSH and Keys (13 min.)](https://www.youtube.com/watch?v=mF6J-VQHPxA&t=293s)
- [:book: SSH Tunnel (15 min.)](https://www.ssh.com/ssh/tunneling/)
<!--
- [Man in the middle attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack) Read the first part (Example) of the article and skim the rest
- [:book: Symmetric vs Asymetric Encryption](https://www.jscape.com/blog/bid/84422/Symmetric-vs-Asymmetric-Encryption)
- [:book: Cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function) (Skim only)
- [:book: Cipher Suites](https://www.jscape.com/blog/cipher-suites) Skim only, neccesary to understand parts of the Wireshark demo
- [:book: Differenc between a digital signature, a MAC and a hash](https://crypto.stackexchange.com/questions/5646/what-are-the-differences-between-a-digital-signature-a-mac-and-a-hash) Read the approved answer in this StackExchange article
-->
### Exercises :memo:
<!--
- [SSL and SSH, three different scenarious](https://docs.google.com/document/d/1ac7HrNnu4rlS43LODodjAP25KR-p2apKSaMFy01PWro/edit?usp=sharing) This should, if possible, be done/started before lesson-1 in this week
-->
- [SSH-SSL with MySQL](https://docs.google.com/document/d/1G3GaXH3ZfoX29bQRmUJLxPaTbc8Zta7XgbjFoLVik1c/edit?usp=sharing)
- [SSL Handshake](https://docs.google.com/document/d/13oD_h5fO9i1rIeQaiMxzG54w3q5dc0neL8nPGX2HEdw/edit?usp=sharing) We will do this together in the class
- [Tomcat with SSL and preparing for the exam](https://docs.google.com/document/d/1pY6gbHgAzzMZshgwIhejSZ9ROtQy8dHacci0mdJvdcI/edit?usp=sharing) 
- [:book: Differenc between a digital signature, a MAC and a hash](https://crypto.stackexchange.com/questions/5646/what-are-the-differences-between-a-digital-signature-a-mac-and-a-hash) Read the approved answer in this StackExchange article

## Thuersday March 21 th.

### What to Read or Watch :information_source:
- [:tv: Introduction to Cryptographic Keys and Certificates (18. min)](https://www.youtube.com/watch?v=q9vu6_2r0o4)
- [:tv: What are certificates (15 min.)](https://www.youtube.com/watch?v=LRMBZhdFjDI&t=264s) (Covers more or less the same topics as the next video, I do however recomment both)
- [:tv: What is PIK (watch the first 8 minutes)](https://www.youtube.com/watch?v=5OqgYSXWYQM&t=170s) 
- [Symmetric vs Asymmetric Encryption (10 min.)](https://www.jscape.com/blog/bid/84422/Symmetric-vs-Asymmetric-Encryption)
- :full_moon: [:book: Cryptographic hash function (5-10. min Skim only)](https://en.wikipedia.org/wiki/Cryptographic_hash_function)
- :red_circle: [:book:Cipher Suites (6 min. skim only so you know what it is conceptually)](https://www.jscape.com/blog/cipher-suites) neccesary to understand parts of the Wireshark demo

