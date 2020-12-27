---
title: "Experimenting with Mushrooms... Seriously"
excerpt: "Okay, not that kind of experimenting. More along the lines of statistical experimenting. In this post, I take you along a journey wherein I test one of the most proliferated old wives' tale in the kitchen: Don't wash your mushrooms, or they will absorb too much water and become soggy! Is this true? Well, come along on this mushroom trip with me and we can use the power of statistics and experimental design to hopefully come up with an answer."
collection: portfolio
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

The next factor of interest was the temperature of the water. Since I am aiming for a $2^k$ factorial design (spoilers!), I wanted two distinct temperatures: hot and cold. Now, the coldest my faucet was able to achieve was 7 degrees Celsius, but I don't like that number so I rounded up and chose 10 degrees. The hottest that my faucet could reach was 40 degrees Celsius. Upon doing research, this is apparently not standard and many faucets can achieve temperatures higher than that. This was news to me, but alas, there is not much you can do about University housing faucets. Sigh. 

Another factor of interest was the length of time each mushroom would be exposed to the treatment. For the sake of not wanting to waste a ton of water, and because I had decided that rinsing would use 1 L/min, the maximum time was chosen to be 5 minutes. For a shorter period of time, I settled on 1 minute. These levels were chosen for practicality. I could've sat there for 30 minutes and let the mushrooms rinse, but that is not realistic. 

Finally, Alton Brown did this experiment for button mushrooms, but what about other common mushrooms. Again, for sake of simplicity, I just wanted one other type of mushroom so I settled on Shiitake mushrooms. 

Alright, now we have our 4 factors: Method (Soak vs Rinse), Temperature (Cold vs Hot), Time (Short vs Long), and Species (Button vs Shiitake). Using quick math, we realize we have $2^4 = 16$ possible treatment combinations. Now, as statisticians, we know how important it is to replicate each treatment combination. Because I was paying out of pocket for these mushrooms, and I wanted to complete this experiment in one day, I chose to do 4 replicates for each combination. This results in 64 experiments that need to be conducted. I drafted a spreadsheet of treatment combinations. Randomized all the rows. And now I was ready to begin. Next up: time to buy the mushrooms.

This was probably the trickiest part. As a statistician, I wanted these mushrooms to be randomly selected. The logical side of me said that would be impossible. But, I persisted, and I went to the store, approached the bulk mushroom bin, closed my eyes, and randomly selected a bunch of button mushrooms. Then, I repeated this exact same method for the shiitakes. I came away from the store with more than 64 mushrooms just in case anything were to happen to my experimental units. All in, it only cost me $29.54 which is a bargain if you think about it. 

# Conducting the Experiment

At this point, I have all 64 mushrooms ready, I have my randomized order of treatment allocation, and I have the day all to myself. I diligently weighed each mushroom, applied the appropriate treatment, then weighed the mushroom again. I ended up using a jewelry scale that could weigh in increments of 1 mg allowing for precise measurements (or at least as precise as possible given the conditions). The data were recorded as the before and after weights, in grams, and can be downloaded as a csv file [here](https://github.com/iamurphy/iamurphy.github.io/tree/master/files/blog/mushroom_complete.csv). 

Now, I know this is not perfect, but c'mon--I am trying my best given the circumstances. Of course this could've been done better in a more controlled environment, but I think that I took all precautions necessary to come up with some interesting results. Speaking of...

# Exploratory Analysis

Before doing any statistical modelling, we will start with basic exploratory analysis. Firstly, let's look at the distribution of the change in weight of the mushrooms. Below is a histogram showing this distribution:

<div style="text-align:center"><img src ="/images/mushroom_changeinweight.png" /></div>

As we can see from the graph, all mushrooms gained weight during the experiment, as expected. The next thing to look at are the covariates of interest: type of mushroom, method of exposure, temperature of the water, and length of time of exposure. Since the covariates of interest here are all factors, the best type of plots that I can think of right now are interaction plots. Since we have pre- and post- measurements, and we are mainly interested in the change in the weight, we will plot the change in weight on the y-axes for these plots. Essentially, we want to consider the weight of the mushroom after treatment exposure while accounting for baseline weight (more on this in the upcoming sections). Moreover, we are only considering two-order interactions for this experiment since three-order interactions are usually meaningless when trying to interpret, and I am trying to keep this experiment and blog as straightforward as possible. Okay enough blabbing, let's look at those interaction plots. 

<div style="text-align:center"><img src ="/images/interactioneffects.png" /></div>

Alright, so what are we looking for, and what does all this mean? Well, from these plots, we can see if there are any major interactions between the variables. Major interactions occur when the two lines are not parallel. If the lines are parallel, then the difference of the response variable under the first treatment combination is the same under the second treatment combination (think: vertical distance between the two points). However, if the two lines are not parallel (including if they cross-over), then we have a significant interaction effect. The larger the difference in slopes of these two lines, the larger the interaction effect. From these plots, we suspect that there is an interaction between Type and Method, and Time and Temperature. However, the interaction between Type and Method is probably not large enough to be detected as significant. The other 4 interaction effects seem to be non-significant. This will be shown to be true in the next sections. Okay, interaction plots, check!

# Modelling

The next step in this analysis is to produce some statistical models. Now, the simplest model, and probably the best model, is a linear regression. For this model, our goal is to model the final weight of the mushroom as a function of the aforementioned covariates while controlling for baseline mushroom weight. This is a typical pre-post analysis, and some may even call it ANCOVA. I call it linear regression and you should too. The model will take the following form for all my mathies out there.

\begin{align}
y_i &= \beta_0 + \beta_1 x_i + \beta_2 \texttt{Type_i} + \beta_3 \texttt{Method_i} + \beta_4 \texttt{Time_i} + \beta_5 \texttt{Temperature_i} \\\\
&+ \texttt{Interactions_i} + \epsilon_i
\end{align}

Where $y_i$ is the weight of the mushroom after exposure to treatment, $x_i$ is the baseline weight before exposure to treatment, and all those other covariates are indicator variables which are equal to 0 or 1 depending on which treatment is given to the $i^{th}$ mushroom. I also didn't type out all those interaction terms, but I'm sure you can visualize them accordingly. Finally, I included that $\epsilon_i$ term which is the random error that is assumed to be normally distributed with mean 0 and constant variance $\sigma^2$. Fitting this model in R with all two-order interactions, we get the following:

```R
library(tidyverse)

# Load the data
mushroom <- read.csv("../mushroom_complete.csv", header=TRUE) 

mushroom$Time <- as.factor(mushroom$Time)
mushroom$Temperature <- as.factor(mushroom$Temperature)
mushroom$Type <- as.factor(mushroom$Type)
mushroom$Method <- as.factor(mushroom$Method)

m1 <- lm(after ~ before + (Type + Method + Time + Temperature)^2, 
         data = mushroom)
summary(m1)
```

Now, the output of this model produces the following:

```R
> summary(m1)

Call:
lm.default(formula = after ~ before + (Type + Method + Time + 
    Temperature)^2, data = mushroom)

Residuals:
     Min       1Q   Median       3Q      Max 
-0.86902 -0.14599 -0.01658  0.09321  1.68269 

Coefficients:
                            Estimate Std. Error t value Pr(>|t|)    
(Intercept)                -0.182584   0.221237  -0.825 0.412980    
before                      1.015753   0.008401 120.902  < 2e-16 ***
TypeShiitake                0.446472   0.198280   2.252 0.028590 *  
MethodSoak                  0.178938   0.183972   0.973 0.335237    
Time5                       0.182681   0.184585   0.990 0.326909    
Temperature40               0.510460   0.184125   2.772 0.007706 ** 
TypeShiitake:MethodSoak    -0.195886   0.184298  -1.063 0.292749    
TypeShiitake:Time5          0.056272   0.183912   0.306 0.760845    
TypeShiitake:Temperature40 -0.120061   0.183924  -0.653 0.516775    
MethodSoak:Time5            0.067062   0.184132   0.364 0.717179    
MethodSoak:Temperature40   -0.316587   0.185808  -1.704 0.094381 .  
Time5:Temperature40         0.720319   0.187560   3.840 0.000335 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.3678 on 52 degrees of freedom
Multiple R-squared:  0.998,	Adjusted R-squared:  0.9976 
F-statistic:  2348 on 11 and 52 DF,  p-value: < 2.2e-16
```

If you are familiar with R, you can interpret this output quite easily. If not, the important point to notice here is that the interaction terms which we thought were not significant are in fact not statistically significant. They seem to provide nothing to the model, and only make it more difficult to interpret. This also coincides with our initial assumption from the interaction plots that the Time-Temperature interaction is the only significant one. Some may argue that I should keep these variables in the model for completeness, or perhaps that by selectively removing them I am introducing bias. And those people make some very good points. However, if we wish to predict the final weight of a mushroom that is exposed to a certain combination of treatments, by including these other terms, we can end up with weird estimates and large standard errors. So I am making the professional decision to remove the interaction terms which are non-significant. Moreover, this smaller model will be more compact and easier to interpret. Here is the output of the new model:

```R
m2 <- lm(after ~ before + Type + Method + Time + Temperature + Time*Temperature, data = mushroom)
summary(m2)

Call:
lm.default(formula = after ~ before + Type + Method + Time + 
    Temperature + Time * Temperature, data = mushroom)

Residuals:
     Min       1Q   Median       3Q      Max 
-0.85284 -0.15476 -0.04546  0.11745  1.71746 

Coefficients:
                     Estimate Std. Error t value Pr(>|t|)    
(Intercept)         -0.023197   0.192311  -0.121  0.90441    
before               1.014054   0.008266 122.676  < 2e-16 ***
TypeShiitake         0.300548   0.120567   2.493  0.01560 *  
MethodSoak          -0.044210   0.091743  -0.482  0.63173    
Time5                0.246489   0.130126   1.894  0.06327 .  
Temperature40        0.296881   0.131747   2.253  0.02810 *  
Time5:Temperature40  0.712869   0.186982   3.812  0.00034 ***
---
Signif. codes:  0 ‘***’ 0.001 ‘**’ 0.01 ‘*’ 0.05 ‘.’ 0.1 ‘ ’ 1

Residual standard error: 0.3669 on 57 degrees of freedom
Multiple R-squared:  0.9978,	Adjusted R-squared:  0.9976 
F-statistic:  4326 on 6 and 57 DF,  p-value: < 2.2e-16
```

Now, if you are concerned about whether or not this smaller model has resulted in a significant reduction in information, we can check this via a likelihood ratio test. This tests the null hypothesis that the simpler model is adequate. The code and output is given below.

```R
library(lmtest)
lrtest(m2, m1)

Likelihood ratio test

Model 1: after ~ before + Type + Method + Time + Temperature + Time * 
    Temperature
Model 2: after ~ before + (Type + Method + Time + Temperature)^2
  #Df  LogLik Df  Chisq Pr(>Chisq)
1   8 -22.930                     
2  13 -20.156  5 5.5477     0.3527
```

The p-value from this test is large, indicating no evidence to reject the null hypothesis that the simpler model is adequate. Ok, we keep the simpler model! Let's look at this simpler model in more detail. If you are super keen as well, you would notice that the baseline term, $\texttt{before}$, is highly significant because there is a very, very, high correlation of this variable with the response variable. Moreover, the adjusted $R^2$ term for this model is very high because of the inclusion of this variable as well. 

## Interpreting the Model

Two-way interactions are much easier to interpret, albeit still tricky. So what does all this mean? Great question! Let's examine the Time-Temperature (T-T) interaction. Let's look at the interaction plot directly from the data, then we will compare that against the estimate from the model. 

<div style="text-align:center"><img src ="/images/timetempint.png" /></div>

Firstly, we note that the y-axis is the change in weight of the mushroom. Secondly, we note that the x-axis is the time factor. The two lines represent the two levels of the temperature factor with blue being cold (10 degrees) and red being hot (40 degrees). Now, let's focus on the 1 minute time level. At this point, the average change in weight for the cold temperature is around 0.35 grams whereas the average change in weight for the hot temperature is around 0.65 grams holding all else constant. This is a difference of around 0.3 grams. Now, as we change the length of time to 5 minutes, the average change in weight for the cold group is close to 0.55 grams and the average change in weight for the hot group is a whopping 1.55 grams for a difference of 1 gram. Look at that! The difference between the average change in weight of the mushrooms between the two temperature groups at 5 minutes is 1 gram, but it is only 0.3 grams at 1 minute. Hence, we have a strong interaction effect of about 1 - 0.3 = 0.7! The effect of time on the change in weight depends on which temperature the water is set to! 

So what about the estimate from the model? Well, the simpler, reduced model produces estimates for the main effects of Time and Temperature as 0.246 and 0.297 with the interaction effect estimated as 0.713. How can we interpret these numbers, specifically the interaction effect? Well, let's consider the general regression model.

\begin{align*}
Y &= -0.023 + 1.014 \texttt{before} + 0.301 I(Type = Shiitake) - 0.044 I(Method = Soak) \\\\ 
&+ 0.246 I(Time = 5) + 0.297 I(Temp = 40) + 0.713 I(Time = 5) * I(Temp = 40)
\end{align*}

Where $I()$ is an indicator function which equals 1 if the condition inside the brackets is satisfied and 0 otherwise. Now, let's consider two models. The first model is the average response for when time is set to 5 minutes and temperature is set to 40 degrees, holding all else constant. This model is:

\begin{align*}
Y_1 &= -0.023 + 1.014 \texttt{before} + 0.301 I(Type = Shiitake) - 0.044 I(Method = Soak) \\\\
&+ 0.246 + 0.297 + 0.713
\end{align*}

Now, consider the exact same model, but this time, we set the temperature to be 10 degrees instead of 40. We get:

\begin{align*}
Y_2 = -0.023 &+ 1.014 \texttt{before} + 0.301 I(Type = Shiitake) - 0.044 I(Method = Soak) \\\\
&+ 0.246
\end{align*}

Subtracting these two models, we get the average change in the after-weight going from 40 degrees to 10 degrees when the time is 5 minutes, holding all else constant, which is:

$$
Y_1 - Y_2 = 0.297 + 0.713
$$

Similarly, let's consider two models where we hold time to be 1 minute, then see what happens when we change temperature. Those two models are:

\begin{align*}
Y_3 = -0.023 + 1.014 \texttt{before} + 0.301 I(Type = Shiitake) - 0.044 I(Method = Soak) \\\\
&+ 0.297
\end{align*}

$$
Y_4 = -0.023 + 1.014 \texttt{before} + 0.301 I(Type = Shiitake) - 0.044 I(Method = Soak)
$$

Subtracting these two models gives the average after-weight change going from 40 degrees to 10 degrees when then time is 1 minute.

$$
Y_3 - Y_4 = 0.297
$$ 

Okay, so finally, we subtract the resulting subtractions, if that makes sense. See below:

$$
(Y_1 - Y_2) - (Y_3 - Y_4) = (0.297 + 0.713) - (0.297) = 0.713
$$

So this is the coefficient estimate of the interaction effect! Now what exactly does $(Y_1 - Y_2) - (Y_3 - Y_4)$ represent. Well, it is a difference of differences. So, 0.713 is the average _change_ in the differences in average after-weight of the mushrooms going from 5 minutes to 1 minute for 40 degrees versus 10 degrees, holding everything else constant. Now that is one convoluted sentence! Mathematically, you can see how that is derived. Conceptually, it may take some time to really understand what is going on here. Notice that the 0.713 estimate is actually quite close to our "back-of-the-envelope" calculation using the interaction plot, which was about 0.70, give or take. This is to be expected! 

This type of interpretation is very common in longitudinal data analysis as you can compare the treatment and control group over two time periods, usually follow-up versus baseline. It allows for a better understanding of any treatment-time interaction effect. Remember when I said that interpreting interaction effects is difficult? I was not lying!


## Interpreting Main Effects

In the absence of interaction effects, the main effects are quite simple to interpret. It's really just a _this_ vs _that_ scenario. Let's interpret the effect of mushroom type. Since type does not appear in any interaction terms, the interpretation is easy. Shiitake mushrooms, on average, tend to have a final weight that is 0.301 grams higher than button mushrooms, holding everything else constant and adjusting for baseline weight. Easy! The same could be said for method, however, that term is non-significant. On average, soaked mushrooms are about 0.04 grams lighter than rinsed mushrooms after adjusting for baseline weights. What about the time and temperature terms? Well, since they appear in the interaction term, it is inappropriate to interpret them by themselves as their effect depends on one another. You can refer to the previous section where I wrote out the complete models for different scenarios, then try to extract those coefficients for the main effects of time and temperature. Then, you can try to compare models against one another to isolate those main effects. Notice that if we don't set time or temperature at a fixed level and we allow them to remain as variables, then we will be stuck with that pesky interaction term making it harder to extract the coefficients for the main effects. This is why it is generally not recommended to interpret the main effects on their own when those main effects exist in interaction terms in the model. 

Last but not least, what's the deal with that baseline term? Well, we included it in the model to adjust for different weights of the mushrooms at baseline. When we ran the model, we got a model estimate that is practically equal to 1. This can be easily justified by just assuming that the amount of water absorbed by the mushrooms is independent of its starting weight. This coefficient is formally interpreted as, "for every 1 gram increase in starting weight, the final weight of the mushroom increases by 1 gram, holding all else constant". Well, duh! That's what we would expect. Now, the actual estimate is slightly larger than 1, and it is statistically significant. So, this might mean that larger mushrooms at baseline actually absorb more water than smaller mushrooms at baseline. This makes sense physically since larger mushrooms have larger surface areas resulting in more water absorption. It would be interesting to see what would happen if Enoki mushrooms were included in this experiment since they are very light but have high surface area! Maybe that would require an interaction between baseline weight and type of mushroom! SO many possibilities! 

# Discussion

Ok, so what now? We collected the data, we fit the model, we chose the model that is most appropriate for our purposes, we examined interaction effects, and now we are satisfied with the model. So what can we do? Well, our original question asked, "Do mushrooms absorb water?" and that is a resounding YES. They sure do! All the mushrooms in the experiment ended up gaining some water. None stayed the same, and none lost any water. So yes, they do gain water. Now, how much? And is that a significant amount? 

Well, let's consider for example that you are making a delicious ribeye for dinner, and you want to make sautéed button mushrooms on the side. You like browned mushrooms, and not soggy mushrooms because who likes that??? Beforehand, you decide to clean the mushrooms. What should you do to avoid water logged mushrooms? Well, at this point, we can control three factors: time, temperature, and method. We've already established that the method does not matter, so we choose rinsing for simplicity. Next, we look at time and temperature. Let's set time to be 1 minute, and temperature to be 40 degrees. Suppose the single lonely mushroom that we decide to clean weighs only 20 grams. Then, we would expect the final weight of that mushroom to be: -0.023 + 1.014*20 + 0.297 + 0.713 = 21.267 grams. A measly 1.267 grams of water was absorbed. And if the recipe called for 10 mushrooms, all of which were 20 grams exactly. And we cleaned each one individually like we did in the experiment. Well, then the total amount of water absorbed would be expected to be 12.67 grams, or about 0.053 cups of water, which is around 2.6 teaspoons of water. Now, a tablespoon is 3 teaspoons, so that would be less than a tablespoon of water that is absorbed. Not too shabby!

How could we minimize the amount of water absorbed? Well, we would need to set all the indicators from our model to be 0. We do this by choosing: Button mushrooms that are rinsed for 1 minute in 10 degree water. 

# Next Steps

What could be done in the future? By all means, if someone wants to replicate this study, please do! I'd love to see what kind of results you come up with. What about other mushrooms? Creminis, which are a type of button mushroom, may act differently. I have no idea! What other factors could go into this? The store you bought it from perhaps. Or maybe the age of the mushroom, how long it has been sitting out, and how dry it is. If I had access to these variable, you bet I would've included them!

So, this brings us to the end of our very exciting mushroom trip... I mean journey. I hope you had as much fun reading along as I did when conducting this experiment. Of course, I have to thank Alton Brown for inspiring not only this experiment, but also my love of cooking and being in the kitchen. It's not every day when you get to combine statistics and cooking--two things I love--into one project. 
