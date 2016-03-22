# Sealed Cities - Soil Sealing in European Cities




























I morphed the map into a chloropleth, accounting for the different degrees of soil sealing, and added tooltip events that display the average % of soil sealed across the cites of one country, when hovering on the country.


























### Udacity Forums

*DAND P6 | Data Visualization with D3.js | P6: Make Effective Data Visualization*

[**Early feedback for final project under construction (includes little trees and houses ; )**](https://discussions.udacity.com/t/early-feedback-for-final-project-under-construction-includes-little-trees-and-houses/160913)

*martin-martin4d2*

One big part of this Section of the ND is to get and incorporate feedback from others, so I decided to put this out in the current state.

It's not finished, but I'd be glad for feedback in this early stage.

There's a map, and there are individual 10x10 images squares that will represent each clickable country. And what? The percentage of soil sealing in European cities: [https://gist.github.com/martin-martin/f7367d6de3701c2e21a7](https://gist.github.com/martin-martin/f7367d6de3701c2e21a7)

: )

The idea is to display the map as the first and only thing on the page, and then pop-up modal boxes with the individual %-visualization regarding the cities of the clicked country.

Do say, compliment, criticize (especially this) - maybe it'll help me to develop the visualization into a better direction without getting too stuck with my image. I might also be stuck with it, just saying ; )

---

*martin-martin4d2*

... maybe too early. Didn't yet managed to make it work on gist/bl.ocks, so I draw my daring post back in... : )

---

*stefan_1537033d*

@martin-martin, have a look at https://pages.github.com/1 , Gists are better suited for 1-3 files, I think.

---

*martin-martin1d*

Thanks @stefan_153703, this was a good idea!

-

Here it comes: [http://martin-martin.github.io/sealed_cities/](http://martin-martin.github.io/sealed_cities/)

This is the first version where the functionality seems fine. I did not yet style it much, so it's an unpolished look. But I'm also up for style suggestions, although I have some ideas on how to do it.

I'm putting this out like this because I think that a big part of this project is to receive and iterate upon feedback that others give, so I'm excited to hear your thoughts! : )

Thanks!

---

*stefan_1537037h*

@martin-martin, Your visualization of the country details using symbols is making things clearer for me. I think it would be great to have a simple version of that in the overview map already, so that it is easier to compare countries. Choropleth?

---

*martin-martin4h*

Hei @stefan_153703!

How do you mean this? A legend for the three different colors I'm using on the start page?

e.g.
```
-----------------
(green)  <  40%
(orange) >= 40%
(red)    >= 50%
-----------------
```
Yeah, I think it's a chloropleth : )
At least that's what I think it is.

Or do you mean having the symbols somehow on the overview map?

---

*stefan_1537033h*

Sorry, I hadn't seen the last version. Just if you could see all country colors at once, for the big picture.

---

### G+ Data Analyst Community

*Martin Breuss9:15 AM*

[http://martin-martin.github.io/sealed_cities/](Martin Breuss
Discussion  -  Yesterday 9:15 AM)

My P6 data visualization : D

I'll be gladly taking in your feedback, considering thoughtfully, and trying to implement what I like and manage to!

Thanks a lot. I like feedback ; )

Both getting and giving it.﻿

---

*Andrew Bauman10:12 AM+1*
 
Wow, this is a really great visualization.  Soil sealing is a hot topic in the Pacific Northwest (where I live).  For me it would be useful to see the color code initially (see which countries are in green, yellow, or red state).  currently you can only see that info on hover.  To this end I might suggest adding showing the color code of the country along with a legend for the % sealed range encoded by each color.﻿

---

*Andrew Bauman10:15 AM*
 
oh, I really like the grid on click, that 10 - 10 with each tile = to 1% is very informative.  ﻿

---

*Andrew Bauman10:17 AM+1*
 
ah, one other thing, since values for each country represent the mean of several cites, consider giving the viewer the following information.  Min, max, mean, median (mean you already have).  This would allow the audience to get an idea of the distribution of the data.﻿

---

*Jenny Lu12:09 PM+1*
 
Your visualization is really great! My only comment is that I have no idea what soil sealing is so maybe if you were to add a little blurb somewhere explaining what it is and why it's important?﻿

---

*Martin Breuss12:29 PM*
 
Yay! Thanks +Andrew Bauman  and +Jenny Lu !
Good points you put! : D

I like a bit the discovery of running over the map with the mouse - but I'll try to add a button so one can switch on the map color for all countries at the same time by choice.
Distribution is actually quite crucial, that's true. Because it actually makes quite a difference sometimes and my visualization doesn't show this at all.

And sure I'll try putting a little info blob somewhere : )
There's a link up-right, but I'll get the info right inside!

Thanks you two! : )﻿

---

*Martin Breuss12:51 PM*
 
By the way discovery: Who can find the country with the lowest average soil sealing ; )﻿

---

### Slack Data Analyst Group

Hello @channel ! : )
I’ve finished the functionality (= raw version) of my data visualization, and wanted to ask for your feedback.

I decided to give it out early, because I think a big part of this project is to receive and iterate upon feedback!

So I’m looking forward to what you have to say.
[http://martin-martin.github.io/sealed_cities/](http://martin-martin.github.io/sealed_cities/)

Thanks! : )

---

*cms_6813 [1:40 PM]*

@martin-martin: I like the elegance of your vis so far. While looking around it a bit gives a sense of what the colors mean, a key would help - and I'm sure you're working on it. Maybe you could design the key so that when you click on a color in it, the countries in that category are highlighted on the map.

---

*martin-martin [1:45 PM]*

Hei @cms_6813 ! Thanks for you reply : )
I’m thinking about doing some kind of legend for the colors - your idea of highlighting the same-colored ones sounds interesting too.
I might be lonely in this, but I actually like the fact that it’s all gray and you discover which is which only by mouseover… : )

[1:45] 
I was thinking of adding a button to optionally switch on all the colors on the map.

---

*cms_6813 [1:56 PM]*

I would say it depends on your goals for what the audience should get out of it. I look forward to seeing the next iteration!

---

*martin-martin [2:25 PM]*

: )
I’ve actually already been working on it forward since I posted here! Mouseover and some styling wasn’t available initially ; )

---

### Data

- **soil sealing data (cities):** [http://www.eea.europa.eu/data-and-maps/figures/degree-of-mean-soil-sealing](http://www.eea.europa.eu/data-and-maps/figures/degree-of-mean-soil-sealing)
- **geoJSON:** [http://grokbase.com/t/gg/d3-js/1372gq18j9/geojson-maps](http://grokbase.com/t/gg/d3-js/1372gq18j9/geojson-maps)
- **soil sealing data general (ancestor dataset):** [http://www.eea.europa.eu/data-and-maps/figures/degree-of-soil-sealing-as](http://www.eea.europa.eu/data-and-maps/figures/degree-of-soil-sealing-as)

### Assets
- **little house:** [http://www.clipartbest.com/cliparts/dTr/zby/dTrzbyLT9.png](http://www.clipartbest.com/cliparts/dTr/zby/dTrzbyLT9.png)
- **little tree:** [http://www.micnatur.pt/img/tree.svg](http://www.micnatur.pt/img/tree.svg)

### d3 info
- **tutorial:** [http://alignedleft.com/tutorials/d3](http://alignedleft.com/tutorials/d3)
- **csv:** [https://github.com/mbostock/d3/wiki/CSV](https://github.com/mbostock/d3/wiki/CSV)
- **linking csv:** [https://discussions.udacity.com/t/linking-csv-with-d3-js/160222](https://discussions.udacity.com/t/linking-csv-with-d3-js/160222)
- **getting data:** [https://leanpub.com/D3-Tips-and-Tricks/read#leanpub-auto-getting-the-data](https://leanpub.com/D3-Tips-and-Tricks/read#leanpub-auto-getting-the-data)
- **parsing data:** [http://learnjsdata.com/read_data.html](http://learnjsdata.com/read_data.html)
- **joins:** [https://bost.ocks.org/mike/join/](https://bost.ocks.org/mike/join/)
- **data in DOM:** [https://www.dashingd3js.com/using-data-bound-to-dom-elements](https://www.dashingd3js.com/using-data-bound-to-dom-elements)
- **binding data:** [https://bost.ocks.org/mike/circles/](https://bost.ocks.org/mike/circles/)
- **bar chart:** [https://bost.ocks.org/mike/bar/](https://bost.ocks.org/mike/bar/)
- **range:** [https://github.com/mbostock/d3/wiki/Arrays#d3_range](https://github.com/mbostock/d3/wiki/Arrays#d3_range)
- [http://stackoverflow.com/questions/18991680/d3-trigger-mouseover-event](http://stackoverflow.com/questions/18991680/d3-trigger-mouseover-event)
- [http://www.d3noob.org/2013/01/adding-tooltips-to-d3js-graph.html](http://www.d3noob.org/2013/01/adding-tooltips-to-d3js-graph.html)
- **legend:** [http://zeroviscosity.com/d3-js-step-by-step/step-3-adding-a-legend](http://zeroviscosity.com/d3-js-step-by-step/step-3-adding-a-legend)
- **flexbox chart:** [http://blog.scottlogic.com/2015/02/02/svg-layout-flexbox.html](http://blog.scottlogic.com/2015/02/02/svg-layout-flexbox.html)

### JavaScript

- **JavaScript Basics:** [https://www.udacity.com/course/viewer#!/c-ud804/l-1946788554/m-2550568535](https://www.udacity.com/course/viewer#!/c-ud804/l-1946788554/m-2550568535)
- **Intro to jQuery:** [https://www.udacity.com/course/viewer#!/c-ud245/l-3314378535/m-3316638682](https://www.udacity.com/course/viewer#!/c-ud245/l-3314378535/m-3316638682)
- **Object-Oriented JavaScript:** [https://www.udacity.com/course/viewer#!/c-ud015/l-2593668697/m-3479768789](https://www.udacity.com/course/viewer#!/c-ud015/l-2593668697/m-3479768789)
- **modal 1:** [https://discussions.udacity.com/t/ways-to-get-a-clean-slate-with-js/160826](https://discussions.udacity.com/t/ways-to-get-a-clean-slate-with-js/160826)
- **modal 2:** [http://www.w3schools.com/howto/howto_css_modals.asp](http://www.w3schools.com/howto/howto_css_modals.asp)
- **JS scopes:** [https://discussions.udacity.com/t/populating-a-div-inside-a-nested-function-call/160956/2](https://discussions.udacity.com/t/populating-a-div-inside-a-nested-function-call/160956/2)

### Data Viszualization
- **Shark Attack:** [http://jchernov.com/post/46445834470/man-bites-shark](http://jchernov.com/post/46445834470/man-bites-shark)
- [http://www.datavizcatalogue.com/methods/stacked_bar_graph.html](http://www.datavizcatalogue.com/methods/stacked_bar_graph.html)
- **using color:** [http://www.perceptualedge.com/articles/visual_business_intelligence/rules_for_using_color.pdf](http://www.perceptualedge.com/articles/visual_business_intelligence/rules_for_using_color.pdf)
- **misleading statistics:** [https://medium.com/i-data/misleading-with-statistics-c63780efa928#.j9u4nu4e0](https://medium.com/i-data/misleading-with-statistics-c63780efa928#.j9u4nu4e0)

### Soil Sealing

- **short video:** [https://www.youtube.com/watch?v=YU6jz061kTs&feature=youtu.be](https://www.youtube.com/watch?v=YU6jz061kTs&feature=youtu.be)
- **extensive European report:** [http://ec.europa.eu/environment/archives/soil/pdf/sealing/Soil%20Sealing%20In-depth%20Report%20March%20version_final.pdf](http://ec.europa.eu/environment/archives/soil/pdf/sealing/Soil%20Sealing%20In-depth%20Report%20March%20version_final.pdf)
- **definition:** [http://esdac.jrc.ec.europa.eu/themes/soil-sealing](http://esdac.jrc.ec.europa.eu/themes/soil-sealing)