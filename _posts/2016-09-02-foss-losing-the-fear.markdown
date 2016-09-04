---
layout: post
title:  "Open Source: Overcoming the Fear of Contributing"
link: foss-losing-the-fear
date: 2016-09-02 16:00:00 -0300
categories: mobile
comments: true
lang: en
---



Hello! In this post I'm going to talk a bit about my first steps collaborating with Open Source projects. I have already read that collaborating help us gain experience and we can also learn with others. However, I always a bit of fear because I didn't have enough experience or maybe my contribution would be not good enough. Recently, I decided to take the risk and did some very simple contributions that taught me a lot! I'm gonna talk about them in this post.


### My first Pull Request ( on PythonRio's website !)

The first place to look for project to collaborate is the Github! There, we can find many projects happening and in need of collaboratos. I already used Github to host my school projects repositories, but never used it as a platform for collaboration.

Here, in Rio we have the [PythonRio](http://pythonrio.python.org.br/) group that meets every month. The group has a website made with [Lektor](https://www.getlektor.com/) and they needed help to improve. The first thing I did was read its list of issues and, among them, there was this one about the need to create a blog section for the website.

I forked the project and started working on that. In one of PythonRio's meetup, I had watched a talk by [Luciano](https://lucianoratamero.github.io/) about Lektor and learned that it is really easy to work with.

After finishing my work, I sent my [Pull Requests](https://github.com/pythonrio/pythonrio.github.io/pulls?q=is%3Apr+is%3Aclosed+author%3Atfalbo)! Luciano helped me a lot and I could see how simple is to send a pull request! 

After sending it, we could see how my code was compatible with the code that is already in the project. This helps the owners on analyze and approve the Pull Request!


### Helping to translate the Django Girls tutorial!

I didn't know it before, but one can help open source projects without event knowing how to program! That's right! There are a lot of projects in need of documentation and translation!


By the beginning of this years, the [PyLadiesRio](http://rio.pyladies.com/) organized a [Django Girls (there is a post in this blog about this event)](http://blog.thaissa.eng.br/django/2016/03/14/my-first-django-girls/). Among the tasks that we needed to work was the translation of the tutorial. The original tutorial is in English and usually has a lot of updates. It would be great if the translation went along!

I asked the girls what I could do to help and they sent me the [Crowdin link of the tutorial](https://crowdin.com/project/django-girls-tutorial/pt-BR#). There, anyone can post their translation suggestions so it can be voted by other users and approved by the proofreaders.

After some time sending suggestions, I decided to go a little further: I sent an e-mail to the project organizers asking if I could be a proofreader! Then, I could review the translations of the Django Girls tutorial to Portuguese! <3
 

### Sending Kernel patches! xD

Until last year I was doing a internship in Operating Systems. Also, after taking the OS subject at school, I got more interested into this topic. Just after that, I heard about the [Outreachy Program](https://www.gnome.org/outreachy/) and that among its projects is the [Linux Kernel](https://kernelnewbies.org/OutreachyIntro)!


Outreachy happens twice a year and the application includes doing some collaborations to the project(s) of interest. I got really excited about it and start working on my patches right away! For that, I followed the tutorial on the [project's wiki](https://kernelnewbies.org/OutreachyIntro) and started sending my patches.

My patches were really simple and more related to kernel coding style, but they served as learning experience to me! I learned how to compile the kernel, how to use mutt, and how to send commits by email. For my surprise, I had some [accepted patches](http://git.kernel.org/cgit/linux/kernel/git/torvalds/linux.git/log/?qt=author&q=thaissa) and [my name is in the changelog of the 4.6 kernel release](https://github.com/gregkh/kernel-history/blob/master/email/addresses-4.6)! Yay!


#### Conclusion

It is really simple to collaborate with Open Source Projects! I know that sometimes we may feel a bit lost. In these moments, the best option is to ASK FOR HELP! I believe the community is above all in these projects, so there is no problem in asking for hep! There will be always someone willing to help! :)
