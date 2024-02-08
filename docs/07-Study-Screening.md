---
bibliography: references.bib
---

# Study Screening {#screening}

At this point we have established our research question(s), set up our inclusion criteria, searched databases, located our studies, removed duplicates, and created our own database of abstracts for review. That seems like a lot, but don't worry, we're just getting started with the systematic review process.

What's next?

Well, we need to review these abstracts to see if they meet the inclusion criteria.

## Phases of Study Screening

I like to break down study screening into two phases, creatively named, Phase I and Phase II.

### Phase I Screening

I consider Phase I screening to be title and abstract screening. In this phase, we want to review the titles and abstracts of studies in our database to see if they *appear* to meet the inclusion criteria or not. If they do, we mark them for inclusion in the next phase. If not, we mark them for exclusion. If we're not sure, then we mark them for inclusion in the next phase.

You're probably wondering, how do we mark studies? Well there are a bunch of a different options. One is to use a spreadsheet. This is how I did abstract screening for more than a decade (I now use software). It just works. But there is also software that can help (discussed below).

When you're done with abstract screening, it is important to write down how many studies were excluded. This will end up in your PRISMA flowchart.

#### Abstract Screening Tools

You can use a simple spreadsheet to keep track of your decisions to include or exclude studies. I usually use an Excel file or Google Sheet if I'm using a spreadsheet for tracking. If you created your database in a citation management system, you can generally export your database as a .csv. When you do that, so long as the databases your originally searched exported the abstract with the citation information (I hope you didn't forget that step!), you'll have everything you need, and more, in that .csv file. Typically each row will be a specific study, and I'll create a new column to indicate inclusion or exclusion. I use a 1 to indicate retaining a study, and a 0 to indicate excluding a study. That way at the end I can sort that column to get all my included studies together. It's simple and it works.

Another option is to use software like [ASReview](https://asreview.nl/) (free at the time of writing), [Rayyan](https://www.rayyan.ai/) (at the time of writing there is a free version), [Covidence](https://www.covidence.org/) (not free at the time of writing), or [MetaReviewer](https://www.metareviewer.org/) (free at the time of writing). There are other programs as well, those are just the four I'm most familiar with. I just completed a couple reviews using ASReview and Rayyan (January, 2024). Specifically, I used ASReview for abstract screening and Rayyan to keep track of inclusion and exclusion during full-text review. I really enjoyed using both, but that doesn't mean they will work well for your workflow. In my limited experience with Covidence it was relatively similar in terms of features. But alas, your experience may differ because software programs tend to change relatively frequently. [Consequently, my recommendation is to try out the different options and see what works best for your workflow.]{.underline}

### Phase II Screening

We've reviewed our abstracts and now we have a set of studies that might meet our inclusion criteria. First, let's write down how many studies we have left. This will end up in our PRISMA flow chart.

Next is the *really fun* task of locating the full text of all of the studies that need to be reviewed. I was taught to save the files using the naming convention of 'FirstauthorlastnameSecondauthorlastnameYear'. For example, Schroeder and Kucera (2022)[@schroeder2022] would be saved as SchroederKucera2022. This system has worked really well for me so I don't see myself changing that.

From time to time, you may not be able to locate the full text of a study. If so, write down how many you couldn't locate. This will also go in your PRISMA flowchart.

The next step is really easy: We review the full-text of each study to see if it meets the inclusion criteria or not. However, you should keep track of *why each study was excluded, because the summary numbers will go in your PRISMA flow chart.* These reasons will be related to your inclusion and exclusion criteria.

## Inter-rater Reliability or Agreement

You need to calculate inter-rater agreement or inter-rater reliability anytime you have more than one coder involved in the screening process. Generally speaking, I see 10-20% of the sample dual coded for inter-rater agreement or reliability purposes. 20% is what I would call "standard", while smaller percentages are occasionally used with larger reviews.

How do you calculate this? Well, it depends on what you are calculating. Many times I see a simple inter-rater agreement statistic reported as a percentage. This is OK. Cohen's kappa is another option if there are two raters. I've also seen correlation coefficients reported. What is most appropriate depends on your study and your data.

## Automation Tools

At the time of writing (January, 2024), we are seeing the rise of AI-assisted abstract screening. A number of different software platforms can aid with this. Is it a good idea? Time will tell. Before relying on AI-assisted screening, where you have AI-exclude studies based on algorithms, I recommend looking for evidence that the software works well for your use case. This type of work exists in the literature and can help guide what types of software works best, and how different algorithms perform in different scenarios. We recently (January, 2024) used [ASReview](https://asreview.nl/) after reading this [preprint by Campos et al. (2023)](https://osf.io/preprints/psyarxiv/fpwc2/download)[@campos2023]. Overall, using ASReview was a very positive experience for us, but we likely would have screened all of the studies had we not read the findings of Campos et al. (2023)[@campos2023]. One benefit of the AI-assisted screening however is the ability to move the most relevant studies first. Even if all abstracts are reviewed, this process alone could likely save the screener time.
