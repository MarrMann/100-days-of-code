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

**Today's Progress**: Thought I found a really nice way to find holes and their direction, turns out I was wrong. Didn't have enough time to do exactly 1 hour today either.

**Thoughts** Welp, back to the drawing board.

**Link(s) to work**
No.


### Day 8: January 30th, Saturday

**Today's Progress**: Went back to detecting clockwise/counterclockwise by using an algorithm which gets the area*2 of the polygon. Negative numbers mean it's a hole!
Holes are now getting bound to their belonging islands so each island class contains the edge and hole.

**Thoughts** I really like working on a laptop. Maybe it's the limiting factor of only having 1 screen? The shitty mouse meaning you use more shortcuts? Idk...

**Link(s) to work**
1. [Proof!](https://twitter.com/MarrMany/status/1355655665902039040)
2. [StackOverflow answer (much love)](https://stackoverflow.com/questions/1165647/how-to-determine-if-a-list-of-polygon-points-are-in-clockwise-order)