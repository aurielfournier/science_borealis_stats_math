## Science Borealis Post September 2015

There was a time in my (Auriel's) life, well really there was this entire beginning part of my life, where I hated math. I didn't think it was worthwhile, I wanted to study birds and in my mind that meant I didn't need math. I didn't think I would ever use it and I graduated high school planning to move past this whole math thing and study wildlife ecology. 

The problem is, my mother was right (_again_), and math is super useful. But it took me till I was in graduate school to really understand why and to embrace statistics as something I wanted to learn more about on my own.

In my first year of graduate school I attended a week long statistics workshop on occupancy modeling, and I was sitting there listening to someone with a PhD in statistics talk about statistics and I loved it. That was when it really hit me that my outlook on math and statisics had taken a drastic turn. 

Statistics were really useful (espcially when you can stop doing them by hand) and I was hooked. 18-yea-old me would laugh, long and hard, at this idea, but statistics and I now spend part of most working days together analyzing data, writing code, or working on other parts of the data crunching process. 

Currently I spend quite a bit of time doing hierarchical modeling with an R package 'unmarked'. These models allow us to take survey data of birds (in my case these awesome wetland birds called rails) and model both abundance (our end goal) and detection probability (the probability of detecting a bird, given that it is present) which provides more accurate measures of abundance in relation to different variables (like water depth in the wetland, or observer performing the survey).

This allows us understand how wetland management impacts fall migration of rails. It allows us to compare how densities of rails change over the season to understand the timing of their migration and to compare the differences in timing between years. 

I do all of my statistics in R, which is a statistical programming language that can be used for a wide variety of types of statistical tests and modeling. You can also use it for data management, cleaning, manipulation, programming and other tasks. It is one of many languages, within wildlife ecology R one of the most widely used, but many fields of science use different languages.

The most recent step in my continuing journey with statistics was deciding to pursue a Masters in Statistics and Analytics along with my PhD in Ecology and Evolutionary Biology during my time here at the University of Arkansas. My PhD was extended a year because of some additional funding (yah!) which opened up some time for me to take a few extra courses. I am very pumped to share what I learn over the next two years about statistics with all of you and help you understand why statistics are so useful, why they are important for everyone, and what is currently going on in the world of math.

## Andrew's words

-- messages: I'm a a field ecologist who programs: ---

I first saw real quantitative ecology in a small shack, on a deserted island hidden in the Atlantic fog.

I was an undergraduate, and this was my first real field course: two weeks on [Bon Portage Island](http://www.acadiau.ca/~dshutler/PIsland.html), off the coast of Nova Scotia. As in all field courses, we did lots of group fieldwork -- counting periwinkles and _Fucus_ sp., counting birds, measuring plants. As we were preparing our final projects, Professor Dave Shutler sat in a small shed behind the main classroom. Each group would troop down the hill to where he sat in the fog, and read out the data from our smudged yellow Write-in-the-Rain notebooks. He'd type the numbers in, hit a few buttons, and run something called a "GLM" (a Generalized Linear Model).

In that moment, statistics wasn't some vague, plodding subject about flipping coins. Statistics was deeply connected to the animals, plants and environment of this small island. At the same time it was still very mysterious to me, my knowledge of it was small and indistinct as that tiny island in the Atlantic fog. 

Then, during my Masters, I met a tropical ecologist named Cam Webb, who introduced me to something called "R". R is a programming language that specializes in working with data and statistics. I loved it. It's an excellent tool for a field ecologist (or any scientist): freely available, flexible, and with a huge community to help a beginner learn. I switched to R for doing all the statistics and plots for my Masters.  But it wasn't until my PhD that I actually took a live class in R -- this was from [Software Carpentry](https://software-carpentry.org/), an organization that helps scientists teach _other_ scientists how to program. I learned a lot of good R programming from Software Carpentry, and this last year I finally signed up to become an instructor! That's how I met my fellow editor, Auriel Fournier!

Right now I am studying the community of invertebrates that lives inside plants called bromeliads. Bromeliads are found all throughout the Neotropics. The collect rainwater in their leaves, and lots of small flies, beetles and damselflies live in these tiny pools of water. They're really great for studying ecology in small, discrete habitats. To understand them, I spend a lot of time in R doing multivariate statistics with [vegan], generalized linear models (no longer _completely_ mysterious!) and randomization tests. The latter is an important way to think about patterns we see in ecological communities. For example, if you find that some species are only found in large habitats, does that mean that they actually *prefer* large habitats? It could be because larger habitats have more individual animals, and therefore a bigger chance of containing any specific species. Randomization tests let you ask what patterns you would see in your data if there were "no biology" -- in this case, no preference for bromeliads of a different size!

I'm still very much on the journey of learning about statistics -- and this system (I'm actually in Brazil studying bromeliads now!). And I'm really looking forward to sharing my enthusiasm for statistics, math and programming with all of you!

