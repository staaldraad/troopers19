# Troopers 19

This repository contains all the content from the talk I gave at Troopers 19.

## Abstract

Link: [https://www.troopers.de/troopers19/agenda/e93wet/](https://www.troopers.de/troopers19/agenda/e93wet/)

Supply-chain attacks have come to the fore recently, with more and more companies moving towards DevOps. This talk demonstrates attacks against the software used to manage and download source code and how this affects the whole software supply-chain and DevOps pipeline.

In this talk I’ll be demonstrating attacks against the software used to retrieve source code and software packages. The talk starts by examining CVE-2018-11235 a vulnerability in git and how this could lead to code-execution. From here we look into the surprising number of places, such as Docker, Kubernetes, npm, and the golang package manager, where this vulnerability could be exploited by an attacker. From here we progress into vulnerabilities in the package/source-code managers for various languages. I will demonstrate a vulnerability in go get that leads to RCE (CVE-2018-16873). Other security issues in source-code/package managers will also be examined. The talk will further examine possible defences against these type of attacks and how the DevOps pipeline can be hardened to prevent these issues from being exploitable.

## Slides

The slides are published here and include speaker notes: [Google Slides Presentation](https://docs.google.com/presentation/d/e/2PACX-1vRw9U55wxo6FIQBylswIPouHZanXkcy9t1tce_qMnyJa96M8mWkKlOR7josXA7C5ylP2jS7XWU_9dyO/pub?start=false&loop=false&delayms=3000&slide=id.g51f88efe39_0_6)

Alternatively, there is a pdf copy in the repo: [https://github.com/staaldraad/troopers19/blob/master/Troopers_2019_slides.pdf](https://github.com/staaldraad/troopers19/blob/master/Troopers_2019_slides.pdf)

## Demos (videos)

* Git - CVE-2018-11235: [https://youtu.be/G0K8DoACDHQ](https://youtu.be/G0K8DoACDHQ)
* Exploiting Docker with CVE-2018-11235: [https://youtu.be/DCKOzHOK8Z4](https://youtu.be/DCKOzHOK8Z4)
* Go - CVE-2018-16873: [https://youtu.be/Obl0hR_tKo0](https://youtu.be/Obl0hR_tKo0)

## Blog posts

Exploiting CVE-2018-11235: [https://staaldraad.github.io/post/2018-06-03-cve-2018-11235-git-rce/](https://staaldraad.github.io/post/2018-06-03-cve-2018-11235-git-rce/)
Go get CVE-2018-16873: _Not available yet_
