# Open-source vs Monetization

Most people would argue the monetization and open-source are mutually exclusive.  After all, how do you charge money for something that can be freely copied?

There are several existing strategies, mentioned below.  People have been trying to do this for a long time.  Open-source projects have tried to collect donations and encourage businesses to support their projects, with varying levels of success.

The important point here is to understand that:
1. monetizing open source software is inherently challenging
2. it can be done
3. it's extremely important for the success of the open source project

I have a few two unique strategies for accomplishing this: [source code encryption and access control](encrypted-source-code.md), and granular [api licensing controls](advanced-api-licensing.md).

## Segmentation

You separate your code base into 2 layers.  The most basic functionality becomes your free tier (and gets open-sourced), and the premium features remain closed-source.

This allows you to gain momentum from the open-source community, while keeping a competitive advantage.

This is probably the safest option, in the sense that your premium features are never actually published.

## Viral license trap (Dual license strategy)

The "viral" open-source licenses require you to use the same (viral, open-source) license for your software, if you use their software.

For example, if you want to embed MySQL into your own software, you either need to open source your software, or buy a license to avoid this condition.  Many startups can't justify open-sourcing their platforms, but they can opt to license the software.

This allows the software to benefit from being open source (allow anyone to contribute to it), and also allows the producer to charge money.

The code is public, so there are no physical protections, just the legal implications.
