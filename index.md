## Zero to Analytics Engineer

You've arrived at an open source curriculum, meant to help an aspiring future Analytics Engineer to go from zero to hirable in this new, emergent profession that blends together elements of data architecture, data analysis, software engineering, and business intelligence. It may also serve as an extended introduction to the role for skeptical executives or hiring managers!

### Why You Should Listen to Me

Great question! I'm Simon, I hired the first grip of Analytics Engineers at WordPress.com and went on to lead the analytics function for that organization's parent company, Automattic. I liked it so much I went on to join Fishtown Analytics, the folks behind *key Analytics Engineering tool* dbt, as a Product Manager. I've worked as an Analytics Engineer, hired Analytics Engineers, managed teams of Analytics Engineers, and today work for the company on the cutting edge of this emergent profession - there are probably other folks who could say more, better, or more interestingly - and I hope they read this, and submit a PR :) 

### What is an Analytics Engineer?

The best introduction is from the one, the only, [Michael Kaminsky](https://kaminsky.rocks/), published at Locally Optimistic: _[The Analytics Engineer](https://locallyoptimistic.com/post/analytics-engineer/)_.

There, he says the job of the Analytics Engineer is to:

>  * Write production-quality ELT code with an eye towards performance and maintainability
>  * Coach analysts and data scientists on software engineering best practices (e.g., building testing suites and CI pipelines)
>  * Build software tools that help data scientists and analysts work more efficiently (e.g., writing an internal R or Python tooling package for analysts to use)
>  * Collaborate with data engineers on infrastructure projects (where they advocate for and emphasize the business value of applications)

This serves as a really _excellent_ structure that we can use to build our curriculum around! I think broadly we'll want to think about the skills we need to be a market-competitive Analytics Engineer as falling into two flavors; **learning how to do the work** and **learning how to work together**.

Before we can do either of those things, we need to start from the beginning: this is meant to be **Zero** to Analytics Engineer, after all, which means we need to explain some of what we will be learning.

### Fundamental Concepts

As we dip a toe into this kind of work, we're going to come across a lot of talk about ELT and ETL - these are in some ways, parallel and competing visions of the way that data should move around and become useful within an organization. It's worth reading a few different takes on the difference:

* [Talend's Blog: ETL vs ELT](https://www.talend.com/resources/elt-vs-etl/)
* [Panoply.io: ETL vs. ELT](https://blog.panoply.io/etl-vs-elt-the-difference-is-in-the-how)
* [Fivetran: ETL vs. ELT](https://fivetran.com/blog/etl-vs-elt)

Broadly, the big difference is, when do we transform our data from its raw format? Before it enters the warehouse? Or, within the warehouse itself? Historically, we'd be motivated to Transform (that's the **T**!) before we pipe data into the warehouse - with modern solutions organizations are finding it easier and more effective to transform within the warehouse - or, after Loading. 

(If all this talk of data warehouses is not landing, there's a [pretty good description of what, exactly, a data warehouse is over at Stitch](https://www.stitchdata.com/resources/data-warehouse/).)

## Learning to do the Work

The core technology, the seed from which all of the Analytics Engineer's organizational and technical advantages flow, comes from the humble **SQL** - ol' Structured Query Language. Some Analytics Engineers also leverage other programming languages - notably Python and R, although proprietary languages like LookML are also great to have in the toolbox - but that comes later. I am of the opinion that at least intermediate SQL knowledge is *absolutely mandatory for anyone wanting to work in this field*. You need it to understand the data, you need it to work in additional key tooling (the world-changing **dbt** for instance) and it's the keystone to ensuring that your organization's information flow is traceable, trackable, and changes are managed and understood by your colleagues.

You need to be good at [SQL](https://en.wikipedia.org/wiki/SQL) - there's no getting around it. 

### Starting with SQL 

My first exposure to SQL was via pretty basic queries against WordPress databases via phpMyAdmin - suboptimal! - and when I first started dedicating myself more to the data profession, I got a lot of value out of [SQL Zoo](https://sqlzoo.net/) - it's still a totally solid place to start, but I think I'd be more likely to recommend something like [Khan Academy's SQL course](https://www.khanacademy.org/computing/computer-programming/sql) - it's free, and it covers all of the core concepts. If you already have a membership somewhere like Code Academy or Datacamp or something like that, I'm sure that's a fine way to get your feet wet as well.

> *(gut check here - giving the above reading and first-steps-into-SQL the appropriate time, especially if you're doing this nights-and-weekends, is probably closer to two months than two weeks. Remember, if you plant tomatoes, you don't keep digging up the seeds to check on them, right? Give yourself the time you need. You're **growing**!)*

Two totally essential concepts that you need to graduate from beginner SQL wrangler to Analytics Engineer are **window functions** and **common table expressions**

Window functions are key to providing useful data quickly and efficiently to all parts of the organization - [Mode's Intro to Advanced SQL](https://mode.com/sql-tutorial/intro-to-advanced-sql/) is a great next step after exploring one of the above courses, and it does a great job covering window functions and their utility.

Common Table Expressions are a bit trickier - there isn't a lot of great hands-on explanation of how to use them, but there's a pretty good discussion on [this Stack Overflow thread](https://stackoverflow.com/questions/4740748/when-to-use-common-table-expression-cte) and in [this Quora conversation](https://www.quora.com/What-is-CTE-in-SQL) - CTEs are good to be aware of, and are always preferable to subqueries in my opinion, especially because they'll help you to start thinking about your data transformation as something that happens in a particular order, always in one direction - which will be important later :)

I'd also suggest, now that you're starting to think about SQL in a familiar way, that you take a look at how different people and organizations style their SQL code - two of my favorites are from [GitLab](https://about.gitlab.com/handbook/business-ops/data-team/platform/sql-style-guide/) and ol' [Matt Mazur](https://mattmazur.com/2019/06/13/mazurs-sql-style-guide/) - you should read them, and ask yourself, why would someone have such strong opinions about how code should be written?

### This is as far as I've written so far!
* Below are items on my to-do list to write soon - or, you could submit a PR for them yourself :)

## Meeting a Warehouse
* BigQuery, Snowflake, etc - probably BQ w/ open data sets, puzzles, solving a problem

## dbt - More Than Meets The Eye
* That's a transformers joke

## Dipping into the BI Layer
* Looker, Mode, Chartio

## Thinking Kimbally
* Just buy the book and read the first four chapters

### Learning to Work Together

## Never Walk Alone
* Locally Optimistic, dbt Slack, Data Twitter (#besttwitter)

## Control Your Version Control Your Self
* Intro to Git 
* Github, GitLab 

## Publish the Personal
* Get something up that you can show off / seek feedback on
* Speak at a meetup / conference
* Blog!

## Seek Employment Programmatically
* Make a list of 30 jobs posted now/recently that you'd want
* Identify common requirements / words
* Build yourself into matching the common pieces




