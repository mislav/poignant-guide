On August 19, 2009 why the lucky stiff removed every trace of his work from the Internet, including his Poignant Guide to Ruby.

I've salvaged what I could, cleaned it up a bit and saved here. He released the book under the [Attribution-ShareAlike license](http://creativecommons.org/licenses/by-sa/2.5/). There's a [Japanese translation of the book](http://www.aoky.net/articles/why_poignant_guide_to_ruby/), although I can't tell how up to date it is.

***Update:** just found out about [poignant-guide on why-archive](http://github.com/whymirror/why-archive/tree/master/poignant-guide). Also, it seems people have pushed his code repos back to the "[whymirror](http://github.com/whymirror)" account.*

Interesting detail is that mirroring the site with wget didn't work very well on the Internet Archive site (maybe wget doesn't support the BASE tag) so I had to do it a bit more manually—using _why's own Hpricot library to parse all the LINK, A and IMG tags.

The original soundtrack and PDF edition are also available in [the download section](http://github.com/mislav/poignant-guide/downloads) on GitHub.
