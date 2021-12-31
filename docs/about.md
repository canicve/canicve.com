# About

TL;DR - Blue team member? Find out if you're impacted by a CVE! Red team member? Find out if a CVE exists for your target and if a PoC has worked on that target before!

## Blue Team

Defense is hard. You're literally flooded with notifications, advisories, tweets, and emails every day - 'blahblahblah' was hacked today, 0day for X was released, vendor released patch for Y - it's exhausting... Don't get me wrong - we're doing alot better than we were - but we're not 100% there yet. This site is an attempt to consolidate relevant information based on CVE number, Linux kernel release (in a terminal run: uname -r), and software version. Supplied with any of these values - if a CVE exists (and is in our database), a nice page will be returned showing a little bit of information on the CVE - and two tables: vulnerability and links.

## Red Team

Ever been on a box and wondered if a CVE exists for it? Google doesn't have any results...and github is returning a bunch of rick-roll projects...Well, provide this search a kernel release (uname -r), software version, or CVE (if you know one) and it will return (if a CVE exists and is in our database), a summation of the CVE - and two tables: vulnerability and links. If we've tested the PoC and it's listed in the vulnerability matrix - it should work on your target too. PoCs which are good, but we've not tested for certian versions will be listed in the links section (YMMV).

Visit https://oss-security.openwall.org/wiki/vendors if you have something you would like a vendor to look at.