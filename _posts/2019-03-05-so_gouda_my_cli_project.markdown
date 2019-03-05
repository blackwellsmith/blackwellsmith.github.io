---
layout: post
title:      "So gouda::my cli project"
date:       2019-03-05 17:38:01 +0000
permalink:  so_gouda_my_cli_project
---


The concept I struggled with the most was scraping. I hadn't figured out how it worked when choosing our own site. I tried several websites searching for one that was simple and had something I was interested in. Finally I decided on cheese, Dutch cheese. The actual site is a wikipedia page on protected cheese of the EU. It was built on many table tags, with not enough #id's or .classes. I had to use nokogiri's (tag)[0] method to grab the <a> tags that I wanted. Within the tags was everything I needed, a name, a href and some text with the geographical location of the cheese. I set attributes for that information. I looped over the tags grabbing that information, creating an instance of my scraper class. I added it to my @@cheese array. Finally leaving it in my .all method for later.

     The controller was easier to tackle. At first I got lost in loops and iteration. Slowly I adjusted my If conditionals and added breaks in my loops eventually creating the desired flow. First it askes if you would like to see a list of cheeses or exit. Once you are presented with a cheese list you can exit, open a link to purchase chees, or select a number and learn more about that cheese.  Once it was done. I  was kinda shocked and excited.  Vaarwel!
