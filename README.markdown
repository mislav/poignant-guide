## Why's (Poignant) Guide to Ruby

On August 19, 2009 Why the Lucky Stiff removed every trace of his work from the
Web, including this book: the Poignant Guide to Ruby.

I've salvaged the book from the Internet archive and re-published it. The
original work was under the [Attribution-ShareAlike license][cc].

Since then I have:

1. Changed code examples to never generate syntax warnings
2. Updated code examples to match Ruby 1.9 behavior
3. Applied grammar/spelling corrections
4. Updated outdated Ruby installation instructions
5. Converted the HTML book into Markdown (\_why originally authored it in Textile)
6. Made a build system powered by Jekyll
7. Enabled syntax highlighted code where previously there wasn't

## Build system

Run `script/jekyll` to [build the site with Jekyll][jk].

The individual chapters are in `_posts/` directory.

## Notes

There's a [Japanese translation of the book][jp], although I can't tell how up
to date it is.

The original soundtrack and PDF edition are also available in
[the download section][dl] on GitHub.

Chapter 8: Heaven's Harp was never recovered. I suspect \_why started drawing it,
but never finished or published.

* * *

> "Quite so," he said.  "I went out to my car yesterday and there was a shoe in the passenger's
seat.  A very battered oxford.  Looking straight ahead like it needed a lift to the cobbler's.
I did a cavity search and came up with a crisp note from my deceased ancestor, the same 
whose property I've looked after, lo, these many years."

> "Wow," I said.  And I glared at my shoe, at the things it would do when I'm gone.


  [cc]: http://creativecommons.org/licenses/by-sa/2.5/
  [jp]: http://www.aoky.net/articles/why_poignant_guide_to_ruby/
  [dl]: http://github.com/mislav/poignant-guide/downloads
  [jk]: https://help.github.com/articles/using-jekyll-with-pages
