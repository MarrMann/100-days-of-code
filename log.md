# 100 Days Of Code - Log

### Day 1: January 23rd, Saturday

**Today's Progress**: I fixed my edge detection algorithm for *edge* cases (heh).

**Thoughts** Took me like 30 mins to even get back into the project. I think it could use quite a cleanup and the edge detection could be made easier to read.

**Link(s) to work**
1. [Tweet with pics](https://twitter.com/MarrMany/status/1353103805798371329)


### Day 2: January 24th, Sunday

**Today's Progress**: Refactored edge detection and accidentally fixed a bug at the edges (uh, tips?) of the edge detection.

**Thoughts** Was gonna improve the API by packing everything into a nice class, but hey, fixed the detection instead and cleaned up code.

**Link(s) to work**
No links!


### Day 3: January 25th, Monday

**Today's Progress**: Refactored most mesh analysis stuff into MeshAnalyserUtils and almost finished work on a more effeicient MeshAnalyser (1 loop > 2 loops). Also accidentally introduced a bug.

**Thoughts** I gotta get this done earlier in the day, doing it just before 24 kills me. Set a timer, mute *everything*. Friends and family can wait 1 hour.

**Link(s) to work**
1. [Tweet with pics of bug](https://twitter.com/MarrMany/status/1353832309208866816)


### Day 4: January 26th, Tuesday

**Today's Progress**: Finished refactoring and fixed existing bugs. Slowly started work on hole detection

**Thoughts** Muting everything worked, but I feel super fucking stressed with everything I have to do every day already. Let's see tomorrow...

**Link(s) to work**
1. [Tweet with pics of no bugs](https://twitter.com/MarrMany/status/1354167129524891650)


### Day 5: January 27th, Wednesday

**Today's Progress**: I'm a grade a retard today and couldn't figure out how to detect holes, no progress.

**Thoughts** I hate banging my head against a wall, hope today will be better.

**Link(s) to work**
No.


### Day 6: January 28th, Thursday

**Today's Progress**: Got over my retardation and figured out a super smooth way to figure out if something is a hole. Made an Edge entity class

**Thoughts** Finding the simplest solution is often a good thing, it just takes a bit of time.

**Link(s) to work**
No.


### Day 7: January 29th, Friday

**Today's Progress**: Hole finding.

**Thoughts** Don't remember.

**Link(s) to work**
No.


### Day 8: January 30th, Saturday

**Today's Progress**: Hole finding.

**Thoughts** Don't remember.

**Link(s) to work**
1. [Tweet with pics](https://twitter.com/MarrMany/status/1355655665902039040)


### Day 9: January 31st, Sunday

**Today's Progress**: I don't actually remember, writing this on day 10.

**Thoughts** None.

**Link(s) to work**
No.


### Day 10: February 2nd, Tuesday

**Today's Progress**: Refractored Edge class into Edge, ExtrudedEdge, and GridEdge. Added methods for extruding edges.

**Thoughts** Looking forward to testing extrusion tomorrow! Need to figure out how to connect edges, but should be pretty simple.

**Link(s) to work**
No.


### Day 11: February 4th, Thursday

**Today's Progress**: Extruded edges succesfully!

**Thoughts** Missed another day but oh boy I made a lotta progress today! Extrusion works! I'll have to double check a few things, but for now I'm just stoked that it works!

**Link(s) to work**
1. [Tweet](https://twitter.com/MarrMany/status/1357407961337970689)


### Day 12: February 5th, Friday

**Today's Progress**: Fixed an off-by-one bug

**Thoughts** Prolly gonna have to do a bit more bug-fixing and making a function for filling holes.

**Link(s) to work**
Nope!


### Day 13: February 7th, Sunday

**Today's Progress**: Fixed a small scaling issue, played around with extrusion.

**Thoughts** I really needed the weekend off so it was good to just play around with the tool rather than making big changes/progress.

**Link(s) to work**
1. [Twittytweet](https://twitter.com/MarrMany/status/1358468721405263875)


### Day 14: February 8th, Monday

**Today's Progress**: Corrected stuff in my pull request and finished the merge. Then started implementing heightmaps.

**Thoughts**: Heightmaps should be real easy tbh. I'm getting pretty bored at home and behind schedule with other stuff tho :(

**Link(s) to work**
Not today my friend!


### Day 15: February 9th, Tuesday

**Today's Progress**: First iteration of heightmaps.

**Thoughts**: Took a little longer than expected, plus today was a super unmotivated day, but hey I managed to do this at least. Need good sleep and waking up earlier.

**Link(s) to work**
1. [TweetMcTweet](https://twitter.com/MarrMany/status/1359265285115633668)


### Day 16: February 10th, Wednesday

**Today's Progress**: Fixed a buncha bugs for heightmaps.

**Thoughts**: I kinda want to work on performance, but I don't see a way to improve it without making the code less readable. This'll do for now.

**Link(s) to work**
1. [What's with the face?](https://twitter.com/MarrMany/status/1359601132717432841)


### Day 17: February 11th, Thursday

**Today's Progress**: Researched linear interpolation for marching squares.

**Thoughts**: I think I get it, I found an easy way to convert the formular to my system, gonna give it a try.

**Link(s) to work**
1. [Metaballs and Marching Squares (not made by me, this was my research)](http://jamie-wong.com/2014/08/19/metaballs-and-marching-squares/)


### Day 18: February 13th, Saturday

**Today's Progress**: Attempted to implement interpolation, sort of worked.

**Thoughts**: I'm sure I've done something wrong, it's like it has the opposite effect of what I want so I'm gonna look into that.

**Link(s) to work**
1. [Confusing tweet, confusing image](https://twitter.com/MarrMany/status/1360686476586016768)


### Day 19: February 14th, Sunday

**Today's Progress**: Holy fuck I got interpolation working and it's so fucking good what. This is the biggest milestone on this project so far by a fucking longshot.

**Thoughts**: What the fuck it actually works. This was the task I was dreading the most, I thought this would take me WEEKS of headaches to get working, instead it took... 3 hours spread across 3 days lmao.

**Link(s) to work**
1. [Best tweet](https://twitter.com/MarrMany/status/1361038996269371398)


### Day 19-22: February 15-18, Monday-Thursday

**Today's Progress**: Refactored and fixed Grid into IGrid, BaseGrid, and SmoothGrid.

**Thoughts**: Maaan refactoring is demotivating for me, but I can't deny it's so much easier to work with now.

**Link(s) to work**
1. [Switching between grids](https://twitter.com/MarrMany/status/1362509222051799045)


### Day 23-24: February 19 and 21, Friday and Sunday

**Today's Progress**: Started working on flatshaded meshes

**Thoughts**: Started to feel like I was hitting a wall with all the refactoring, so I decided to work on flatshading instead and refactor as I go.