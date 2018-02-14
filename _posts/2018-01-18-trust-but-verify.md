---
layout: post
title: Trust But Verify
---

![]({{ "/img/woman-trust.jpg" | absolute_url }})

It's a well-known fact that security and convenience are on opposite sides of the spectrum. If you want to be hyper-secure it will cost you considerable convenience.

What this dictum boils down to is you have to choose your level of comfort based on — among other things — how much you trust you have and you require.

For example, I recently migrated this blog from a $10/month DigitalOcean VPS instance to a $7/month Heroku dyno. Having done that I don't think I will ever look back. But it wasn't such an easy decision.

# Paranoia

Cutting my teeth on dedicated servers I picked up a way of thinking that can best be described as If it's not my network — I don't trust it (Thanks for the saying Darren Kitchen).

I'll admit it — I had kind of an anarchist/libertarian philosophy when it came to tech. Especially after discovering just how much organizations like the NSA had worked to create less secure standards and forced the back door data sharing agreements with big companies.

As a Christian minister and a techie, I often played with scenarios like:

- What if restrictive state policies come into play and they demanded user data from us?
- What if users from a repressive state can't access our websites?
- What if we use a SaaS that one day refuses to give us our data?

Add huge breaches by hackers to concerns about Advanced Persist Threats and it seemed like nothing short of building a decentralized architecture with peer-to-peer file-sharing and paying for servers with stolen bitcoin would do it. Okay, not really stolen, but you get the point.

Anyways, over time I realized something — we all make decisions to trust what we really can't trust.

# Externalized Trust

For example, if you have a bank account you have no real assurance that your bank isn't doing something nefarious with your money right now. Like stealing 1/2 cent like in Superman III.

Mathematicians and philosophers alike use tools to be able to fully verify the veracity of a claim. As a developer, the best way to make sure that an app is doing what it is supposed to is look at the code and run the tests.

Well, yeah you can't do that with your bank. Go ahead and try. I'll be waiting.

Using the word trust in a concrete mathematical rigor kind of way, you have to implicitly trust your bank 100% a priori.

But you might counter and say: "But we do have verification — There is no proof what so ever that a bank does something nefarious with your money".

Well, the smartass in me wants to say something about the fractional reserve system, but the point is that just because you don't have proof, doesn't mean they don't do it.

To cut to the chase, the only proof you can have is social proof. Everyone trusts banks with their money, so we can externalize the trust process and just believe that banks are safe.

In the example of banks, social proof includes things like FDIC guarantees — despite the fact in an emergency they would have to borrow money from the same system that would be in crisis — and fraud laws.

It's not perfectly verifiable but for most people, it's enough. And that is what the whole trust issue boils down to — how much is enough.

# A Page From Religion

The same issues of trust can be found in the debates surrounding the validity of religion.

An atheist might say: "I don't have to disprove that God exists, I just can't find any evidence that God exists, or in the case of Christianity, that the gospel accounts are historically true".

An honest Christian might respond: "I don't have 100% proof that the New Testament accounts are historically accurate because of the doubts raised by textual criticism, but the evidence that I do see is enough for me".

To which the atheist would say: "Well, my interpretation of the same data is enough for me."

All that to say — if the biggest questions in our lives come down to deciding how much proof is enough, then surely the same applies to technology.

# Pragmatic Conclusion

The more I read about internet security the more I realized that my real threat model was so small as to be almost inconsequential.

Furthermore, there are real benefits to giving up perceived and actual autonomy.

In moving from a dedicated server to a virtual server I got more fault tolerance in exchange and the ease of spinning up a new server in a minute.

In moving from a VPS to Heroku, I got the ability to iterate with much more freedom and deploy and rollback with confidence.

In closing, the anarchist in me will always want absolute verifiability. But that's just not ever going to happen for everything in life.

Plus, if I'm honest, often by giving up absolute verification you get something of superior quality in return than anything you could make yourself.

If a company has the money to hire geniuses, their product will probably always be better, unless FUD applies.

So to sum it — pick your level of comfort, verify as much as you can, and get back to work building something awesome that people use.