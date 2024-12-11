1. What was the effect of moving the gate from level 30 to level 40 on 1-day retention rates?
   Moving from 30 to 40 decreased the retention rates slightly. This is shown in my charts, 30 hovers around 0.45 whereas 40 hovers around 0.43

2. What was the effect of moving the gate from level 30 to level 40 on 7-day retention rates?
   Again, moving from 30 to 40 decreased the retention rates slightly. This is shown in my charts, 30 hovers around 0.19 whereas 40 hovers around 0.18
3. What was the biggest challenge for you in completing this assignment?
   Figuring out the distributions and making the priors was very difficult for me.

Initially I was making relative priors in the sense that I was trying to express "I think group 30 will have higher/lower retention rates than group 40".
I had a much better time when I made my priors absolute i.e. "I think group 30 will have X retention rate and groupe 40 will have Y retention rate". I used generative AI for this part of the assignment to get past my confusion about not knowing how to decide on the prior and it led me to the conclusion that I described.

I also had trouble understanding the different distributions. There seems like so many options and I didn't know which fit. I included a picture in my repository to a chart that helped me understand the differeces between each distribution. I ended up using beta distribution for my priors because it was bound between 0 and 1 which makes sense for a retention rate. I also found binomial distribution to be effective because it was from 0 to infinity, which is appropriate because there can be 0 to infinity(ish) counts for whether or not someone stayed. Here is where I found that helpful chart https://learning.nceas.ucsb.edu/2021-10-delta/session-4-introduction-to-bayesian-modeling.html
