---
title: "The Great Mushroom Experiment"
date: 2020-12-22
permalink: /posts/2020/12/blog-post-1/
tags:
---

If you're anything like me, then you enjoying spending exuberant amounts of time in the kitchen trying to whip up a tasty meal or fancy dessert whenever you get the chance. If you're anything like me, then you tend to watch cooking shows on the _Food Network_ for more hours than you wish to admit. And, if you're anything like me, then you are very curious and will not take "because I said so" as an appropriate answer. 

Growing up, I was obsessed with the TV show *Good Eats* (1999-2012, 2019-Present) hosted by the infamous chef, TV personality, and overall hilarious man: Alton Brown. Alton is able to combine humour, science, and cooking all into one show, which he deems is a mixture of "Julia Child, Mr. Wizard, and Monty Python". After a brief hiatus, *Good Eats* returned for a new season last year. When I tell you my inner child was ecstatic, that was an understatement. *Good Eats* was a major part of my formative years and was one of the reasons why I love cooking so much. 

As a formally trained statistician (statistician in training?), I have developed a love for experiments, and especially experimental design. A properly designed experiment is your best bet at being able to prove (or rather disprove) your hypothesis of interest. Now I know you may be thinking, "Ian, what was this whole spiel about your love of cooking and *Good Eats* have to do with being a statistician? And what the heck is this doing on a website regarding statistics?". Well, bare with me for a moment. 

Season 8 Episode 15 of *Good Eats*, titled "Mythsmashers", sees a curious Alton Brown mimicking the infamous "Mythbusters" in the kitchen. Several food myths are put to the test, in a digestible format for the viewer, to truly see if these so-called "wives' tales" actually hold a flame to reality. The show opens with a wonderful myth that us cooks have been told is true since the creation of fire: "Searing a piece of meat will seal in the juices". Alton goes on to test this theory by preparing two very similar steaks: one with a sear and one without a sear. The steak without a sear is placed into a 400 degree oven, while the other steak receives a sear and is then placed into the oven to finish cooking. Now, the results of this experiment are less than extraordinary. He found that the seared steak lost 19% of its weight, whereas the non-seared steak only lost 13% of its weight. A 6% difference, no? Well, the statistician in me is screaming. Where are the replicates? Was this difference observed solely due to chance? Were the treatments randomized? What about the oil that was slathered onto the meat prior to cooking? So much is left unsaid that no statistician worth their salt would conclude that this difference was statistically significant. Ok ok, I'm not trying to bash Alton here; after all, this is just a TV show, not a scientific laboratory. I can let this one slide for now.

Here is where things get interesting: Alton's second experiment. Have you ever heard of the old wives' tale "never wash your mushrooms prior to cooking as they will absorb water and become soggy"? Well, I have. Many times actually. And Alton had too. So, he put it to the test in his own experiment. He began with 4 ounces of button mushrooms and soaked them in cold water for 10 minutes. Afterwards, they weighed 4.2 ounces. A second batch of mushrooms he let soak for 20 minutes. They only weighed 4.25 ounces after soaking. A third batch soaked for 30 minutes, and only weighed 4.15 ounces! Finally, a fourth batch of mushrooms got a quick rinse in cold water. These mushrooms ended up weighing 4.2 ounces after a very quick 30 second rinse. The results are very promising. Mushrooms seem to absorb water, but not that much. And definitely not enough water to cause concern in the kitchen. After all, mushrooms do grow in manure, so a rinse in water is probably for the best. 

Again, the statistician in me was screaming. Where are the replicates? Again, were the batches of mushrooms randomized to treatments? How cold was the water? What if the water was warm? Why are you measuring in ounces when grams would be more precise? What if you used a different type of mushroom? How much water was sprayed on the mushrooms? Was the force of the water a contributing factor? So many questions, so little answers.  

As any curious, bored, and downright methodical person would do, I wanted to replicate this experiment, but this time, I wanted to do it right. No offence to you Alton, but this experiment needed some work. So, using my knowledge of experimental design, and my formal training as a statistician, I decided to embark on my first solo experiment in hopes to answer the question, "Do mushrooms absorb water, and if so, what factors contribute to how much is absorbed?". 

# Methods

This experiment began by deciding which factors were most likely going to contribute to this water-logging effect of mushrooms. Firstly, as Alton Brown did, the method of water delivery is probably important. Should you soak or rinse the mushrooms? This question in and of itself sparks another question. What does it mean for the mushroom to be soaked or rinsed? Well, to make this feasible for the home cook, I decided that "soaking" a mushroom meant submerging it completely in 1 litre of water. In order to submerge the mushroom, a plate was placed on top of it to ensure complete water coverage (mushrooms float don't cha know?!). Rinsing on the other hand was more difficult to define. I tested out a few different methods as to not wanting to waste tons of water in the process, and I finally decided on defining rinsing as follows: Rinsing is defined as placing a single mushroom under a constant stream of water 30 centimetres from the faucet with water coming out at a rate of 1 L/min. Yes, I know this is very specific. And trust me, it was not easy to nail this down, but I tried my best to adhere to this definition. Consistency is key! 

The next factor of interest was the temperature of the water. Since I am aiming for a 2^k factorial design (spoilers!), I wanted two distinct temperatures: hot and cold. Now, the coldest my faucet was able to achieve was 7 degrees Celsius, but I don't like that number so I rounded up and chose 10 degrees. The hottest that my faucet could reach was 40 degrees Celsius. Upon doing research, this is apparently not standard and many faucets can achieve temperatures higher than that. This was news to me, but alas, there is not much you can do about University housing faucets. Sigh. 

Another factor of interest was the length of time each mushroom would be exposed to the treatment. For the sake of not wanting to waste a ton of water, and because I had decided that rinsing would use 1 L/min, the maximum time was chosen to be 5 minutes. For a shorter period of time, I settled on 1 minute. These levels were chosen for practicality. I could've sat there for 30 minutes and let the mushrooms rinse, but that is not realistic. 

Finally, Alton Brown did this experiment for button mushrooms, but what about other common mushrooms. Again, for sake of simplicity, I just wanted one other type of mushroom so I settled on Shiitake mushrooms. 

Alright, now we have our 4 factors: Method (Soak vs Rinse), Temperature (Cold vs Hot), Time (Short vs Long), and Species (Button vs Shiitake). Using quick math, we realize we have 2^4 = 16 possible treatment combinations. Now, as statisticians, we know how important it is to replicate each treatment combination. Because I was paying out of pocket for these mushrooms, and I wanted to complete this experiment in one day, I chose to do 4 replicates for each combination. This results in 64 experiments that need to be conducted. I drafted a spreadsheet of treatment combinations. Randomized all the rows. And now I was ready to begin. Next up: time to buy the mushrooms.

This was probably the trickiest part. As a statistician, I wanted these mushrooms to be randomly selected. The logical side of me said that would be impossible. But, I persisted, and I went to the store, approached the bulk mushroom bin, closed my eyes, and randomly selected a bunch of button mushrooms. Then, I repeated this exact same method for the shiitakes. I came away from the store with more than 64 mushrooms just in case anything were to happen to my experimental units. All in, it only cost me $29.54 which is a bargain if you think about it. 

# Conducting the Experiment

At this point, I have all 64 mushrooms ready, I have my randomized order of treatment allocation, and I have the day all to myself. I diligently weighed each mushroom, applied the appropriate treatment, then weighed the mushroom again. I ended up using a jewelry scale that could weigh in increments of 1 mg allowing for precise measurements (or at least as precise as possible given the conditions). The data were recorded as the change in weight, in grams, and can be downloaded as a csv file [here](../files/mushrooms.csv). 

Now, I know this is not perfect, but c'mon--I am trying my best given the circumstances. Of course this could've been done better in a more controlled environment, but I think that I took all precautions necessary to come up with some interesting results. Speaking of...

# Results

Now that the data has been collected, the next step is to analyze it to hopefully come up with some conclusions. To do so, I fit a basic regression model. The response variable is the change in weight of the mushroom, a continuous variable. Below is a histogram showing the distribution of this variable:

<div style="text-align:center"><img src ="/images/histogram_response.png" /></div>

Next, I fit a regression model with all 4 covariates [M(ethod), T(emp), L(ength of time), S(pecies)]. Note that each of the covariates are coded as either 0 or 1. For method, we have 0 for rinse and 1 for soak. For temperature, we have 0 for 10 degrees and 1 for 40 degrees. For time, we have 0 for 1 minute and 1 for 5 minutes. For species, we have 0 for button and 1 for shiitake. Hopefully we can keep that straight in our heads!

For this model, I included all interaction terms up to order three. I ignored the four way interaction term simply because it is highly, highly unlikely to be relevant, and even if it is, it will not help us when trying to interpret the results. Some people might not like this approach, but I think it is sensible enough to consider. If you want to repeat the analysis, the R code is given below:

```R
# Load the data
data2 <- read.csv("../mushrooms.csv", header=TRUE) 

# Wrangle the data to get into a nicer form with added variables
mushroom <- data2 %>% 
  dplyr::select("Type" = "Mushroom.Type",
                "Method" = "Method",
                "Time" = "Length.of.Time..mins.",
                "Temperature" = "Temperature...C.",
                "y1" = "Rep..1",
                "y2" = "Rep..2",
                "y3" = "Rep..3",
                "y4" = "Rep..4") %>% 
  mutate("Temperature" = str_replace(Temperature, "10 ˚C", "10˚C"))

mushroom$Time <- as.factor(droplevels(as.factor(mushroom$Time)))
mushroom$Temperature <- droplevels(as.factor(mushroom$Temperature))
mushroom$Type <- droplevels(as.factor(mushroom$Type))

mushroom <- mushroom %>% 
  dplyr::arrange(Temperature, Time, Method, Type)

df <- gen.factorial(c(2,2,2,2), 4, center=TRUE,
                    varNames=c("S", "M", "T", "L"))

df$response1 <- mushroom$`y1`
df$response2 <- mushroom$`y2`
df$response3 <- mushroom$`y3`
df$response4 <- mushroom$`y4`

y <- with(df, c(response1, response2,
                response3, response4)); y

dat <- data.frame(y, 
                  S = rep(df$S, 2), 
                  M = rep(df$M, 2),
                  T = rep(df$T, 2),
                  L = rep(df$L, 2))

m1 <- lm(y ~ (S + M + T + L)^3, data = dat)
summary(m1)
```

Now, the output of this model produces the following:

```R
Call:lm.default(formula = y ~ (S + M + T + L)^3, data = dat)Residuals:     Min       1Q   Median       3Q      Max -1.01875 -0.20156 -0.02013  0.11944  1.70525 Coefficients:            Estimate Std. Error t value Pr(>|t|)    (Intercept)  0.80134    0.05273  15.198  < 2e-16 ***S            0.12012    0.05273   2.278  0.02711 *  M           -0.03691    0.05273  -0.700  0.48728    T            0.29637    0.05273   5.621 8.93e-07 ***L            0.34506    0.05273   6.544 3.37e-08 ***S:M         -0.06756    0.05273  -1.281  0.20611    S:T          0.01491    0.05273   0.283  0.77860    S:L         -0.01466    0.05273  -0.278  0.78221    M:T          0.01550    0.05273   0.294  0.77003    M:L         -0.07125    0.05273  -1.351  0.18282    T:L          0.14609    0.05273   2.771  0.00788 ** S:M:T        0.03634    0.05273   0.689  0.49391    S:M:L       -0.01766    0.05273  -0.335  0.73916    S:T:L       -0.01075    0.05273  -0.204  0.83929    M:T:L       -0.02772    0.05273  -0.526  0.60147    ---Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1Residual standard error: 0.4218 on 49 degrees of freedomMultiple R-squared:  0.6534,	Adjusted R-squared:  0.5544 F-statistic:   6.6 on 14 and 49 DF,  p-value: 3.109e-07
```

If you are familiar with R, you can interpret this output quite easily. If not, the important point to notice here is that it _appears_ as if the three way interaction terms are not important. And, you'd be correct on that. They seem to provide nothing to the model, and only make it more difficult to interpret. Some may argue that I should keep these variables in the model for completeness, or perhaps that by selectively removing them I am introducing bias. To those people, I say: "Good luck trying to interpret three-way interaction terms in this scenario". So, we ditch them. If you want to be more formal about it, you can run a likelihood ratio test comparing the complex model (with the three-way interaction terms) to the simpler model (without them). The hypothesis that the likelihood ratio test is actually testing is if the simpler model is adequate or not. Running that gives:

```R
m3 <- lm(y ~ (S + M + T + L)^2, data = dat)

lrtest(m2, m1) # From the lmtest libraryLikelihood ratio testModel 1: y ~ (S + M + T + L)^2Model 2: y ~ (S + M + T + L)^3  #Df  LogLik Df  Chisq Pr(>Chisq)1  12 -27.609                     2  16 -27.024  4 1.1714     0.8828
```

The p-value is large, so we have no evidence to reject the simpler model as being adequate. So, we go forth with the model that has only two-way interaction terms. The output for the summary of model 2 is given below:

```R
> summary(m2)Call:lm.default(formula = y ~ (S + M + T + L)^2, data = dat)Residuals:     Min       1Q   Median       3Q      Max -0.96159 -0.17033 -0.02775  0.09950  1.76241 Coefficients:            Estimate Std. Error t value Pr(>|t|)    (Intercept)  0.80134    0.05117  15.662  < 2e-16 ***S            0.12012    0.05117   2.348  0.02265 *  M           -0.03691    0.05117  -0.721  0.47389    T            0.29637    0.05117   5.792 3.87e-07 ***L            0.34506    0.05117   6.744 1.16e-08 ***S:M         -0.06756    0.05117  -1.320  0.19235    S:T          0.01491    0.05117   0.291  0.77193    S:L         -0.01466    0.05117  -0.286  0.77565    M:T          0.01550    0.05117   0.303  0.76312    M:L         -0.07125    0.05117  -1.393  0.16957    T:L          0.14609    0.05117   2.855  0.00613 ** ---Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1Residual standard error: 0.4093 on 53 degrees of freedomMultiple R-squared:  0.647,	Adjusted R-squared:  0.5805 F-statistic: 9.716 on 10 and 53 DF,  p-value: 5.773e-09
```

## Interpreting Interaction Terms

Two-way interactions are much easier to interpret, albeit still tricky. Usually, I prefer to look at interaction plots to gain a better understanding of what is happening with this model. Below is a plot of the interaction effects from this dataset. 

<div style="text-align:center"><img src ="/images/interaction_plot.png" /></div>

Normally, if the lines are parallel, then we expect no interaction effect. Moreover, if the lines cross, we expect something called a cross-over interaction. From these images, we can see that there is probably *no* interaction between Species and Time, Species and Temperature, Method and Time, and Method and Temperature since they are all _relatively_ parallel. The only two that would stand out to me are Species and Method as Time and Temperature interaction effects. (An important point I should mention here is that these plots are independent of any model that is created. These plots are generated directly from the data rather than the model). 

Now, looking at these images, and looking at the regression model, it appears as if the Species-Method interaction is not significant, meaning, the slopes of the lines do not differ enough to make this effect statistically significant. Whereas the Time-Temperature interaction has slopes that differ enough to be deemed statistically significant. It becomes even more clear when examining the y-axes for these graphs. I know that I did not standardize the axes across all plots, and perhaps that would make it clear how different these interactions are, but nevertheless, we can see that the Time-Temperature interaction is much clearer than the Species-Method when we actually look at the y-axis. Oh why not, let's do it anyway. Here's another picture of the interaction effects, but scaled to the same axes. 

<div style="text-align:center"><img src ="/images/scaled_interaction.png" /></div>

From this picture, it is more clear that the interaction of Time-Temperature is much bigger than the Species-Method interaction, hence why the Species-Method is non-significant in the regression model. Whew, glad we cleared that one up. 

So what does all this mean? Great question! Let's examine the Time-Temperature (T-T) interaction. Firstly, we note that the y-axis is the change in weight of the mushroom. Secondly, we note that the x-axis is the time factor. The two lines represent the two levels of the temperature factor with blue being cold (10 degrees) and red being hot (40 degrees). Now, let's focus on the 1 minute time level. At this point, both the average change in weight for the cold temperature is around 0.3 grams whereas the average change in weight for the hot temperature is around 0.6 grams holding all else constant. This is a difference of around 0.3 grams. Now, as we change the length of time to 5 minutes, the average change in weight for the cold group is close to 0.75 grams and the average change in weight for the hot group is a whopping 1.6 grams for a difference of 0.85 grams. Look at that! The difference between the average change in weight of the mushrooms between the two temperature groups at 5 minutes is 0.85 grams, but it is only 0.3 grams at 1 minute. Hence, we have a strong interaction effect!

Still not clear? Let's look at the small, albeit interesting, interaction term between Species and Method. From this plot, we can see that the average change in weight for rinsed mushrooms in the button group is about 0.65 grams and in the soaked group it is about 0.75 grams. Now, when we look at the shiitake group, this effect is actually the opposite! The rinsed mushrooms gain about 1 gram whereas the soaked group only gains about 0.8 grams. So, depending on the type of mushroom being cleaned, the method of cleaning will result in different amounts of water being absorbed, on average. Hence an interaction! Now, this interaction effect is quite small, and ends up being non-significant, but nonetheless, that is how we interpret the findings. Takeaway here? If you have button mushrooms, you can either rinse or soak them. But, if you have shiitakes, you should probably soak them since that'll result in less water being absorbed! 

## Interpreting Main Effects

In the absence of interaction effects, the main effects are quite simple to interpret. It's really just a _this_ vs _that_ scenario. Let's consider the model with all main effects but only including the Time-Temperature interaction effect. The output is given below:

```R
> m3 <- lm(y ~ S + M + T + L + T:L, data = dat)> summary(m3)Call:lm.default(formula = y ~ S + M + T + L + T:L, data = dat)Residuals:     Min       1Q   Median       3Q      Max -0.97366 -0.19395 -0.03722  0.12617  1.75034 Coefficients:            Estimate Std. Error t value Pr(>|t|)    (Intercept)  0.80134    0.05070  15.807  < 2e-16 ***S            0.12012    0.05070   2.369  0.02116 *  M           -0.03691    0.05070  -0.728  0.46955    T            0.29637    0.05070   5.846 2.44e-07 ***L            0.34506    0.05070   6.806 6.19e-09 ***T:L          0.14609    0.05070   2.882  0.00554 ** ---Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1Residual standard error: 0.4056 on 58 degrees of freedomMultiple R-squared:  0.6208,	Adjusted R-squared:  0.5881 F-statistic: 18.99 on 5 and 58 DF,  p-value: 3.866e-11
```

Ok, so now we have a simpler model. Let's interpret the effect of species. Since species does not appear in any interaction terms, the interpretation is easy. Shiitake mushrooms, on average, tend to absorb 0.12 grams more water than button mushrooms do, holding everything else constant. Easy! The same could be said for method, however, that term is non-significant. What about the time and temperature terms? Well, since they appear in the interaction term, it is inappropriate to interpret them by themselves as their effect depends on one another. 

# Discussion

Ok, so what now? We collected the data, we fit the model, we chose the model that is most appropriate for our purposes, we examined interaction effects, and now we are satisfied with the model. So what can we do? Well, our original question asked, "Do mushrooms absorb water?" and that is a resounding YES. They sure do! All the mushrooms in the experiment ended up gaining some water. None stayed the same, and none lost any water. So yes, they do gain water. Now, how much? And is that a significant amount? 

Well, let's consider for example that you are making a delicious ribeye for dinner, and you want to make sautéed button mushrooms on the side. You like browned mushrooms, and not soggy mushrooms because who likes that??? Beforehand, you decide to clean the mushrooms. What should you do to avoid water logged mushrooms? Well, at this point, we can control three factors: time, temperature, and method. We've already established that the method does not matter, so we choose rinsing for simplicity. Next, we look at time and temperature. According to our model, if we set time to be 5 minutes, and temperature to be 40 degrees, we can expect on average an increase in 0.80 + 0 - 0.037 + 0.296 + 0.345 + 0.146 = 1.55 grams of water weight per mushroom exposed to these conditions! That could seriously add up. So, to minimize this, we would set time to be 1 minute and temperature to be 10 degrees. Not only does that set the main effects to be zero, but it also sets the interaction effect to be zero. 

# Next Steps

What could be done in the future? By all means, if someone wants to replicate this study, please do! I'd love to see what kind of results you come up with. What about other mushrooms? Creminis, which are a type of button mushroom, may act differently. I have no idea! What other factors could go into this? The store you bought it from perhaps. Or maybe the age of the mushroom, how long it has been sitting out, and how dry it is. If I had access to these variable, you bet I would've included them!

So, this brings us to the end of our very exciting mushroom trip... I mean journey. I hope you had as much fun reading along as I did when conducting this experiment. Of course, I have to thank Alton Brown for inspiring not only this experiment, but also my love of cooking and being in the kitchen. It's not every day when you get to combine statistics and cooking--two things I love--into one project. 
