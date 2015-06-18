I've been playing on and off with [Tahoe-LAFS](https://tahoe-lafs.org/) since [before](https://dubiousdod.org/uri/URI:DIR2-RO:r7xnodn7et6d3ex44p77qk4eka:nvca4ivhhm2an3eafzpg7wpppy7osgyxvngng5uriqjv2qkcag6a/Latest/5th-of-november.html) IT history has [ended](https://en.wikipedia.org/wiki/Global_surveillance_disclosures_%282013%E2%80%93present%29) [retroactively], and until recently believed there were 2 issues Tahoe-LAFS should solve before becoming abundantly available:

1. "Magic folder" functionality
2. Quotas/accounting

The first one is the proverbial "last mile" problem. If it's not as easy as having "team" folder (instead of actively uploading files via web or command line), and anyway - browsers are an attack surface "magic folders" avoid.

The second problem is more inherent: if I can tell *how much* information you're storing, this is already a partial leak of that information (e.g. I can tell you have at most X hours of video).

The way this is solved today is by having grids by clusters of people who *completely* trust each other (i.e. not applicable for traders and news orgs ;) ). A more generalized way of saying this is: *accounting is handled client side* (a code of honor system is also a system).

### Now here comes the clever bit:

Suppose we *sold* honorable *hardware*?

Say a box that contains a 10TB disk that acts as a local lan storage server (web, samba, whatever), and only lets you use 1TB of it, but you get LAFS redundancy for your money.

Now this box is built so that it keeps updating its code from a well known [git] repository, and is legally wrapped so that if it doesn't do *exactly* that (i.e. it's backdoored), you know *exactly* who to sue.

That's it, in a nutshell.

* Not much freedom, but at least it's in a box :wink:

* If you fork this, I believe they will come.

* If you crowdfund such a box, I pledge `$249.30` for it.

* If you like the idea, please spread the word (e.g. star this if you *really* like it).

Respect to all makers,

[The Dod](https://dubiousdod.org)
