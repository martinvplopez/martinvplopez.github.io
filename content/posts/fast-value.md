---
date: '2026-10-17T20:58:41+02:00'
draft: false
title: 'Fast Value'
description: "Looking back at my own trades to understand how I really invest, and why my way of investing is hard to parametrize."
---

# Why?

Investing has been a part of my life for about four years now. It started as a way to capitalize on my savings, and over time it also became a way to feed my curiosity and try to figure out what's actually true about the world (more on that in another post).

My approach is pretty mixed. I look at fundamentals, a bit of momentum, and a fair amount of intuition/conviction based on coming growth trends. I wanted to check all of that with data, so I built Fast Value[^1]. It scores a company against my own checklist of *green flags* I've thought about across these years: valuation, returns on capital, management behavior, insider trades, trend, volume and the market regime. Then it backtests that score, both on my portfolio and on the market. The goal was just to have a weighted system for all the angles I already look at.

What I ended up valuing most was looking back at my own trades with it. It showed me which decisions the data would have backed, and which ones came from somewhere else.

**disclaimer**: Not financial advice. This is just a hypothesis based on my small sample size in a good market :).

---

## The best signal is no signal? Conviction

The best moment to buy is not something I could find in the data. Big markets are quite efficient and most signals are already priced in. E.g., P/E or insider buying in big caps predicted nothing. The research says it does work in small caps, where fewer people (myself included) are watching[^2].

In my case, "when to buy" signals were really inaccurate. After many runs, the system couldn't tell whether a downtrend was a moment to sell or a moment to buy because it would rebound. The clearest signal I found: *buying a good business when the market says it's not a good time*.

This only pays if the reason for the selloff is temporary and not structural (*coyuntural vs estructural*, as we'd say in Spanish). The tricky thing is that in the moment both have the same symptoms. I'd love to do more research on this topic.

That's where conviction comes in. **Fast Value's rating at the moment I bought didn't separate my winners from my losers**. My two biggest winners today were my two biggest losers in 2025. I kept buying through the lows because I was (and still am) **convinced** the drop wasn't structural.

## Pulling the trigger

I want to go further with this idea after listening to Druckenmiller (btw, with an average 30% yearly track record over 30 years). He describes pulling the trigger as a sort of courage/intuition, not only analysis: "To be willing at the right moment in time to put it all on the line"[^3].

My backtests showed the same thing: my mixed approach made systematic, with fundamentals and trading signals all voting, made less than the index. This is exactly his point: even though you can use data to make an informed decision, the returns come from action under uncertainty.

## It's immensely hard to beat the market

For the last 15 years the S&P 500 made 14.1% a year. The best version of my simulation framework made 15.6%.

*Caveat*: my analysis misses companies that went bankrupt, my run had a worse risk ratio, and with portfolio management fees accounted for, it would probably be the same performance.

It could be seen as cherry picking since it has been a great period for the S&P 500. However, this systematic survival rule (keeping winners in a bag and updating based on market cap), even though simple, is really tough to beat.

## Final Thoughts

If I had only followed Fast Value, would I have done as well as I've been doing? **Not at all.**

This tool didn't give me a formula to beat the index. I don't even think that exists. What it gave me was a way to look back at my own decisions and see which ones the data backs and which ones came from me. The checklist keeps me honest about whether the business behind it still holds.

In my case, the edge comes from conviction in a trend before the data confirms it, patience through the setbacks, pulling the trigger, and following what's actually happening in the company.

I'd recommend doing this with your own trades. You don't need a full backtest. Even writing down why you bought something and checking it a year later teaches you a lot about how you really invest, which is, most of the time, not how you think you do.

Stay curious. Thanks.

![The clock tower on the trading floor of the Madrid Stock Exchange](/images/bme-trading-floor.jpg "My visit to the Spanish stock exchange this year during an investing event.")

### Reference

[^1]: [Fast Value: Multi-factor model of a complex adaptive system](https://github.com/martinvplopez/fastvalue)
[^2]: [Lakonishok & Lee, Are Insider Trades Informative? (2001)](https://doi.org/10.1093/rfs/14.1.79)
[^3]: [Morgan Stanley, Hard Lessons: Stan Druckenmiller (2026)](https://www.morganstanley.com/insights/videos/hard-lessons/duquesne-stan-druckenmiller-iliana-bouzali)

