![R Film Series](R-graphic.png)

Please join Fridays from 12 - 1 pm this spring for screenings of excellent talks from the recent Rstudio::conf. We'll be meeting in ETC 105B. Many/most of these talks have useful gems even to folks with only limited exposure to programming and R.

Come for the talks, stay for the follow-up conversation (and free pizza).

* * *

## Schedule

- [Creativity and Tidy Timeseries - February 15th](#creativity-and-tidy-timeseries---february-15th)
- [Animated Graphics - February 22nd](#animated-graphics---february-22nd)
- [How to Teach Programming - March 1st](#how-to-teach-programming---march-1st)
- [Spatial Statistics and Mapping - March 8th](#spatial-statistics-and-mapping---march-8th)
- [The Unreasonable Effectiveness of Public Work - March 15th](#the-unreasonable-effectiveness-of-public-work---march-15th)
- [Case Studies in Social Science - March 22nd](#case-studies-in-social-science---march-22nd)
- [Scientific Reproducibility - April 5th](#scientific-reproducibility---april-5th)
- [Writing Better R - April 12th](#writing-better-r---april-12th)

* * *

### Creativity and Tidy Timeseries - February 15th
[Cultivating creativity in data work](https://resources.rstudio.com/rstudio-conf-2019/cultivating-creativity-in-data-work) - Hilary Parker  
Traditionally, statistical training has focused primarily on mathematical derivations, proofs of statistical tests, and the general correctness of what methods to use for certain applications. However, this is only one dimension of the practice of doing analysis. Other dimensions include the technical mastery of a language and tooling system, and most importantly the construction of a convincing narrative tailored to a specific audience, with the ultimate goal of them accepting the analysis. These "softer" aspects of analysis are difficult to teach, perhaps more so when the field is framed as mathematics and often housed in mathematics departments. In this talk, I discuss an alternative framework for viewing the field, borrowing upon the past work in other fields such as design. Looking forward, we as a field can borrow from these fields to cultivate and hone the creative lens so necessary to the success of applied work.

[Melt the clock Tidy time series analysis](https://resources.rstudio.com/rstudio-conf-2019/melt-the-clock-tidy-time-series-analysis) - Earo Wang  
Time series can be frustrating to work with, particularly when processing raw data into model-ready data. This work presents two new packages that address a gap in existing methodology for time series analysis (raised in rstudio::conf 2018). The tsibble package supports organizing and manipulating modern time series, leveraging tidy data principles along with contextual semantics: index and key. The tsibble data structure seamlessly flows into forecasting routines. The fable package is a tidy renovation of the forecast package. It promotes transparent forecasting practices and concise model representations, to empower analysts tackling a broad domain of forecasting problems. This collection of packages form the tidyverts, which facilitates a fluent and fluid workflow for analyzing time series.

### Animated Graphics - February 22nd
[gganimate cookbook](https://resources.rstudio.com/rstudio-conf-2019/gganimate-live-cookbook) - Thomas Lin Pedersen

[Visualizing uncertainty with hypothetical outcomes plots](https://resources.rstudio.com/rstudio-conf-2019/visualizing-uncertainty-with-hypothetical-outcomes-plots) - Claus Wilke  
Uncertainty is a key component of statistical inference. However, uncertainty is not easy to convey effectively in data visualizations. For example, viewers have a tendency to interpret visualizations of the most likely outcome as the only possible one. Viewers may also misjudge the likelihood of different possible outcomes or the extent to which moderately rare outcomes may deviate from the expectation. One way in which we can help the viewer grasp the amount of uncertainty present in a dataset is by showing a variety of different possible modeling outcomes at once. For example, in a linear regression, we could plot a number of different regression lines with slopes and intercepts drawn from the range of likely values, as determined by the variation in the data. Such visualizations are called Hypothetical Outcomes Plots (HOPs). HOPs can be made in static form, showing the various hypothetical outcomes all at once, or preferably in an animated form, where the display cycles between the different hypothetical outcomes. With recent progress in ggplot2-based animation, via gganimate, as well as packages such as tidybayes that make it easy to generate hypothetical outcomes, we can easily produce animated HOPs in a few lines of R code. This presentation will cover the key concepts, packages, and techniques to generate such visualizations.

### How to Teach Programming - March 1st
[Explicit Direct Instruction in Programming Education](https://resources.rstudio.com/rstudio-conf-2019/opening-keynote-day2) - Felienne  
In education, there is and has always been debate about how to teach. One of these debates centers around the role of the teacher: should their role be minimal, allowing students to find and classify knowledge independently, or should the teacher be in charge of what happens in the classroom, explaining students all they need to know? These forms of teaching have many names, but the most common ones are exploratory learning and direct instruction respectively. While the debate is not settled, more and more evidence is presented by researchers that explicit direct instruction is more effective than exploratory learning in teaching language and mathematics and science. These findings raise the question whether that might be true for programming education too. This is especially of interest since programming education is deeply rooted in the constructionist philosophy, leading many programmers to follow exploratory learning methods, often without being aware of it. This talk outlines this history of programming education and additional beliefs in programming that lead to the prevalence of exploratory forms of teaching. We also explain the didactic principles of direct instruction, explore them in the context of programming, and hypothesize how it might look like for programming.

### Spatial Statistics and Mapping - March 8th
[3D mapping, plotting, and printing with rayshader](https://resources.rstudio.com/rstudio-conf-2019/3d-mapping-plotting-and-printing-with-rayshader) - Tyler Morgan-Wall  

[Spatial data science in the Tidyverse](https://resources.rstudio.com/rstudio-conf-2019/spatial-data-science-in-the-tidyverse) - Edzer Pebesma  
Package sf (simple feature) and ggplot2::geom_sf have caused a fast uptake of tidy spatial data analysis by data scientists. Important spatial data science challenges are not handled by them, including raster and vector data cubes (e.g. socio-economic time series, satellite imagery, weather forecast or climate predictions data), and out-of-memory datasets. Powerful methods to analyse such datasets have been developed in packages stars (spatiotemporal tidy arrays) and tidync (tidy analysis of NetCDF files). This talk discusses how the simple feature and tidy data frameworks are extended to handle these challenging data types, and shows how R can be used for out-of-memory spatial and spatiotemporal datasets using tidy concepts.

### The Unreasonable Effectiveness of Public Work - March 15th
[The unreasonable effectiveness of public work](https://resources.rstudio.com/rstudio-conf-2019/the-unreasonable-effectiveness-of-public-work) - David Robinson  
In this talk, I'll lay out the reasons that blogging, open source contribution, and other forms of public work are a critical part of a data science career. For beginners, a blog is a great accompaniment to data science coursework and tutorials, since it gives you experience applying practical data science skills to real problems. For data scientists at any stage of their careers, open source development offers practice in collaboration, documentation, and interface design that complement other kinds of software development. And for data scientists more advanced in their careers, writing a book is a great way to crystallize your expertise and ensure others can build on it. All of these practices build skills in communication and collaboration that form an essential component of data science work. Each also lets you build a public portfolio of your skills, get feedback from your peers, and network with the larger data science community.

### Case Studies in Social Science - March 22nd
[R at the ACLU: Joining tables to to reunite families](https://resources.rstudio.com/rstudio-conf-2019/r-at-the-aclu-joining-tables-to-to-reunite-families) - Brooke Watson  
Last year, over 2500 immigrant children were separated from their family while in government custody. Information about their status is scattered across several government agencies, and throughout the national class-action lawsuit “Ms. L vs ICE,” the Analytics team of the ACLU has been using R to join, deduplicate, validate, and analyze it. Using specifics of this case, this talk will address common challenges arising from human-generated data in spreadsheets. With generalizable examples, I will discuss data tidying, standardization, deduplication, and validation using the tidyverse, janitor, assertthat, and other packages. Finally, I will share best practices for requesting useful data from non-quantitative subject matter experts.

[Learning and using the tidyverse for historical research](https://resources.rstudio.com/rstudio-conf-2019/learning-and-using-the-tidyverse-for-historical-research) - Jesse Sadler  
My talk will discuss how R, the tidyverse, and the community around R helped me to learn to code and create my first R package. My positive experiences with the resources for learning R and the community itself led me to create a blog detailing my experiences with R as a way to pass along the knowledge that I gained. The next step was to develop my first package. The debkeepr package integrates non-decimal monetary systems of pounds, shillings, and pence into R, making it possible to accurately analyze and visualize historical account books. It is my hope that debkeepr can help bring to light crucial and interesting social interactions that are buried in economic manuscripts, making these stories accessible to a wider audience.

### Scientific Reproducibility - April 5th
[R Markdown: The bigger picture](https://resources.rstudio.com/rstudio-conf-2019/r-markdown-the-bigger-picture) - Garrett Grolemund  
Statistics has made science resemble math, so much so that we've begun to conflate p-values with mathematical proofs. We need to return to evaluating a scientific discovery by its reproducibility, which will require a change in how we report scientific results. This change will be a windfall to commercial data scientists because reproducible means repeatable, automatable, parameterizable, and schedulable.

[A guide to modern reproducible data science with R](https://resources.rstudio.com/rstudio-conf-2019/a-guide-to-modern-reproducible-data-science-with-r) - Karthik Ram

### Writing Better R - April 12th
[Working with categorical data in R without losing your mind](https://resources.rstudio.com/rstudio-conf-2019/working-with-categorical-data-in-r-without-losing-your-mind) - Amelia McNamara  
Categorical data, called “factor” data in R, presents unique challenges in data wrangling. R users often look down at tools like Excel for automatically coercing variables to incorrect datatypes, but factor data in R can produce very similar issues. The stringsAsFactors=HELLNO movement and standard tidyverse defaults have moved us away from the use of factors, but they are sometimes still necessary for analysis. This talk will outline common problems arising from categorical variable transformations in R, and show strategies to avoid them, using both base R and the tidyverse (particularly, dplyr and forcats functions).

[Getting it right: Writing reliable and maintainable R code](https://resources.rstudio.com/rstudio-conf-2019/getting-it-right-writing-reliable-and-maintainable-r-code) - Amanda Gadrow  
How can you tell that your scripts, applications, and package functions are working as expected? Are you sure that when you make changes in one part of the code, it won't break something in another part? Have you thought deeply about how the consumers of your code (including Future You) will use it, maintain it, fix it, and improve it? Code quality is essential not only for reliable results but also for your script's maintainability and your users' satisfaction. Quality can be measured in part with targeted testing, and fortunately, there are several effective and easy-to-use code testing tools available in R. This talk will discuss some of the most useful testing packages, covering both concepts and examples.

