---
layout: post
title: My Note Taking System - pt 1. 
---

*Productivity As a Linux User and Uni Student*


> "Notes aren’t a record of my thinking process. They are my thinking process."
> – Richard Feynman

This is just the perfect quote that summarizes my obsession to note taking and note taking systems. 
I have this bad habit of switching note and task listing methods so often.

I used to use text files for storing simple notes here and there snippets of text with a file name of what was contained inside them like "Shortcuts for kdenlive.txt" so if would be easier for me to recognize them later on.  

Jump a few years forward and i learn about this second brain thing, every one is on the hype about note taking and every one all of a *sudden has ADHD* (hot take just saying.) so i learn about this really niche software that just came out of beta and a second brain note taking program with linking notes functionality and so on, if you guessed it kudos to you i am taking about [obsidian](https://obsidian.md/) and it uses markdown a human digestible easier version of HTML which was the successor of XML, to much obstruction but that is not the issue on hand. 

Obsidian was just the thing i needed has a working flatpak application on Linux, locally stored notes and uses MD, learning markdown basically just takes 5 minutes and i was hooked i had it open always and started reading about it. 

Then it got popular as the idea of the second brain and note taking started to get more spot light Notion was another tool i tried but online and within the browser did not do it for it, so then more people who loved obsidian started popping up. We had YouTube channels dedicated to it and only it more plugins more of everything every one in every field that deals with notes have heard of obsidian or is using obsidian and as the community started to grow and new things got added my obsidian workflow also started to grow and that is when the drawbacks of obsidian started showing up on me, it's start up time got slow with all the plugins and themes and it took like minutes to load, a lot of features added and it turned from this one simple tool something that i completely just don't use often anymore as i used to do. 

When ever i installed a fresh install of a distro it would be one of the programs i had installed  but don't use often, just stays there and i use it sometimes for taking podcast notes and researching stuff because obsidian really left that markdown love stamped on me, so while researching other markdown note taking systems i discovered that obsidian plugins are open source and that obsidian itself is not open source but free for personal use, now it did not bother me at first but when i got so into FOSS and Open Source stuff i knew that looking to other alternatives was a great idea.

I tried variety of markdown note editors on Linux ghost writer, haroopad, gitbook and many others but one that stayed a bit long with me was Mark Text for its simplistic looks and great pdf export, after a while of using it started to go funky on me, so inevitably i had to go back to obsidian and use it for my notes until i found a better alternative.

But one editor that always popped up in the articles i digested was Vim, now why did i not try vim, i am an extensive vim user built up my vimrc here and there for years for PDE( personal development Environment) and i never thought that a modal terminal based text editor could satisfy my note taking needs, YouTube being YouTube it recommended me videos on VimWiki, i thought VimWiki ?? is that a fork of ZimWiki of what. So i did not bother trying and just kept on my life,
But YouTube did not stop recommending me those videos and one videos popped up to me and i thought i should watch this. 

In the midst of this i was using libre office specifically libre writer for taking notes and writing my blogs i really loved it and *.odt* should be the default standard for word documents. i even convinced my windows user friends to save in .odt in MS-Word, now there was no way of back linking and organizing notes to this second brain stuff, no tags and no graphs but while using libre writer i got into the mindset of *What Ever Gets The Job Done*.

So back to the YouTube video that talks about VimWiki (check out the [video](https://www.youtube.com/watch?v=HbF0yAghbDo&pp=ygUHdmltd2lraQ%3D%3D)) so after watching this and seeing that i was convinced to switch to VimWiki, i did not hesitate i went added the plugin set it up to read markdown moved all my obsidian notes into the VimWiki directory and was hooked just like that.

But there were a few drawbacks to it, tags quite a hustle, after adding a tag you have to remember to rebuild tags and searching them was quite a pain but nothing you can automate in the vimrc. 

Now you might find this a bit surprising but i did not stay that long on VimWiki, with the constant bullying of my friend to switch to neovim and the passing away of Bram Rest In Peace, i finally made the switch to neovim. I basically just cloned his nvim directory straight from his dot files on GitHub and configured it to my liking and was right on the go. 

But now here is the issue VimWiki which i finally got to work properly in vim using packer, i know i know use lazy nvim and stuff but when i first started with neovim i used kickstart nvim which uses the lazy package manager and was not my cup of tea but packer i really got the hang of it quick, so after getting VimWiki to work on neovim. There were this minor inconvenience like links require double enter to open, backspace does not save sometimes and was quite annoying.

But it was not long before i found out another note taking system that integrates well with neovim and that is [Neorg](https://github.com/nvim-neorg/neorg) i first heard about this on a reddit post i asked in vim asking about migrating from obsidian to VimWiki. 

They told me that is was a great note taking tool and they used it for a year now and it like emacs org mode but different and for vim, but i refused because i was on vim and VimWiki was working fine for me and no reason for me to switch and move out of my comfort zone and relearn new syntax other than markdown, i mean if i really wanted org mode i would have switched to emacs, which i did a while a go to try it but what ever i read and heard just fell out the other ear so i ended up not using emacs org mode.

Now after switching to neovim i had no other option it was either install emacs learn to configure it then learn to use org mode which was quite a hustle and i am already on neovim so why complain just suck it up and learn *norg* syntax and start using neorg, so before reading the docs i wanted to see what the YouTubers had to say about it, so when i searched up neorg i found this great playlist by one of the developers that explains it from the ground up, installation, syntax, errors and stuff and that was a perfect beginning ground for me.

Now i don't want to drag this blog longer than this and turn it into a novella but norg syntax is similar to markdown and org mode its like the middle child 

![Excalidraw Graph](https://i.imgur.com/IgoTotU.png)

It has all the Cool features from most common used markup languages and also adds its own functionality and extends it is still under development and the developers are adding more functionality into it and i would proudly say it is the future, and for now my note taking system is fully reliant on neorg. And i don't think i will be changing anytime soon. 





*I know this blog felt rushed at the end but that is because i did not want to drag you all the way along reading about my journey but i am thinking abut writing separate other blogs on neorg and logseq and how i use them in my daily life as a part 2  and 3 to this one, and as always hope you enjoyed this one and don't forget to check neorg out 2024 is the year of neorg i feel it*

