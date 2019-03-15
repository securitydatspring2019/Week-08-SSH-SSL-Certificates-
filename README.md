# Week-08-SSH-SSL-Certificates
Cryptograhy, Certificates, Digital Signatures, Man-in-the-middle and more

_This is going to be a pretty heavy week when it comes to theory. Most of the exercises will not involve code, but steps necessary to understand and USE the terms below, and see how they are all required to get a secure connection in a browser_
- Symmetric Encryption
- Asymmetric Encryption
- Hashing and Hash Digests
- MAC (Message Authentication Code)
- Digital Signatures
- Certificates
- Certificate Authorities and Certificate Trust Hierarchies
- Cipher Suites

## What to Install

[WireShark](https://www.wireshark.org/download.html) if not already done. If you have installed Kali Linux, just continue with the version available here.

#### WireShark SSL-handshake sample we did in the class
[wireshark-sample (TBD)](#)
      

## Wednesday March 20 th.

### What to Read or Watch :information_source:

- [:tv: Introduction to Cryptographic Keys and Certificates](https://www.youtube.com/watch?v=q9vu6_2r0o4)
- [:tv: What are certificates](https://www.youtube.com/watch?v=LRMBZhdFjDI&t=264s) (Covers more or less the same topics as the next video, I do however recomment both)
- [:tv: What is PIK (public key infrastructure)](https://www.youtube.com/watch?v=5OqgYSXWYQM&t=170s) (watch the first 8 minutes)
- [:tv: Intro to SSH and SSH Keys](https://www.youtube.com/watch?v=mF6J-VQHPxA&t=293s) (This introduces the three scenaious you are expected to set up in the first exercise, and eventually demonstrate at the exam)

_Since we are not using a text-book, but web resources only, there are many alternatives to the suggestions given below. You can use the topic-list given at the beginning of this document and find your own references if you prefer. You are definitely not expected to end up as a hardcore crypto-specialist when this week is over ;-) But you are expected to have a conceptual idea of the purpose with all the topics, and why they are needed for SSL (and SSH)_

- [Man in the middle attack](https://en.wikipedia.org/wiki/Man-in-the-middle_attack) Read the first part (Example) of the article and skim the rest
- [:book: Symmetric vs Asymetric Encryption](https://www.jscape.com/blog/bid/84422/Symmetric-vs-Asymmetric-Encryption)
- [:book: Cryptographic hash function](https://en.wikipedia.org/wiki/Cryptographic_hash_function) (Skim only)
- [:book: Cipher Suites](https://www.jscape.com/blog/cipher-suites) Skim only, neccesary to understand parts of the Wireshark demo
- [:book: Differenc between a digital signature, a MAC and a hash](https://crypto.stackexchange.com/questions/5646/what-are-the-differences-between-a-digital-signature-a-mac-and-a-hash) Read the approved answer in this StackExchange article

### Exercises :memo:
- [SSL and SSH, three different scenarious](https://docs.google.com/document/d/1ac7HrNnu4rlS43LODodjAP25KR-p2apKSaMFy01PWro/edit?usp=sharing) This should, if possible, be done/started before lesson-1 in this week
- [SSL Handshake](https://docs.google.com/document/d/13oD_h5fO9i1rIeQaiMxzG54w3q5dc0neL8nPGX2HEdw/edit?usp=sharing) We will do this together in the class
- [Tomcat with SSL and preparing for the exam](https://docs.google.com/document/d/1pY6gbHgAzzMZshgwIhejSZ9ROtQy8dHacci0mdJvdcI/edit?usp=sharing) 
