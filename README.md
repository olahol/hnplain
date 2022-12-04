# hnplain
> output Hacker News in plain text

## Example

```bash
$ hnplain -n 5 --list show --topcomment
1. Show HN: Temple.io – Read, annotate, and search popular religious texts
==========================================================================
Link: http://temple.io
Comments (3): https://news.ycombinator.com/item?id=9560269

atonse 2015-05-17 19:25:28
> Fascinating - what I'd love to see is the debate (probably in
> annotations) vs how verses are interpreted.

2. Show HN: Our 1 week hack: A chat room for every app installed on your phone
==============================================================================
Link: https://play.google.com/store/apps/details?id=com.larvalabs.myapps
Comments (0): https://news.ycombinator.com/item?id=9560674

3. Show HN: A DJ Khaled Tinder Bot
==================================
Link: http://joelotter.com/2015/05/17/dj-khaled-tinder-bot.html
Comments (2): https://news.ycombinator.com/item?id=9558251

maknz 2015-05-17 09:56:22
> Great writeup, hilarious outcome! Nice work.

4. Show HN: Simulation of common page replacement algorithms in C
=================================================================
Link: https://github.com/selbyk/pagesim
Comments (4): https://news.ycombinator.com/item?id=9557475

georgerobinson 2015-05-17 00:11:16
> I so could have done with something like this for my Operating Systems
> exam last week. Never the less, it looks great!

5. Show HN: Simple Hash Table Implementation for C
==================================================
Link: https://github.com/watmough/jwHash
Comments (22): https://news.ycombinator.com/item?id=9557920

watmough 2015-05-17 01:59:49
> I know this is pretty simple, but I never ever did at any point
> implement a hash table, just went more or less straight to programming
> in Assembler in a semi-mature system, then to MFC on Windows since
> about 1998. Performance-wise, my single-threaded test runs about 6
> times faster than the equivalent JS, which puts it in the C ballpark.
> I  was  really pleased about the performance under multi-threading.
> With 4+ threads, it's near to being 4 times faster, and the bucket
> lock only spins occasionally (prints a few '.' but still works).
```

## Documentation

```bash
$ hnplain --help
usage: hnplain [-h] [--list {ask,new,top,job,show}] [-n N] [--topcomment]

output Hacker News in plain text

optional arguments:
  -h, --help            show this help message and exit
  --list {ask,new,top,job,show}
                        what list to pull stories from (default: top)
  -n N                  the number of stories (default: 15)
  --topcomment          add the top comment of a story
```
