# Let's encourage ad blocking

[![Bill Hicks on advertising](https://img.youtube.com/vi/jemqAtxKyAo/0.jpg)](https://www.youtube.com/watch?v=jemqAtxKyAo)

**[Are you protected against ads?](https://blockads.fivefilters.org)**

Ads are everywhere on the web. They're not only annoying, but they're used to track you and expose you to [malware](https://en.wikipedia.org/wiki/Malvertising). The good news is that it's not that difficult today to block most of the advertising you come across by simply installing a browser extension.

If you already use an ad blocker, you've probably come across sites which ask you to switch it off. In doing so, they're exposing you to threats they themselves do not control&mdash;as Forbes readers [discovered](https://www.schneier.com/blog/archives/2016/02/the_ads_vs_ad_b.html) when they did just that at the behest of the site and got infected with malware.

Many ad-dependent sites are now so desperate for ad money that they'll give you a stern telling off if they find you're using an ad blocker, or prevent you from seeing their content until you turn it off.

In [Why It's Okay to Block Ads](http://blog.practicalethics.ox.ac.uk/2015/10/why-its-ok-to-block-ads/), James Williams writes that in much of the debate around ad-blocking, there's a surprising assumption, from both sides, that "the large-scale capture and exploitation of human attention [is] ethical and/or inevitable in the first place".  He continues

<blockquote>...the question should not be whether ad blocking is ethical, but whether it is a moral obligation. The burden of proof falls squarely on advertising to justify its intrusions into users’ attentional spaces&mdash;not on users to justify exercising their freedom of attention.</blockquote>

The purpose of this project is to test for and encourage the use of ad blockers. 

For the time being it's a simple test to see if you have an ad blocker installed, and a recommendation to install one if you don't. We do not believe in '[acceptable advertising](https://github.com/fivefilters/block-ads/wiki/There-are-no-acceptable-ads)' so we also try to test for that and suggest a better adblocker if we detect it. 

Our tests are still quite primitive so will not detect all blockers. But then again, we are testing for things we feel should be blocked, so if yours isn't blocking them, perhaps you want to change it or update its settings. 

### Test site for ad blocking

The code here is running on our site at: [blockads.fivefilters.org](https://blockads.fivefilters.org)

Feel free to share that page with anyone you feel could benefit from more ad blocking. It not only tests for ad blocking, but also checks to see if the browser is letting through 'acceptable' ads&mdash;if it is, you get warned about it. Many users of Adblock Plus  are unaware that the company [makes money from whitelisting advertisers](http://www.engadget.com/2016/02/12/rip-adblock-plus/).

### Why do we recommend [uBlock Origin](https://github.com/gorhill/uBlock)?

Because of its uncompromising stance towards ['acceptable' ads](https://github.com/gorhill/uBlock/blob/master/MANIFESTO.md):

<blockquote><p>The uBlock project does not support Adblock Plus' "Acceptable Ads Manifesto", because the "Acceptable Ads" marketing campaign is really the business plan of a for-profit entity.</p>

<p>Users are best placed to know what is or is not acceptable to them. uBlock's sole purpose is to give users the means to enforce their own choices.</p></blockquote>

Technically, it also [performs better](https://github.com/gorhill/uBlock#performance) than Adblock Plus and other ad blockers.

### Feedback!

This is an experimental project from [FiveFilters.org](http://fivefilters.org). Let us know what you think. Feel free to copy, improve, share your changes.

This entry is an edited version of our [blog post](http://blog.fivefilters.org/post/140421322122/lets-encourage-ad-blocking).
