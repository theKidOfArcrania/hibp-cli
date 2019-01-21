# hibp-cli

Simple CLI that queries Have I Been Pwned (HIBP) servers.

This is a small shell program that I wrote that has some simple command line
arguments that you can pass to it. Part of the reason for writing this is
because I do not trust third party web servers that take passwords (even though
I think it only actually processes the first five letters of the sha1 hash
server side...).

It is also a pretty cool learning experience of using bash shell. Also if you
play around enough with the different passwords that are pwned, you realize that
a lot of them are very creative, but still doesn't work ;), for example
`thisisasecurepassword` has been found 10 times as of this writing (so I guess
it really isn't that secure after all :P ).

This is licensed under GPLv3+ license
