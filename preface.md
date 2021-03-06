# Preface

You are a **software developer**? And sometimes you need to use **cryptography** in your daily job, like hashes, encryption and digital signatures? And you think cryptography is complex and full of math and it is for nerds only? No, this is not true, every developer can learn **how to use cryptographic algorithms**. This book will show you how, with code examples, with less math and more practice.

It is not required to be а strong mathematician or even not strong mathematician to **understand the cryptographic concepts from the developer perspective**. This book will teach you the basics of **applied cryptography** in almost free of math style, following a step-by-step approach with lots of **code examples** and **practical exercises**, just like when you learn Web development, databases or mobile apps. Yes, if you can learn Web development or RESTful services, you can learn the practical aspect of cryptography as well. It is just like learning a new API or a new Web development framework: you learn a combination of **concepts** + **APIs** \(crypto algorithms implemented in crypto libraries\) + **tools** + **best practices** how to use these APIs and tools.

From this book you will learn **how to use cryptographic algorithms and cryptosystems** like hashes, MAC codes and key derivation functions \(KFD\), random generators, key exchange protocols, symmetric ciphers, encryption schemes, asymmetric cryptosystems, public-key cryptography, elliptic curves, digital signatures and quantum-safe crypto algorithms, together with modern cryptographic tools and libraries.

I am happy to publish this free **developer-friendly practical cryptography book**.** **It holds just **what developers need to know** in order to **use cryptography in their every day work**. It does not cover the internals of the algorithms and how to design symmetric ciphers, public-key cryptosystems or authentication schemes. It covers the basic understanding of the **core cryptographic concepts** and how to use them from developer's perspective: **libraries**, **tools**, **code examples**. This is what most developers need to know about cryptography. This is what this book gives to you for free.

## This Book is for Developers!

This book is designed** for developers** who write code every day, for **software engineers** who create software systems, Web applications, mobile apps and other software. It may be useful also for **DevOps engineers** who deal with crypto algorithms and write code to automate the IT infrastructure, for **system administrators**, who want to learn practical cryptography better, for **information security engineers**, who need to deal with cryptography every day and to know which ciphers and crypto algorithms are safe and which are broken, along with the possible attacks, for experienced **QA engineers** who perform security testing and code reviews about security and cryptography, and for many other **IT professionals**.

This book is about **using crypto algorithms** and cryptographic packages, not about designing ciphers, signature schemes and cryptosystems. You will learn how cryptosystems work \(without too much math\) and how to use them in your daily job. This book is not 100% free ot math, but the complexity level is reduced to match the average developer's level, and complex concepts are explained in simplified and understandable style. This book is created **by developers for developers**, not by university professors or mathematicians. It is about coding in a smart way, with understanding the concepts and **using the crypto algorithms and crypto libraries the right way**. It is about the modern crypto algorithms and cryptographic techniques, used today in the software industry \(as of Nov 2018\).

## This Book is Free!

The main book author **Dr. Svetlin Nakov** donates this book and its entire content and code examples **for free** to the developer and IT community as **open-source project**, under [the MIT license](https://opensource.org/licenses/MIT). Why? Because the main book author and the people behind this project believe that the **knowledge is for everyone** and it should be **shared for free**, because developers should learn to use cryptography the right way, because our world needs more secure software, because **sharing knowledge and skills for free** is the greatest miracle of the modern education.

For the same reasons, which drive the people to build **Wikipedia** and share knowledge for free, to publish open-source projects in **GitHub** and share code for free, to develop open-source software like **GNU/Linux** and **Firefox** and distribute it for free, I write and publish this open-source cryptography book for developers. I want to **share knowledge and skills**, to help the developers to become **better professionals**. I personally as a developer, when I learn a new technology, I search for free resources and code examples in Internet and I am happy that someone creates and shares them for free. Now it is time to return back to the society and to the developer community and this makes me happy.

## About the Author: Dr. Svetlin Nakov

**Svetlin Nakov** \([http://www.nakov.com](http://www.nakov.com)\) is a passionate **software engineer**, inspirational **technical trainer** and tech **entrepreneur** from Bulgaria, experienced in broad range of languages, software technologies and platforms. He is co-founder of several highly successful **tech startups** and non-profit organizations and is a **technical advisor** in several successful blockchain **ICO projects**.

Svetlin Nakov has 20+ years of technical background as software engineer, software project manager, consultant, **trainer** and **entrepreneur **with rich experience with .NET, Java EE, information systems, databases, cryptography and software security, Web development, JavaScript, PHP, Python and software engineering. He is the leading **author of 15 books** on computer programming, software technologies, cryptography, C\#, Java, JavaScript, Python and tens of technical and scientific publications.  He is a big fan of **knowledge sharing** and is proud Wikipedia contributor, free books author and open-source supporter.

Svetlin has been a **speaker** at hundreds of conferences, seminars, meetups, courses and other trainings in the United States, Singapore, Germany, Egypt, Bulgaria and other locations. He holds a **PhD **degree in computer science \(for his research on computational linguistics and machine learning\), several **medals** from the **International Informatics Olympiads** \(IOI\) and the Bulgarian **President’s award “John Atanasoff”**. He has been a part-time assistant professor / trainer in Sofia University, New Bulgarian University, the Technical University of Sofia, Ngee Ann Polytechnic \(Singapore\), Kingsland University \(USA\) and few others.

Currently Svetlin Nakov together with his partners drive the global expansion of the largest training center for software engineers in Bulgaria – the **Software University** \(https://softuni.org\), where he inspires and teaches hundred of thousands of young people in computer science, software development, information technologies and digital skills, gives them a profession and a job.

## The History behind This Book

Svetlin Nakov together with tens of co-authors has created and published as open-source projects \(in the period 2004-2018\) **tens of technical books** about computer programming and software technologies \(see http://www.introprogramming.info and http://www.nakov.com/books\), most of which in Bulgarian language. In the last few years Svetlin switches to English and takes **global knowledge sharing initiative** for **better and accessible tech education**, demonstrated with creating and sharing free tech books, free tutorials, free tech webinars and seminars, conference talks and many other activities. 

The book author **Svetlin Nakov** is involved with **applied cryptography** from 2005, when he published the book "_Java for Digitally Signing Documents of the Web_" \(in Bulgarian\), following his master thesis on a similar topic. Later Nakov is involved in his practice as software engineer, tech trainer and entrepreneur, with **cryptography**, **software security** and **blockchain** systems, and his technical expertise grows along with his experience. In 2018 he decides to write a **free book** to share his knowledge about cryptography and crypto algorithms from developer's perspective and donate this knowledge to the global dev community. The book takes 3 months to be written and gets published in Nov 2018. You can get a free copy from https://cryptobook.nakov.com.

## Why Another Book on Cryptography?

Most books about cryptography are written either in too **academic style** with a lot of theory, like [http://cacr.uwaterloo.ca/hac](http://cacr.uwaterloo.ca/hac/%29%29%29\).

...

Others are too old: ...

...

Others are not bad, but are not free:

[https://leanpub.com/crypto](https://leanpub.com/crypto)

[https://www.amazon.com/Cryptography-Developers-Tom-St-Denis/dp/1597491047](https://www.amazon.com/Cryptography-Developers-Tom-St-Denis/dp/1597491047)

Crypto libraries come with limited and not consistently organized documentation, e.g. the Crypto++ Wiki [https://www.cryptopp.com/wiki/Main\_page](https://www.cryptopp.com/wiki/Main_page%29%29%29\).

...

...

## Why Python is Used for the Examples?

...

