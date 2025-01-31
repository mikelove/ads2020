--- 
pagetitle: "Week 12 - Data analysis presentations"
---

# Week 12

## Week 12 Learning objectives

:::keyidea

At the end of this lesson you will be able to: 

* Identify the types and lengths of data analysis presentations
* Identify and create the key components of data analytic presentations
* Combine components to create a data analytic story
* Be able to identify and use different styles of data analytic presentations
:::

_This lecture borrows significantly from [Shannon Ellis'](http://www.shanellis.com/) excellent work in creating the lectures for [Written and Oral Communication in Data Science](https://leanpub.com/universities/courses/jhu/cbds-communication)._

## Why give data analytic presentations? 

When you are first starting out you should accept pretty much every opportunity to speak about your research you get. In approximate order of importance, the value of talks early in your career are:

1. To meet people
2. To make people excited about your ideas/software/results
3. To make people understand your ideas/software/results
4. To practice speaking

Later the reasons evolve, altough not be as much as you'd think. The main change is that 4 evolves more into "to show people you are a good speaker".

The importance of point 1 can't be overstated. At the beginning of your career, the primary reason you are giving talks is for people to get to know you. Being well regarded is absolutely not the goal of academia. However, being well known and well regarded can make a huge range of parts of your job easier. So first and foremost make sure you don't forget to talk to people before, after, and during your talk. 

Point 2 is more important than point 3. As a scientist, it is hard to accept that the primary purpose of a talk is advertising, not science. See for example Hilary Mason's great presentation [Entertain, don't teach](http://www.hilarymason.com/speaking/speaking-entertain-dont-teach/). Here are reasons why entertainment is more important:

* People will legit fall asleep on you if you don't keep them awake - this is embarrassing
* People will never understand your ideas/software/results if they fell asleep and didn't hear about them
* There is __no way__ to convey any reasonably complicated scientific idea completely in an hour - even less so in shorter periods of time 
* If you entertain people __they might go read your paper/use your code__ which is the best way to achieve goal 3. 

That being said, be very careful to avoid giving a [TED talk](https://www.ted.com/talks/browse) (unless you are giving a Ted talk!). If you are giving a scientific presentation the goal is to communicate scientific ideas. So while you are entertaining, don't forget why you are entertaining. 

### Why is this part of advanced data science?

The technical components of data science (statistics, computing, databases, etc.) are usually the first things you learn in the field. You might take a course in R programming or in biostatistics to learn how to fit regression models. There is sometimes the mistaken impression when you are taught these tools for the first time that because data science is empirical it means that it isn't a human enterprise. But as we discussed in Week 9, the more advanced you become in data analysis, the more it becomes a communication artform. Just as with written data analyses, it is critical that you are able to convey your data analysis message in oral presentations. Without effective communication the technical, statistical, and computational analyses you perform will not have any impact. 


## Types of data analytic presentations

There are a few different types of data analytic presentations that you will give over the course of your career. The big categories include:

- __Informal group or lab meeting presentations__
  - __Goal__: Update people on what you are doing and get help.
  - __What to talk about__: Research in progress. This may either be a brief update or an attempt to get help. 
* _Short conference talks_ 
  - __Goal__: Introduce yourself and your research so people will want to learn more. 
  - __What to talk about__: Research you have completed, distilled into the highest level form and accessible to a broad audience. 
* _Long form seminar style talks_
  - __Goal__: Introduce yourself and your research so people will want to learn more. 
  - __What to talk about__: Research you have completed with a little bit more detail, but still at a high enough level that most people can follow along. 
* _Job talks_ 
  - __Goal__: Get a job.  
  - __What to talk about__: Research you have completed that highlights your potential, some technical details that are impressive, and a summary of your plans going forward. 
* _Flash talks_ 
  - __Goal__: Give people a teaser of what you are up to and intrigue them enough to read your work or talk to you.   
  - __What to talk about__: Just the high level problem and your most high impact result. 
  
  
There are three "typical" lengths with a little bit of wiggle room on the exact timing: flash (2-5 minutes), short form conference talks or research group updates (15-20 min), and long form seminar talks (50min-1hr). While this description is pretty specific to academic style talks;  getting good at each of these forms of presentation is critical, whether you are in academia, industry or government. 

Elevator pitches in industry, like flash talks in academia, are how you get your foot in the door with potential funders, collaborators, employees, employers, or bosses. Short form talks are a part of updates whether you are in a research group or as a part of a presentation to your management teams. Long form talks are probably a little less common in industry (based on my convenience sample of industry folks) but it is worth learning how to present well anyway in case you want to end up on the keynote lecture circuit and raise your profile in industry. 


  
## Structure of your talk

The biggest trap in giving a talk is assuming that other people will follow you because you follow the talk. In general it is always better to assume your audience knows less than you think they do. People like to feel smart. I have rarely heard complaints about people who went too basic in their explanations, but frequently hear complaints about people being lost. That being said, here are some structural tips. Your mileage may vary. 

* __Always lead with a brief, understandable to everyone statement of your problem__. 
* Explain the data and measurement technology before you explain the features you will use
* Explain the features you will use to model data before you explain the model
* When presenting results, make sure you are telling a story. 

The last point is particularly important. Usually by the results section people are getting a little antsy. So a completely disparate set of results with little story behind them is going to drive people bonkers. Make sure you explain up front where the results are going (e.g. "Results will show our method is the fastest/most accurate/best ever"), then make sure that your results are divided into sections by what point they are making and organized just like they would be if you were telling a story. 

### Flash talk structure

As a person who has been stuck in a large number of interminable flash talks, the main piece of structural advice is to not go long! Typically a flash talk will consist of between 2-5 slides. 

- 1-2 slides to introduce the key problem
- 1-2 slides to introduce the solution
- One slide to point people to a website where they can learn more. 

A key problem people often run into with flash talks (as they are often required to introduce yourself generally to an audience) is that they try to cover too much ground. A flash talk should only have one take home message. 

### Short form talk structure

In 15 minutes you have very little time to get into detail. Typically you might expand the scope of your talk into:

- A few slides to introduce the background
- A few slides to introduce the data
- A few slides describing the methods
- A few slides describing the results
- A slide summarizing conclusions and pointing to further reading

A shorter conference talk may have a couple of key messages, but with this little time, you will likely not have any room to get into detail. The purpose of the talk is to get the audience hooked so that they will read whatever follow up material you point them to, approach you and talk to you after the conference, or invite you to speak in a longer form format. 

### Long form talk structure

A long form talk allows you more space to introduce your topic more thoroughly. But remember, even in 50 minutes, it will be hard to explain everything you did. Nor should you! Remember a data analytic presentation is about telling a story, so you want to keep the same sort of arc: 

- Background
- Introduce the Data
- Introduce the Methods
- Describe the results
- Summarize and point people to next steps

Some of the more painful talks to attend are those that fail to touch one or more of these key points - say by only covering background and methods, or by only describing the results. The point is to take the listener along through the story so they can see the main conclusions, then give them something to do after. 


## Slide style

Now that you've outlined *what* you'll talk about in your presentation, it's time to decide *how* you're going to put those ideas onto slides. There are many things to consider when designing visually-appealing slides. 

### Text

A few guidelines when deciding the words you'll include on slides:

* limit the number of ideas on a single slide
* limit words on slides
* encourage listening (limit reading)
* include references on the slides directly (and at the end!)

Do not try to cram all your ideas onto a single slide. And, everything you say does *not* have to be up on the slides. You're speaking for a reason. The slides should help guide you along in telling your story, but your audience should have to listen to what you're saying to get the full picture of your story. 
  
### Fonts

To convey textual information to your audience, choosing a good font is important. It's generally safe to **stick to Sans Serif font**. Sans Serif fonts can be searched through at [Google Fonts](https://fonts.google.com/). And, when in doubt, **Helvetica is a safe font choice**. Further, use consistent fonts throughout your talk. More than one font *can* be used to draw viewers attention to something, but typically there should be a consistent font used throughout the presentation.  Finally, as with most rules, there are exceptions, so take time deciding on what font looks best for each part of your presentation.
  

![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_86)

### Size

Regardless of what font you choose for your text, your **text should be very large**. It's often argued that you should design your slides for the back of the room. 


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_287)

The same goes for images. There's no need to leave empty space on your slides around images. **Expand your images** to take up as much space on the slide as possible.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_297)

### Colors 

Finally, with regards to slide design, colors matter. Choosing a dark background (such as dark gray) means that your text should be light (maybe white). If your background is light, your text should be dark. Contrast will make it easier on your audience to read.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_307)

Additionally, use color to focus on text you want your audience to focus in on. If all your text is white, highlight a few words in a brighter color to draw your listener's attention to what's important.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_328)

The same goes for figures and plots. All images should have colors that are viewable and distinguishable by every person in your audience. Consider color blindness. Consider colors that tend not to project well (such as yellows or light pastels). Then, design your slides using colors that will work for your audience.

### Alignment

Visually, things should be aligned. Center things in the middle of your slide. Make sure text boxes that should line up do line up. It may seem trivial, but it's important to line things up so viewers aren't distracted by something like alignment and can instead focus on your talk.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_339)

## Presenting

When it comes time to give the presentation, there are a few things to keep in mind. First and foremost, **speak clearly**. Whether you are a loud-talker, a soft-speaker, someone who speaks slowly, or a fast-talker, the most important thing is to make sure that the words you say are clear to your audience.

Second, you should **be excited**. If you're not excited or passionate about what you're talking about, why would your audience be? If you're not excited, it may be best to *reconsider your outline* and re-work your story until you are. 

To avoid being boring during your talk, you can vary the speed and volume of your voice. You can move around so you're not always in one place. And, you can use pauses effectively. It's ok to not speak every second that you're up there. You can pause and give your audience some time to look at a graph before you talk about it. Silence for short periods of time is allowed! 

Finally, be yourself. If you naturally like to tell jokes, tell jokes during your presentation. If stories are more your style, work a story or two in. Ultimately, if you're not comfortable in front of your audience, check to make sure you're being true to who you are as an individual.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_81)

Finally, when presenting it's important to remember that **you've seen the data and figures you're presenting many times, but your audience has not**. They'll need time to get up to speed! Thus, it's important to always introduce your axes (tell your audience what is on the x-axis and what is on the y-axis), explain the colors on your plot, *and* walk the audience through the figure you're presenting.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g4039734916_0_0)


### Be prepared

The day of your presentation, things may go wrong. Power goes out, projectors don't always present your material exactly the same way it looks on your computer screen. Technology doesn't always behave as we expect it too. In these cases, you just have to roll with the punches. 

To avoid any big issues, it's best to bring a copy of your talk on a USB drive, carry any adapters you may need should you have to (or choose to) present from your own computer. Don't expect the location to have the adapter you need. And, be sure your phone is on silent. After that, just roll with anything that goes wrong. The audience will be forgiving, as they all know that technology can sometimes act unexpectedly.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_364)

## Equations

If you are giving a data science talk you will probably have some equations. That is ok. But the way you present them is critically important to giving an understandable talk. Here are a few important points:

* Before presenting an equation explain the data
* Whenever possible use words instead of symbols in equations (_Expression = Noise + Signal_ is better than _E = N + S_ is better than _Y = X + E_)
* No more than two subscripts
* When explaining an equation
  * First explain the point of the equation (we are trying to model expression as a function of noise and signal)
  * Then explain what each symbol is (E is expression, N is noise, etc.)
  * Then explain how the model relates them (E is a linear function of signal and noise)
* Try to avoid subscripts, and no more than two are allowed. 


## Figures

If you have a figure in your talk you should present it in the following way. 
 
* Explain what the figure is supposed to communicate (e.g. "this figure shows our method has higher accuracy")
* Explain the figure axes (e.g. "the y-axis is sensitivity the x-axis is 1-specificity")
* Explain what trends the audience should look for (e.g. "curves that go straight up at zero and across the top of the plot are best")


## Job talk specific issues

When giving a job talk you have an additional job on top of the four main goals we talked about above. The goal is to present your complete professional persona to a bunch of people who (mostly) won't know who you are. You should tailor this a little bit to the place you are applying to a job, but don't try to pretend to be something you are not. You can show a little more theory at a theory place and a few more results at an applied place, but don't claim you are proving theorems all the time if you aren't. 

You should include both at the beginning and the end of the talk brief summaries of all the stuff you have worked on and plan to work on so they get an idea of who you are in a complete sense. __But only talk about one specific project when giving the talk__. There is nothing more detrimental to your chances of getting a job than going way over time or not getting to give your whole talk. 

Two things that I think you want to convey when giving a job talk are:

1. You would be a fun person to work with and can play well with others
2. You have some unique expertise that will strengthen the place you are applying

Traditionally in data science, (bio)statistics and computer science departments, people demonstrated #2 by showing that they could prove really hard theorems or do really difficult computations. At some places, that is still a really good thing to do. Other things that might make you unique are the ability to write amazing R packages that get used, the ability to analyze massive data sets other people can't, the ability to teach courses that students will want to take but the department doesn't have, or ideas about a brand new research area (with some data to back them up). 

Before giving a job talk ask around and get a feel for the sorts of things that people have heard about the place you are applying so you can be smart about your choices of how/what to present. 

## Answering hard questions

Inevitably you will get hard questions during your talk. The most important point is not to panic and not to get defensive. It is way better to just say _I don't know_, then to get upset. When you get asked a really hard question you should:

* Take a second and a deep breath. If necessary, ask the person to repeat the question. 
* Answer the question the best you can come up with on the spot
* Say _I don't know_ if you don't know. If you say I don't know, then you can give your best guess and explain it is a guess. 

The key is to distinguish what kind of response you are giving. Are you giving a response where you know the answer because you actually looked into that? Are you giving a complete guess where you have no idea? Or, what is more likely, are you somewhere in between? 

Most importantly, don't feel embarrassed! Hard questions happen to everyone and if you are polite, explain how sure you are about your answer, and try your best it won't be a problem. 


### That one person who keeps going bonkers on you


Almost everywhere you give a talk there will be a person who is upset/intense/aggressive. __Do not fall into the temptation to be aggressive in return__. Answer their first questions politely just like everyone else. If they keep asking really aggressive/lots of questions, you are within your rightst to say: "You are bringing up a lot of good issues, I'd be happy to discuss with you after the presentation more in depth, but in the interest of time I'm going to move on to the next part of my talk". It is ok to keep things moving and to finish on time. 

## Finishing on time


Do it. People will love you for it. If you are the last speaker in a session and others have gone long, adapt and go shorter. The value you gain by making your audience happy >>>> the extra 5 minutes of details you could have explained


## Where you should put your talk

If you have weblinks in your talk you need to post it online. There is no way people will write down any of the links in your talk. Two good places to put your talks are https://speakerdeck.com/ or http://www.slideshare.net/. But then link to all the talks from one, single, memorable site you can show people at the very end of your talk. All my talks are at http://jtleek.com/talks/. You are welcome to send a pull request with your talk there if it is Leek group related, or you can put them on your own short and sweet web link. 

I personally like Slideshare a little better these days because the slides are much easier to view on mobile phones and iPads, which is the most likely place someone will read your talk. 

## Example Presentation: Methods

To walk you through an example of a data science presentation, we're going to use a talk presented at a statistics conference by [Lucy D'Agostino McGowan]((https://www.lucymcgowan.com/)), a well-known biostatistician and R programmer. The slides used in the talk and a video of the talk itself (!) can be found [here](https://www.lucymcgowan.com/talk/asa_joint_statistical_meeting_2018/). The title of Lucy's talk was "Harnessing the Power of the Web via R Clients for Web APIs." In this talk she discussed accessing information from APIs using the `httr` package. So, if you need a refresher on this topic, [the slides and video here](https://www.lucymcgowan.com/talk/asa_joint_statistical_meeting_2018/) would be a great reference! 

### Talk Outline

In the introduction, Lucy expresses her excitement and gives her audience an outline of the talk. The three topics she's going to cover are: 

* What is an API?
* How are APIs accessed from R
* Case studies.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e029efc87_0_29)

We didn't discuss this above; however, a general rule of thumb is that **three main topics is about the most you should include in a talk**, as humans' attention spans are not very long. Lucy nailed this one with exactly three main topics to discuss, all of which tie together into a story about how to get information from Web APIs!

### Slide Design

As Lucy dives into the content of her talk, she follows many of the best practices discussed above. We'll pull a few slides from the talk to discuss here; however, do reference the whole talk to see it in its entirety!

Lucy uses large fonts and colors that can be distinguished by anyone in the audience and that present well. As a result, everyone in the room, no matter where there seat was, was able to learn and be entertained.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g2bfdb07292_0_151)

Additionally, Lucy uses effective highlighting of text using different colors. Here, the parts of the text that Lucy wants the audience to focus on are in a brighter blue and a brighter green! Also note that there is not a lot of blank space on the slides.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e029efc87_0_6)

Additionally, Lucy's slides guided what she was going to say but didn't include all the words on the slides. Here, we see large font and large images but no words. This allowed the audience to listen to what she was saying rather than read all the words on the slides! 


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e029efc87_0_19)

### Presentation

In addition to having well-designed slides, Lucy was excited as she spoke, was clear in her speech, spoke at an easy-to-listen-to pace, and her personality came through as she spoke. This is all evident if you listen to the video of her presentation. Lucy being true to her personality helps make it a wonderful presentation. If your personality is different than Lucy's, that's totally ok! Just be sure that when you present, you're presenting in a way that you're most comfortable! 

## Example Presentation: Analysis

Lucy's presentation is an example of a wonderful, educational, and helpful talk; however, her goal wasn't to talk in depth about an analysis she's done. Often, as a data scientist, you'll be tasked with presenting an analysis you've done. To do so, you'll want to use the same guidelines we previously discussed, but with a focus on **presenting the story of your data analysis**. This includes the plots, analytical approach, and findings of your project. That said, your slides should still be well-designed, you should still tell a story, and your text and colors should all be readable when projected; however, in this case, there are a few additional caveats to consider. 

To discuss these, we'll use an example presentation from Julia Silge, who is a data scientist at Stack Overflow and a wonderful presenter. In 2017 at the rstudio::conf, [Julia Silge](https://juliasilge.com/about/) presented "Text Mining the tidy Way". The [video](https://www.rstudio.com/resources/videos/text-mining-the-tidy-way/) and [visuals](https://speakerd.s3.amazonaws.com/presentations/d6041c6b704d4bf7bfa9d0973ae2d006/rstudio_conf.pdf) from her presentation are available online. This talk discusses the `tidytext` package (which she and [David Robinson](http://varianceexplained.org/about/) developed) and example analyses using this awesome R package. We've discussed this package previously, but if you want a refresher on tidytext, how to work with textual data, and sentiment analysis, [this](https://www.rstudio.com/resources/videos/text-mining-the-tidy-way/) is a great resource!

As above, we'll highlight a few slides from the talk and discuss considerations to make when presenting a data analysis. 

### Talk Outline

As in Lucy's talk, Julia Silge, in addition to an introduction and a conclusion, had three main parts to her talk:

* `tidytext` package
* Jane Austen example
* NASA example

In data analysis talks, it's often best to start with background information. Julia covers this information when discussing what the `tidytext` package is. Then, she delves into discussing a few examples of the types of analyses you can do with this package.

### Slide Design

As discussed above with Lucy's presentation, in Julia's slides, she limits the amount of information she puts on any one slide, thus allowing the audience to listen to the words she's saying. And, she has text that's large enough and legible when projected.

However, what's different about this presentation is how Julia presents her analyses. When presenting an analysis, it's generally best to first explain the approach and then present the results. For example, Julia uses TF-IDF to analzze text in Jane Austen's novels.

She first explains what TF-IDF is. She includes the bare minimum amount of information on her slide, so that her audience is only seeing what's necessary. Then, she verbally describes what TF-IDF is. 


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_24)

On subsequent slides she includes the code she used to run the analysis, discussing what is going on with the code on each slide and describing the output.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_12)

Finally, for each part of her analysis, she includes a visualization of the results. These figures have text large enough to be seen by all in the audience, are well-labeled, and include an informative title.


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_5)

Note that Julia does not go into every single detail of every analysis, nor just she talk about all the things she tried in a single presentation. She includes enough information so that her audience learns and can go try this type of analysis on their own, if they're interested! 

### Presentation

Watching the [18 minute video](https://www.rstudio.com/resources/videos/text-mining-the-tidy-way/) will give you the best sense of how Julia presented the information in her `tidytext` presentation; however, we'll highlight a few things here. 


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_17)

Julia spoke at a reasonable pace and clearly, keeping her audience interested. Additionally, she presented true to her personality. Julia and Lucy are two different people and that is clear in their presentation styles. Differences are wonderful and help keep presentations interesting! It would be boring if everyone were the same.

Additionally, Julia knew her audience. She knew that there would be many programmers in her audience, and that most of them would be familiar with the R programming language. Thus, she didn't need to explain what the R syntax was. She could put R code on her slides, and her audience would successfully follow along. But, she knew that not everyone has worked with the `tidytext` package. Thus, she focused her time here, discussing the purpose of and basics on how to use the `tidytext` package and provided clear examples of analyses using this package. When outlining and preparing presentations, always consider your audience. If your audience is more technical, include more details about *how* you did the analysis. If they're less technical, be sure to explain what you did at an appropriate level. And, of course, always make sure your figures are clear, regardless of your audience.

We'll note that at around 17:45 in the presentation, Julia went to show an image but it didn't immediately show up how she had intended. This is a great example of rolling with the punches. She didn't panic. She simply acknowledged that it didn't work the first time and tried again. The audience, of course, didn't mind, but when you're presenting, these small occurrences can feel like a big deal. When it happens to you in the future, know that things don't always work as anticipated and that this happens to everyone. If this happens to you, take a play out of Julia's book and simply acknowledge what happened, try again, and continue on!


![](https://docs.google.com/presentation/d/1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg/export/png?id=1SNcN3sJoZ7i7zXieS5MTRpzrgEi_RFInFp9teYFqpIg&pageid=g3e060237c1_0_39)


## Presenting to a General Audience


When considering presenting to a general audience, this would be an audience that doesn't know a lot about data science or quantitative analysis. This would be an audience that generally does not code or analyze data on a regular basis. This could be individuals at your company who are more focused on day-to-day operations or an audience of high schoolers getting their first introduction to data science.

### The Goal

Regardless of exactly to whom you're presenting, the goal of this type of presentation is to **teach at a high level what you did**. Your presentation should still inspire, educate, and entertain, but it should leave out some of the nitty gritty details and keep in more background and general explanation of your approach.

### General Presentation Example 

To discuss giving presentations to a general audience using a specific example, we're going to walk through a presentation that was given to a general audience. The audience for this presentation was college students  with a year  of calculus  but no particular  background in statistics. This means that any statistical concepts would have to be explained, but it could be assumed that the audience was fairly analytical. The slides for this talk can be viewed [here](https://docs.google.com/presentation/d/1AslQFsTHIz4R50KSDuzQtu75AlofrtCD1ZH80lp5k3A/edit?usp=sharing). The title of this talk was "Upcycling genomics data: From publicly-available 'junk' to priceless 'treasure'." 

The outline of this presentation was as follows:

- Introduction
- Part 1: recount
- Part 2: phenopredict
- Part 3: application
- Conclusion

Click on [this link](https://docs.google.com/presentation/d/1AslQFsTHIz4R50KSDuzQtu75AlofrtCD1ZH80lp5k3A/edit?usp=sharing) and scroll through the slides to get an idea of what the presentation looked like. The content of the talk is not what we'll be focusing on, so it doesn't actually matter if you look at these slides and understand what they're talking about. Rather, we're going to walk through how this presentation was organized and designed to focus on a general audience. 

We'll also walk through the slides for a talk on the exact same topic, that that was designed and presented to a technical audience.

To walk through how this talk was organized, we're going to use the following figure:


![](https://docs.google.com/presentation/d/1DW4eO4oQ_0qhAXs0IB-FBp790qeM8gH3ZLq-z58jBYg/export/png?id=1DW4eO4oQ_0qhAXs0IB-FBp790qeM8gH3ZLq-z58jBYg&pageid=g3eb60191d5_0_11)

Each slide in the presentation was assigned to one of 7 categories. Each category is a different color on the figure:

* Question - the motivating question used to tie the story together
* Outline - to remind the audience what we've already discussed and what we're about to discuss
* Background - Information the audience is required to know in order to understand the project/analyses
* Approach - How the data were analyzed
* Teaching - A quick lesson about a specific topic to ensure the results make sense to the audience
* Conclusion - The end of the slides, wrapping up the presentation

If we consider background, teaching, and explaining the approach, we see that about 65% of the time was spent providing information to the audience that had nothing to do with the specific new information being presented about this analysis.

![](https://docs.google.com/presentation/d/1DW4eO4oQ_0qhAXs0IB-FBp790qeM8gH3ZLq-z58jBYg/export/png?id=1DW4eO4oQ_0qhAXs0IB-FBp790qeM8gH3ZLq-z58jBYg&pageid=g3eb60191d5_0_1241)


## Presenting to a Technical Audience 

When presenting to a technical audience, you're presenting to an audience of your peers. These are individuals who regularly analyze data and/or are familiar with your work and the way you approach data analysis. This could be other members of your team or other individuals at a conference in your specific field of expertise. As a result, you can often limit the amount of information you provide as introductory material in this type of presentation and really focus on the details of your analysis.

### The Goal

Unlike a general audience presentation where the goal is to teach at a high level what you did, the goal of this type of presentation is to really **explain details of what you did**. The details and caveats of your approach should be the focus here.


### Technical Presentation Example 

Like in the case of a general talk, we're going to walk through a technical talk. The title of the technical talk we'll be discussing is "Improving the value of public data with recount2 and phenotype prediction" and the slides are viewable [here](bit.ly/technical_audience). Go to these slides now and scroll through them. Note the mathematical notation on slides 70 through 87 -- this level of detail was *not* included for the general audience (slides 96-110 [here for the general audience comparison(bit.ly/general_audience)]. While the title and presentation details differ from the general audience presentation, the outline of the talk remains the same:

- Introduction
- Part 1: recount
- Part 2: phenopredict
- Part 3: application
- Conclusion

We'll break down this talk in the same way that we did the general audience talk.

![](https://docs.google.com/presentation/d/1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk/export/png?id=1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk&pageid=g3eb60054e7_0_192)

We can see that the bulk of the presentation is spent on background, results, and approach. There is not much teaching in this technical presentation.

![](https://docs.google.com/presentation/d/1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk/export/png?id=1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk&pageid=g2bfdb07292_0_151)

### General vs Technical

Each presentation was on the same topic. Thus, it would be beneficial to compare the two directly.

Here we see the general presentation visualized at the top and technical beneath it. The focus on teaching and approach in a general talk and the focus on approach and results in a technical talk becomes evident when compared on the same image.


![](https://docs.google.com/presentation/d/1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk/export/png?id=1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk&pageid=g3f9d5b130f_0_25)

To summarize this graphically, using the same bar plots, here we have the same categories we've looked at previously, but we see the results for each type of presentation. General talk is in green. Technical talk is in orange. When we focus on the results and teaching bars, we can see this general talk did a lot more teaching, while the technical talk focused more time presenting results. 

![](https://docs.google.com/presentation/d/1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk/export/png?id=1EromtzNJS1mzKLOHzV4Cwes4XhrMR23dMXtjqOCUVzk&pageid=g3eb60054e7_0_188)


## Additional Resources

:::resources
* Example talks
  - [Jeff/Leekgroup talks](http://jtleek.com/talks/)
  - [Karl Broman](http://kbroman.org/pages/talks.html)
  - [Zach Holmann](http://zachholman.com/talks)
  - [Hilary Mason](https://hilarymason.com/speaking/)
  - [Jean Fan](https://jef.works/talks/)
* Talk guides
  - [http://www.howtogiveatalk.com/](http://www.howtogiveatalk.com/)
  - [The talk on talks](https://zachholman.com/talk/the-talk-on-talks/)
  - [How to Give a Scientific Presentation](http://www.biostat.wisc.edu/~kbroman/talks/giving_talks.pdf)
* Talk software
  - [xaringan](https://github.com/yihui/xaringan)
  - [xaringanthemer](https://pkg.garrickadenbuie.com/xaringanthemer/)
:::

## Homework 

:::homework
* __Template Repo__: https://github.com/advdatasci/homework12
* __Repo Name__: homework12-ind-yourgithubusername
* __Pull Date__: 2020/11/23 9:00AM Baltimore Time 
:::
