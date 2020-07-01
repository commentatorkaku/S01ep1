# Predicting Covid-19 spread in India,  whether exams should be postponed, by Commentator kaku
## Welcome to S01E01 of Commentator Kaku's episodes!

[<img src="https://j.gifs.com/K1NqEx.gif" width="50%">]( https://www.youtube.com/watch?v=NYLQNwQJkUg)

# Transcript:

Today we are going to discuss about… a lot of things, which relate to Covid-19. 

Ok so, let me 1st list the things which we are going to discuss today:
1. The graphs of covid-19 and how I got to replicate it.(believe me that’s super fascinating)
2. Predicting the future spread of Covid-19
3. Exams and Covid
4. Why I cannot completely believe everything which the government is telling us

And for those who are thinking what is a science video doing inside a channel which is supposed to post musical stuff, then let me tell you that the background music which is ORIGINAL!!!, and hence becomes eligible to feature in a channel of music. And the potato background which you are seeing is also designed by me….I don’t know what struck me while drawing this….huh…..just didn’t want to pull up someone’s art without credit… And if there are any commerce/arts students watching this video, then hang on, Covid is also related to you(I am just giving you an excuse to increase the no. of views on this video) . Enough of commenting non-sense, now let’s get to work.

## Replicating Covid-19 Graphs:

So, for doing this I used knowledge from biology, a bit of mathematics, and class 10 Java programming knowledge. What a dangerous combination!! O I also forgot to mention a bit of common sense and a lot of trial and error were also involved.
Okay, so we have an aim that we have to construct Covid-19 statistics graphs, mathematically, but they should be as close as possible to reality.
So, in dealing with this we have to first channel out the path to it:

### 1st step: 
Understand the biological significance of the spread.
### 2nd step: 
Try to write it down mathematically, in some kind of formula
### 3rd step : 
Use that formula in a program and let it, self-generate values. Self generating values would  lead to lower human interaction, and hence your test whether your mathematical model for the spread is correct or not would be less biased..Now see if you want to be biased even then, then you can..but it does not serve our purpose, so there’s no use speaking about it.

Now at this point : You might be asking, why should I do this entire thing? Well, the answer is we need to know whether JEE and NEET would be held at their respective dates..I mean is it even possible to hold.. Because honestly speaking I am just fed-up by now of repeatedly learning inorganic chemistry, plant morphology, only to forget it within a few days…And I have another purpose…to make a video on this and show myself cool in front of my friends(Thug life music starts playing)...

![alt text](https://www.clipartkey.com/mpngs/m/254-2540160_thuglife-shades-sticker-thug-life-shades-sticker.png)

## Okay so back to our first step: Understanding the biology of the spread.

Now most of you know about this….You don’t have to know this in much detail. But the having a knowledge of the following terms will help:

### Incubation Period: 

It is time taken by the body to start showing symptoms, after the body has been affected. Now in case of Covid patients, in this period the probability of transmission of the virus is maximum, because the person affected would have no idea that he/she has been affected. I will be referring to these patients as hidden cases, because these people are affected, but remain hidden from our eye. Probably calling these asymptomatic cases would be more correct, but I will stick to the layman’s term.

### R value: 

It is the no. of people to which one affected person can spread the virus to. Now I have something to say here…r value is generally calculated as the increase in positive cases this day divided by the increase in positive cases the previous day. But I do not agree with this. What we are seeing is an almost 6-7 days delayed result. Because there exists a time lag due to the incubation period. The r value which we are finding today is actually 7 days old. Also if we are dividing the increase of today divided by increase of yesterday, then we assume that the person who has caught the virus today, will be transmitting it tomorrow. But we know, that cannot help.  There has to exist at least a 2-3day lag…The common sense I was talking about. So in mathematical model, I will assume  there to be a time lag unlike the general trend.

### Logisitic growth curve: 

Refer to NCERT Biology Class 12 Section 13.2.2 for it. You have a wonderful equation, if you have enough time, also integrate it, I can guarantee you the satisfaction would be high.

Ok, you have enough biological knowledge by now. 

## Time for the 2nd step: Writing it down mathematically:

So, by now we have the algorithm. So let’s write this down in the form of a program:

## And hence our 3rd step: The program :



