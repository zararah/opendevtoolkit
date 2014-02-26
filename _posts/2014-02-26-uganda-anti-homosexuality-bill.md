---
layout: post
tagline: ""
tags : [tech, open development, data dive, IATI, AidView]
title: "The effect of human rights abuses on aid policy decisions - diving into Ugandan aid data"
unlisted: false
---

Uganda's president, Yoweri Museveni, recently signed a bill that imposes harsh penalities for "homosexual offences", using the terms "mercenaries" and "prostitutes" to describe gay people. His [homophobic comments](http://www.aljazeera.com/news/africa/2014/02/ugandan-president-sign-anti-gay-bill-20142245119120579.html), as well as those from his cabinet, have been met with international contempt, with Barack Obama warning that US-Uganda ties may be damaged, [Norway announcing that they will be withholding $8m in development aid, Denmark diverting $9m away from the government](http://www.theguardian.com/global-development/2014/feb/25/uganda-donors-cut-aid-anti-gay-law) towards private sector initiatives, aid agencies and rights organisations, and [the Netherlands also announcing that they will be witholding aid.](http://online.wsj.com/news/articles/SB10001424052702304834704579404943830788778)

Despite the new bill imposing life sentences for gay sex and same-sex marriage, Uganda's Health Minister has encouraged people to fully disclose their sexual orientation to health workers, who will ["live up to their ethics of keeping confidentiality of their patients."](http://www.bbc.co.uk/news/world-africa-26349166). Unsurprisingly, aid charities are warning [the new bill will have "disastrous" effects on the country's response to HIV.](http://www.bbc.co.uk/news/world-africa-26349166)

So what might this mean in terms of overall aid flows to Uganda? Are there donors who have been funding campaigns or activities fighting for homosexual rights, and given the implications of the bill on healthcare, what kind of aid does Uganda receive for its health sector? Using only **tools designed to help make IATI data accessible** - rather than raw IATI data - we'll see how many of those questions can be answered here. 

### Aid flows to Uganda - a summary

To get a general overview of aid to Uganda, we used [AidView](http://www.aidview.net/) which pulls data from the [IATI Registry](http://www.iatiregistry.org/). Using the ['Filter by Country'](http://www.aidview.net/filter/Country) option, we can see that Uganda received a total of $9 billion in aid, and has 1105 activities funded. It's unclear, however, for what timescale this value is applicable; for just the past year, or the current year? A total of $9 billion seems highly unlikely to be for just one year - so we'll assume it's **all IATI activities** though this is not so helpful. 
Choosing to [view these activities by list](http://www.aidview.net/activities?Country=UG&view=list) (much more user-friendly than 'view as bubbles') brings up the entire list, but shows only 20 activities per page. 

By using the Filter by Sector option, which works on top of the Country Filter, we can see a selection of [32 different 'sectors'](http://www.aidview.net/filter/SectorCategory?Country=UG&view=list) again in bubble format. Nothing specifically about gay rights is mentioned in any of these sector categorisations, but there are some ambiguous sectors, such as ["Unallocated/Unspecified"](http://www.aidview.net/activities?Country=UG&view=list&SectorCategory=998). A quick scan through this list didn't bring anything relevant up, and likewise for the [Government and Civil society](http://www.aidview.net/activities?Country=UG&view=list&SectorCategory=151&p=1)

But while gay rights specifically doesn't seem to be mentioned in aid activities in Uganda, activities centred around health certainly are.

### Health aid 

According again to the Sector Filter from AidView, a total of $165 million was spent in health aid activities, through 37 activities (again, the timescale for these activities is unclear). Interestingly, the only health projects here that are focused on HIV / AIDS are majority funded by the UK, though some in partnership with other multilateral donors such as this project to [improve delivery of HIV Prevention Services](http://www.aidview.net/activity/GB-1-200787-103) between the UNDP and the UK's Department for International Development. 

Through the ['data file' option](http://www.aidview.net/data-file?Country=UG&view=false&SectorCategory=121&p=2) with the two filters of Uganda and Health on, it's also clearly shown that the UK is/was by far the biggest donor in terms of health aid, providing 62.5% of the total health budget, followed by the World Bank's [International Development Association](http://www.worldbank.org/ida/) with 25.6%. According to this data, none of the countries who have said they will withold aid from Uganda are currently funding any health-related projects in the countries. 


### Aid flows from the UK...

On the UK's aid data site, [DevTracker](http://devtracker.dfid.gov.uk/), we can easily see through the [Uganda Country Profile](http://devtracker.dfid.gov.uk/countries/UG/) a number of key statistics - nearly £106 million was spent in Uganda 2013, which works out at 1.06% of the total UK aid budget. Though one of their priorities is stated as "protecting the poorest and most vulnerable" they don't appear to have any project specifically working on gay rights. 

But, given the information shown in AidView above, looking at activities in Uganda in the Health sector also brings up some relevant aid projects, and we can see via DevTracker that 23.18% of the UK's aid budget to Uganda is spent on health. A couple of projects appear in DevTracker that don't show up in AidView, such as ["an Integrated Youth-Led HIV Prevention & Livelihood Project"](http://devtracker.dfid.gov.uk/projects/GB-1-200991/)

Looking at the bigger picture briefly, the only project anywhere in the world funded by the UK government that appears to be supporting gay rights is the ["Global Fund for Men who have sex with Men"](http://devtracker.dfid.gov.uk/projects/GB-1-200886/), with a budget of nearly 1 million GBP, and the project description "to contribute to ensuring equitable access to effective HIV prevention, care and treatment services tailored to the needs of gay men and other men who have sex with men". Assuming the fund was active in areas of the world which might have homophobic laws in place, it sensibly has 'No Country Specified' so we don't know if the project has been active in Uganda. 

### From the Netherlands...

The Netherlands, alongside Denmark and Norway has also announced that they will be cutting aid. Looking at the Aid portal from the Netherlands, [OpenAid.nl](http://www.openaid.nl), we can see [a list of activities](http://www.openaid.nl/projects/?countries=UG), but unfortunately no totals or summaries of how much aid is spent. While there is also a "sector filter" - with much more detailed categories than the previous tools - the lack of functionality to see any totals aggregated here means that it's not possible (as far as I can tell!) to see how much is spent on, for example, the health sector in total by the Netherlands. 

### In conclusion... 

Using only IATI data tools, it's been fairly difficult to get an overall view of the aid flows into Uganda; AidView provides good summaries, but without time periods the data given is without context. To note, though, that AidView is still in prototype stage, so perhaps this feature will be coming later. Also, given that the data in IATI is not (yet!) covering all aid activities from all countries, it's difficult to know what conclusions can be drawn directly from the data provided - for example, US aid to Uganda didn't show up in AidView, giving the misleading impression that the UK was the biggest donor. 

In fact, when trying to get an idea of aid flows to Uganda, the most convincing figure of **total amount of aid received by Uganda** was from a [PDF report](http://devinit.org/wp-content/uploads/2013/09/Investments-to-End-Poverty-Chapter-10-Uganda.pdf) produced by [Development Initiatives](http://devinit.org), which states that Uganda received US$1.6 billion in 2011, with the US as the largest funder. In total, almost a third of Official Development Assistance (ODA) is spent on health. 75% of ODA spent on health is provided by the US, the UK, and the Global Fund; so here it's clear that the countries which have announced that they will be cutting aid aren't large contributors to health assistance within Uganda. 

The amounts of aid declared by Norway and Denmark that will be withdrawn, which comes to a total of $17 million, is (taking the figure of what was received in 2011) just 1.06% of what Uganda receives in Official Development Assistance; too small then, to provide any real pressure upon the government. 

But ODA as a whole forms a considerable 8.04% of the country's GDP, which stood at [$19.88 billion in 2012](http://data.worldbank.org/country/uganda); if, for example, the top 10 largest donors (who between them provide $1.4billion of the total $1.6 billion) were to decide to redirect or withhold aid flows to Uganda as a result of the law, the impact would be much higher. 

No judgement is made on whether this decision would be the right one in terms of the effect on the Ugandan people, or as a pressure tool - this was simply an exercise in seeing what could be found out from data available online about Ugandan aid flows. 

Have we missed anything? Drop [@OpenDevToolkit](http://twitter.com/opendevtoolkit) a line if so! 


