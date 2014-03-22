---
layout: post
title:  "The Git, The Hub, And The Ugly"
date:   2013-05-18 0:18:15
categories: tech how-to
---


It's funny how your opinion about things can change. I didn't like GitHub when I first signed up for a few good reasons.
* It sucked on Windows.
* There was no single good source about how to use GitHub on Linux
Even the Github help pages weren't that useful unless you manage to piecemeal it all together (which I eventually did).
I must admit though, now that I know how to use GitHub on Linux, It's amazing. It's seriously one of the most useful tools that a software developer could use for version control and _forking_ others code. I am a big fan of this open source movement. 
So in order to help all you wary travellers out there who want to become a part of this, let me blaze a single trail here where you can refer back to the basics of using the git command and GitHub.
1. Before we start make sure you have git installed. If your using a Debian based operating system (I'm using Mint which you can check out <a href='http://www.linuxmint.com/'>here</a>) it might already be installed. If not, the easiest way to do this is to type the following into the terminal.
>    apt-get install git
Then to configure it type
>    git config --global user.name " _This is where you put your username_ "
and
>    git config --global user.email " _This is where you put your email_ "
The first line installs git and the next two just configure the settings to remember your name and email.
2. Now is when we can actually go ahead and start using GitHub. Login and create a new repository.
3. Once a new repository is created, clone that repository onto your computer by entering
>    git clone https://This is the repository address
into the terminal. 
4. CD into the repository
>    cd ~/new repository
5. Now you can add things to that directory from your project. Once new files are added to the directory and your ready to upload type
>    git add .
which will prepare GitHub for all the new files you've just added.
6. Next you want to commit your updated directory, type
>    git commit -m "Put whatever commit message you want here"
7. Finally push ( _upload_ ) the directory back to GitHub
>    git push origin master
If you're pushing to a different branch (for example you're using <a href='https://help.github.com/categories/20/articles'>pages</a>), then just type
>    git push origin gh-pages or whatever your branch is

That's really all you need to know to get started. So go get coding, you could even fork this blog from my github page (that's like creating a new repository).

####Word of the day: __pithy__

####Quote of the day:####
<blockquote>
	<p>“Either write something worth reading or do something worth writing.”</p>
	<cite>-Benjamin Franklin</cite>
</blockquote>