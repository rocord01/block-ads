# Let's encourage ad blocking

If you use an ad blocker, you've probably come across sites which ask you to switch it off. Doing so exposes you to not only ads, but often malware too&mdash;as many Forbes readers [discovered](https://www.schneier.com/blog/archives/2016/02/the_ads_vs_ad_b.html) when they switched off their ad blockers to please the site.

While there are clearly many benefits to ad blocking, many ad-dependent sites are now so desperate for ad money that they detect use of ad blockers by checking to see if their ads have loaded in the user's browser. If they haven't, the user often gets a stern telling off.

In [Why It's Okay to Block Ads](http://blog.practicalethics.ox.ac.uk/2015/10/why-its-ok-to-block-ads/), James Williams writes that in much of the debate around ad-blocking, there's a surprising assumption, from both sides, that "the large-scale capture and exploitation of human attention [is] ethical and/or inevitable in the first place".  He continues

<blockquote>...the question should not be whether ad blocking is ethical, but whether it is a moral obligation. The burden of proof falls squarely on advertising to justify its intrusions into users’ attentional spaces&mdash;not on users to justify exercising their freedom of attention.</blockquote>

The purpose of this little project is to encourage the use of ad blockers. For the time being it's a simple test to see if the user has an ad blocker installed, and a recommendation to install one if they don't. It'd also be nice to let website owners add a small banner/ribbon to their site which lets their visitors know if they're not using an ad blocker (we're running one on FiveFilters.org at the moment).

### Detecting absence of ad blocker

How do we detect if someone is not running an ad blocker? We make a request for a file that most ad blockers will block (at least the ones relying on [EasyList](https://easylist.adblockplus.org/en/)). In this case, we're calling our file `ads.css`. 

### Test site for ad blocking

We've also set up a site&mdash;[blockads.fivefilters.org](https://blockads.fivefilters.org)&mdash;anyone can visit to see if their browser is blocking ads or not. It not only tests for ad blocking, but also checks to see if the browser is letting through 'acceptable' ads&mdash;if it is, you get warned about it. Many users of Adblock Plus are unaware that the company [makes money from whitelisting advertisers](http://www.engadget.com/2016/02/12/rip-adblock-plus/).

### Why do we recommend [uBlock Origin](https://github.com/gorhill/uBlock)?

Because of its uncompromising stance towards ['acceptable' ads](https://github.com/gorhill/uBlock/blob/master/MANIFESTO.md):

<blockquote><p>The uBlock project does not support Adblock Plus' "Acceptable Ads Manifesto", because the "Acceptable Ads" marketing campaign is really the business plan of a for-profit entity.</p>

<p>Users are best placed to know what is or is not acceptable to them. uBlock's sole purpose is to give users the means to enforce their own choices.</p></blockquote>

Technically, it also [performs better](https://github.com/gorhill/uBlock#performance) than Adblock Plus and other ad blockers.

### Feedback!

This is an experimental project from [FiveFilters.org](http://fivefilters.org). Let us know what you think. Feel free to copy, improve, share your changes.

This entry is an edited version of our [blog post](http://blog.fivefilters.org/post/140421322122/lets-encourage-ad-blocking).
