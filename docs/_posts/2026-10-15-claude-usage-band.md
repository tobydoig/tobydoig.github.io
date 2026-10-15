---
layout: post
title: "Claude usage band"
---
When using Claude Desktop (aka Claude Code) the little circle used to tell you how long until a compaction will happen. At some point this changed to your
token usage, only it shows your weekly usage rather than (what I think is more important) your session usage.

![Free on Github](https://github.com/tobydoig/claude-usage-band)

Anyway, this little plugin shows your session token usage, weekly token usage and your context window usage.

![Claude usage band screenshot](/assets/img/claude-usage-band.png)

Session usage = the %age of tokens you've used in this session. When it hits 100% you have to wait for it to reset (up to around 3 or 5 hours)
Weekly usage = the %age of tokens you've used this week. When it hits 100% you have to wait for it to reset (for me that's Friday afternoon, just after lunch)
Context = what %age of your model's context window is used. When it hits around 100% the compaction happens, which takes many seconds.

It updates periodically, which is nice.
