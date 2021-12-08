# VMware host runit scripts

**This is unlikely to be maintained or fixed from its current state. I'm only putting it up for potential future use. Use at your own risk.**

A set of shoddy runit scripts to get VMware running on runit-based systems. To use them, copy the contents of the `sv` folder into `/etc/runit/sv/`, make the scripts executable and link them to your current runlevel.

**To do:**
- A proper readme.
- Makefile or package.
- Sort out service dependencies.
