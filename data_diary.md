# Data Diary: Most of Earth Belongs to No One

## Where the data came from

I used the Visual Capitalist "Earth's Surface" infographic as my primary source rather than going straight to the UN Statistics Division data. Honestly? The raw data is a mess of tables and I was working with a tight deadline. The infographic had already done the heavy lifting of calculating percentages of Earth's total surface area. For a few smaller values that weren't explicitly labeled, I estimated based on the visual proportions in the original graphic.

I grouped smaller countries into "Rest of World" because showing all 195 countries would have been unreadable and missed the point. The story isn't about memorizing every country's slice. It's about the pattern: even the biggest players own almost nothing.

## Why bubbles instead of bars or maps

I considered bar charts, but they felt too clinical. The whole point was to make people *feel* how small land ownership is compared to the ocean. Circles scaled by area do that better than bars. When you see Russia as a circle next to international waters, the disparity hits differently than two bars of different heights.

Maps were tempting but would've reinforced exactly what I was trying to critique: the idea that borders are the natural way to see Earth. Plus, you can't easily show "international waters" on a traditional map without it looking like leftover space.

I used square root scaling for the circle areas so the visual perception matches the actual proportions. If you just scale the diameter linearly, larger values look way bigger than they actually are proportionally.

## The three-chart structure

I wanted a zoom-out effect:

1. **Chart 1** shows what we think matters: countries, territory, the stuff we fight wars over
2. **Chart 2** pulls back to show the three real categories: land, territorial waters, and international waters
3. **Chart 3** delivers the punchline: the lawless majority is bigger than everything else combined

That arc felt more compelling than just showing all the data at once.

## The editorial angle

The assignment asked us to turn an infodump into a narrative, and the ocean angle wrote itself once I looked at the numbers. The original infographic treats all these categories neutrally, but neutrality felt like a cop-out when the data is literally showing that we've spent centuries fighting over less than 30% of the planet.

The "colonialism extended offshore" framing for EEZs might be spicy, but it's historically accurate. The Law of the Sea Convention was basically powerful nations formalizing their claims before anyone else could.

## What I cut

I originally wanted to start with the Visual Capitalist infographic and have it "melt" or tear away to reveal my version. It looked terrible. Sometimes the clever idea isn't the good idea.

## Tools

The three charts were designed in Adobe Illustrator and exported using ai2html for responsive sizing. I used Claude to help with the web design, CSS, and getting the responsive breakpoints to work. The Pangea scroll animation uses Intersection Observer. Writing and editorial choices were mine.
