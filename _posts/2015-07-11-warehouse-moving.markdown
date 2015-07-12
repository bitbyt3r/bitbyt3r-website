---
layout: post
title:  "I'm Movin' This!"
date:   2015-07-11 23:23:23
categories: MAGFest
---

MAGFest has outgrown its warehouse. Years of rapid growth in 
popularity and attendance have been accompanied by significant growth 
in volume of junk to store. Eventually, the warehouse became so full 
that even with two levels to store things in, we completely ran out of 
space. Not to mention that the warehouse ceased to function as a 
workspace long ago, and that we never managed to get people to keep 
things inventoried and sorted, it was time for a bit of change.

The new warehouse is three times as large, and more importantly allows 
us to keep all things on one level. No more carrying heavy things down 
a narrow staircase and using a liftgate to get them onto our truck. 
Our new warehouse is conveniently at dock-height, allowing us to do a 
dock-to-dock load-in. Did you hear that sound? That was the sound of 
every vertebrae of a MAGFest staff member rejoicing.

Another nice feature is the addition of workspace. When we build out 
laptops and servers for MAGClassic, we won't need to lug all bajillion 
crates of gear to a datacenter conference room and back. Now we can 
store, maintain, and stage all of our gear under one roof. For those 
of us in Techops, this should make a huge difference in the amount of 
coordination and time needed to prepare for each event. 

Personally, the largest task I am involved with in Techops is 
deploying the hundreds of laptops used to run registration, 
challenges, panels, and other tasks during MAGFest. Basically we 
deploy a complete corporate network complete with monitoring, 
configuration management, a full network stack, and whatever cool 
thing we are trying this year into the Gaylord and rip it back 
up over the course of a weekend. We have hundreds of machines, miles 
of fiber and copper to run, dozens of switches to deploy throughout 
the event, and no time to do it in. We could not do this without a 
significant investment in prep-work in the months leading up to the 
event.

Two years ago, this prep-work involved one of my brothers and me 
taking all of the MAGFest laptops home and imaging them 
on our parents' kitchen table. This was less than ideal. Last year, we 
bought even more laptops, then took the whole lot in several cars from 
the Maryland warehouse to Virginia to join some fellow Techops and
complete the imaging there.

With open floor space in the warehouse, we can save ourselves the work 
of boxing, moving, and unboxing the laptops by doing the imaging in 
the warehouse. If it seems strange that this is such a big deal to me, 
I should mention that imaging laptops takes place at a fairly large 
scale. The build system is fully automated using 
[Foreman](theforeman.org) -- it really has to be. However, we have yet 
to automate driving dozens of crates of laptops to Virginia and back. 
(Google, looking at you!) I would estimate that skipping this step 
will cut the overall build time easily in a third. This gives me time 
to work on cool things such as MAGCloud. More on that later.

A new space is not without issues, however. Aside from the monetary 
costs, there is a not-inconsiderable amount of staff effort involved 
in moving the warehouse, re-installing the pallet racking, 
renegotiating contracts, plumbing, electrical work, maintenance, etc. 
Moving to the new warehouse means developing a new organization 
system, which is to say, developing an organization system. We have 
been looking at warehouse management software for a while now, but 
even with something brilliant and well-integrated into 
[Über](https://github.com/magfest/ubersystem) we will 
need to convince everyone to keep things up-to-date and to accept the 
delays caused by record keeping. Wrangling a whole warehouse of stuff 
is a lot of work. Convincing everyone to change the way they do so 
could be a nightmare. Fortunately, we have extremely competent staff, 
and the end goal should be well worth the effort.

Overall, I am excited about the new space, and cannot wait to begin 
working in it. 
