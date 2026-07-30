# Reflections
## What did you repeat by hand?
I repeated a lot of things by hand, mainly the skeleton, nav, header, and footers.
This was a little annoying and time consuming -- I ended up having to copy paste this
across every single one of the pages, and when I'd made changes to the `nav` tags as I
expanded the page, I had to repeat this process.

Other things that I'd repeated by hand but probably didn't need to would be the ids for
view transitioning from the guide/index to the specific cheese page. I'm sure there would
be some different way to go about this, but I chose the easiest path by taking some suggestion
on Slack to use div background + ids for the view morph.

## What broke when you moved a file? 
Nothing really broke when I moved a file, but that's just because I've managed to change things
such as relative links before actually moving them. For example, I wasn't paying attention to 
the proper directory structure and had to move all my guide and subentries into the guide 
sub-directory, in which case I had to change all the links inside of guide/index and
soft/hard/blue/fresh. Along with this, I had to modify all the nav tags for the guide subpages
and everything else to link properly.

## What would you want a tool to generate for you? 
I'd probably want a tool to help me insert key pieces by themselves. As I mentioned above, things
that I had to repeat that were identical over almost all pages were the nav and footers. It would be
nice to pre-construct these HTML fragments and then insert them as needed automatically via some
sort of tool.

Furthermore, it would be very nice to have stuff like nav be automatically generated and the links to be 
automatically updated through some sort of directory index, like I've seen in some of the
sneak peeks of HW5.