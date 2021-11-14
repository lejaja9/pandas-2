## Mind the Gap 

Oh my god, it has been such a thrilling F1 season. As we enter the last month of races, I think back to the tightest title battles of the last 15 years of so. Three come to mind: Hamilton vs. Massa in 2008 ([what a dramatic ending that was](https://www.youtube.com/watch?v=XHSeGou-pCI)), Vettel vs. Alonso in 2012, and Rosberg vs. Hamilton in 2016. With championship battles that close, I often think that it comes down to who wants it more.

Who wants it more...with that in mind, another thought popped into my head: [reference-dependent preferences](https://www.nber.org/system/files/working_papers/w20343/w20343.pdf) (shoutout to my Behavioral Economics class!).

![](Distribution-of-Marathon-Finishing-Times-n-9-789-093.png)

My Professor pointed out that while the distribution of Boston Marathon finish times is generally normal, we can see spikes at every half-hour mark, with the 4:00 mark the most prominent... why is this? 

In short, reference points (i.e. a 4:00 marathon) serve as a goal marker that divides a marathon outcome between the gain domain (sub4:00 marathon success) and a loss domain (above 4:00 marathon failure). With psychological traits such as loss aversion and diminishing sensitivity, there is a significant in utility from crossing from the loss to gain domain (i.e. the gain in utility from a 4:01 to a 3:59 marathon is much higher than a gain in utility from a 3:58 to a 3:56 marathon, even though the gap between the two times are the same). In fact, this paper even discusses how toward the end of a race, runners who are comfortably within a 4:00 marathon will slow down, while runners near or slightly above the 4:00 marathon are less likely to slow down and in some cases will speed up - and that this phenomenon is not attributed to a race strategy of conserving energy but to achieving their goal. (The paper also states that runners who finish the marathon with a time of 4:01 are more likely to run the next year compared to those who finish with a time of 3:59.) I interpret these findings to explain that runners - and other athletes such as F1 drivers - have to some extent psychological control over their performance. I'm sure every athlete has heard their coach say that success in their sport is "90% mental, 10% physical." 

Looking at these close F1 title battles, I wondered if title protagonists drove at a higher level if they were in the "loss domain" and let their foot off the gas (pun intended) if they were in the "gain domain." Even Nico Rosberg admitted that in Abu Dhabi of 2016 his goal was to come away with P2 and seal the championship rather than fight for the win. 

With this small analysis, I looked at qualifying performances compared to how far behind the driver was in points in the title race. I would expect the driver to perform better in qualifying if they were behind in the title race.

Note: This data wasn't perfect due to engine reliability issues, sessions that were red flagged, and times when the driver simply didn't make Q3. In which case, I looked on a case-by-case basis to give the driver a pseudo-Q3 time.


### 2008

![](2008.png)

As we can see in the 2008 title race, Lewis Hamilton took the championship lead at around the halfway point of the season and never relinquished, although he fought off a very spirited effort from Felipe Massa in what would turn out to be a title that was won at the last corner of the last race. We can also see that throughout the season, both drivers were well within striking distance of the lead. Yet, when we look at their gap to the championship lead and qualifying performace, we see almost no correlation (a slight positive correlation with Massa). The scatterplots below paint the same picture:

![](2008_HAM_MAS.png)

When I plot "Points behind WDC Lead" against "Gap to Pole," there is no correlation for Hamilton and a mildly positive correlation for Massa (r = 0.51). So it looks like perhaps Massa performed better in qualifying the farther he was from the championship lead, while Hamilton brought the same consistency day in and day out.

### 2012

![](2012.png)

2012 marked a thrilling championship battle between multiple rivals that panned out to be a race between Vettel and Alonso after the second half of the season. If anything, I would've expected Vettel to put in mega qualifying sessions during the first half of the season as he fought against contenders such as Hamilton, Button, and Webber, 