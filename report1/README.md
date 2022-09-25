# A report on the state of current perl

## Brutal list of personal issues
* Modules not working as expected
* No realistic examples
* No cookbook recipes
* Failing tests (async)
* High number of alternatives, to most modules - none of which work 
* Decayed frameworks (POE, ... many many others)
* Smaller specialised modules not working at all (choose a random 10 modules)
* Horrific 90s CGI interfaces to author submission portal (PAUSE)
* Broken intro's to the language 
* Chance of a random selection of 10 modules: having tests, passing tests and then actually functioning is about 1%
* No reasonable ways to offer forks of modules (even if they are on github to begin with)
* No flavour support
* Lack of standard style throughout entire community
* Lack of a standard set of modules that are carefully picked and updated
* 

# Blog

First of all, let me start with an apology

I am not in the set of people who can make clean well crafted reports, before this blog I attempted it but ended up 
coming back to the simple fact that the subject and points I wish to raise I have no idea how to do in a strict mannor.

So with that being said, I reverted to typing freely in a blog fasion in the thought that it can be a prototype to a 
formal report, it seems even in writing I will forever be a rapid prototyper.

I will also state that this is entirely of MY OPINION and there is no white or blacks, its always grey.

## The problem with perl is perl

Perl to me has always been a wonderful tool, you can do anything with perl and very often do.

But it also is a fairly old little binary, I have never sourced the truth of if larry walls true intent was to replace 
awk sed grep and friends with a single utility that can do everything, but well if that was his true intent, he succeeded.

So with that being said, it should be plain sailing to the end of days ... but no, there be sharks in these waters.

### Why perl is where it is

This is an awkward one, why is perl such a small community now but such an important one, what happened.

Every perl developer will have a different belief on why perl got so big at the end of the 90s but I tend to think it was 
due to CGI and the boom in website development, with php in its infancy perl was 'the one to use'; given its flexible 
nature you could get it to do almost anything.

So the influx of developers and interested companies was massive, including the BBC for iplayer in the mid 2000's

With this much interest combined with the flexibility of anyone being able to publish a module, further combined with 
development in every direction, the userbase flourished; it actually reached the heights of being quite elitist at some
points but that is neither here nor there at the current point.

So you have arguable the most used language in the world coming up to the millenium, due to the flexibility of CGI; 
driven by the booming web.

### Absolute flexibility for absolute carnage

As human beings we tend to like the idea of being in an open field, the world to be shaped by our hands and desires.

And this is great, if you happen to be an engineer in a field, but for a programming language that entire OS's depend 
upun, including libs such as openssl (b-dep) it can get a little messy.

There is no standard way to write perl, you can write it how you define it almost, which is great you can be as OCD 
NamedasYouLine as you desire, but this is meant to be a community orientated language is it not?

If its a community language where others have to get involved should'nt there be a baseline standard?

Should there not be a standard style, you can wander from if you wish but generally is required for most normal 
development? Strangely when I look at perl.org and all its wonderous insights I happen to not see one.

I feel odd writing these words, but my original point was the problem with perl is perl ... with no style guide there 
can be no standard way of doing anything either. Comically tmtowtdi is what I am targetting here, its really cool 
having alternatives but in the long run someone needs to keep all those alternatives 

### Re-inventing the wheel

Why re-invent the wheel? there is 30 modules that already do what you need ... why is there 30 modules?

In perl-land because of the lack of any focus and adherence to any specific standard, more often than not the easiest 
path is the one you create yourself.

There are exceptions of course the HTTP::* suite for instance; but due to the lack of examples in most cases and the 
absolute hostility between different systems be the object orientated or otherwise, to be in the mind of the author of 
most modules is far more difficult than just writing it yourself.

Very likely adding module 31 to the stack already on cpan.

This seems to 