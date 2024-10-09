I tried to install this part of systemd, but it wouldn't let me for some reason. It said it conflicted with the systemd base package. But as I was looking over what was in it, I saw this section that looks like it is pulling code from a static memory stored in zram? Is this why no matter what I do I still keep ending up with initrd files that decompress not to a filesystem but to a single microcode update file?

Here is the ukify file that was located in the /usr/lib/systemd folder of the deb package that apt couldn't find but that I found online in a repository that is listed in my sources. Also weird.

