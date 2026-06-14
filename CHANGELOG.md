---
Type: Doc
Use: Readme docs for Tokyo Terminal theme, VS Codium/Code version.
Tags: !!str "#documentation #theme"
Creation: 2026-01-15
Update: 2026-06-12
Contributors: 神縁
---

# Changelog

- **2026-01-26 T 01:40**:<br>
Initial commit of a usable version, there are definitely variables unset and forced to ff3b3b or FF0000 by default (I switch things to 00FF00 or 0000FF when I want to check the effect of the variable) Actual production red is decided to be ef2929 (Or 8B3A3A for an aged red).
- **2026-03-10 T 19:59**:<br>
Set up the colors for markdown format as it is the most used format for my text files. It matches almost exactly my obsidian theme, the obsidian theme has not been updated. I am not quite satified with italic color yet but haven't found the real trick. Maybe switch it to a bright yellow or make up a new pastel yellow.
- **2026-05-27 T 14:42**:<br>
Updated my languages to the usual Tokyo Terminal coding scheme. I mostly use Python and C/C++ these days so only focus on editing that.
- **2026-05-28 T 19:10**:<br>
Update KateX color scheme so that it matches the usual coding colors. I found I had to keep numbers in green for better visual appearance, the one that is usually used for comments. But cyan was not contrasting the KaTeX sections from the plain text. So it is... I also made the back returns and linebreaks signs barely noticeable.
- **2026-06-01 T 00:24**:<br>
First prod and publication ongoing. Updated all documentation files.
- **2026-06-02 T 20:07**:<br>
Only just noticed the cpp tokens are not all up-to-date. I will mostly copy the c tokens as I dig a bit deeper into this issue. I also revised shell and yaml for generic visual appearance as well as specific outlining in block of texts.
- **2026-06-04 T 01:48**:<br>
Experimenting with my old VBA .cls files. Using serkonda7 VBA syntax highlight extension that offers token for VBA and VB6 that are enough to emulate the old IDE look.
- **2026-06-07 T 18:08**:<br>
I had to edit an HTML file and took the opportunity to adapt the colour scheme to its language. Plus a lot of minor tweaks here and there.
- **2026-06-07 T 18:08**:<br>
One of my .tex documents needed editing so a few tokens got inserted at the bottom. The limit is passed now I have too many tokens for VS Codium to display hex colours properly everywhere. They are all working fine though and the scheme is nicely defined now.
- **2026-06-08 T 11:30**:<br>
Reworked yaml & json slightly for better coherence. Minor tweaks here and there.
- **2026-06-08 T 11:30**:<br>
Reworked CSS tokens as I was already pulled in the task. Not sure about the color of `entity.name.tag.css`, the orange colored keywords are not alwasy easy to decide. That will do for now.
- **2026-06-09 T 14:33**:<br>
source.json = bold was a case of bad copy paste as it was supposed to only impact curly bracket for a test. Now corrected and properly applied on curly brackets. Also updated the color of entity name tags in css as I could not stand the bold orange overflow when working on compressed css files. Finally I added basic js colour scheme as I had to go through a lot of these js files and it was painful to watch.
- **2026-06-12 T 17:47**:<br>
Reworked Python a little bit. Shell is also verified, a lot is covered in both languages. I finally went through Java common tokens and updated it to the Tokyo Terminal main theme. A lot of variables may be left in all languages but this should be already prod ready all around.
- **2026-06-14 T 23:19**:<br>
Took the time to verify most important languages. A few are left to blind luck but it should be all around pretty consistent and offer visual clarity. I have a nasty default text to fuschia in unknown languages and file formats, I have to manually precise that by default the standard is cyan.