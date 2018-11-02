# BLUEBASIC_Scheme
Scheme for the Redmatix on Hubzilla

- It changes your home-channel into a facebonk-like profile page (as in the picture above), something I found in the "Suckerberg" theme by @Sean Tilley and liked a lot.

- It comes with a new logo-usermenu, which is also inspired by Sean's work. The color of the logo is set by the background of your navigation bar (the top-bar) - so it adjusts nicely. It serves as a button as well, as it always take you back to your network stream. Something I like a lot, when I use Hubzilla on my mobile.

If you want to change the "HUBZ!LLA" label, you have to hack the
userlogomenu.tpl
in the tpl sub-directory of your Redmatrix theme.

In an earlier version of the logo, I wanted to display the site-name automatically, but I couldn't figure how to extract that from the database. But then - many hub-names are rather long, which would destroy the logo, so I sticked with "HUBZ!LLA".

- The scheme does display embedded videos in a 100% width with a styled new "play" button. That's another major visual change it has. NOTE: This is done with a hacked version of the Zotlabs Module 

Oembed.php

And that is also the piece I would need help with! Because this file would potentially be in conflict when a new release is pulled from the git - I just delete it, when

util/udall

throws an error at me and copy it over after the update. (That's NOT sustainable, but how I did it... and it worked ;-)) I just couldn't figure out how to do it on the theme level - if that would be possible at all? Anyway -  a generic theme css, which would be located in another directory would do this job equally well - but anyway, the Zotlabs module would need to be changed - or moved into the theme.

- And then there are multiple small changes all over the place, which are all done just by fiddlin' around with the CSS styling of it... For most you would have to compare the red/bluematrix side by side... but all in all, too me, they make a significant difference.

I will, most likely pack it into a theme of it's own. To me, this was just a proof of concept. I hope, I've been able to explain, how I did it... Be aware: This is experimental!
