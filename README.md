# CSUN BANA 622 (Programming for Business Analytics)


![https://github.com/wsphd/csun-hpc](images/qr.svg "https://github.com/wsphd/csun-bana622")\
<https://github.com/wsphd/csun-bana622/>

**CSUN BANA 622 (Programming for Business Analytics)**\
**Trade-offs, Tensions, and Transitions**

**Thursday, May 1, 2025**

**Wayne Smith, Ph.D., _Department of Management_, <ws@csun.edu>**


## Introduction/Background/Motivation

  * Programming supports Analytics but Analytics, fundamentally, supports Decison-making
    * Analytics or Automation?: [Seven Approaches to Decision Making (see slide #4)](https://ocw.smithw.org/mgt360/hbr-davenport-better-decisions.pptx)

  * (Horizontal) Workflow
    * Where in the data workflow are you (and your team) working?: [Disney Workflow example]<images/analytics-disney.pdf>

  * (Vertical) Stack
    * Where in the technology stack are you (and your team) working?: [Analytics Stack example]<images/analytics-stack.pdf>

  * Even with Programming, remember your 'First Principles'
    * _Architecture_: Enterprise, Standards, Regulatory, Ethics, Funding, Strategy, etc.
    * _Engineering_: Safety, security, sustainability, reliability, interoperability, maintainability, durability, scalability, performance, etc.
    * _Construction_: Agile, Development Effectiveness, Development Productivity, etc.



  * How do you learn best?
    * Books, Classes, Data camps, User Groups/Meetups, Conferences, Workshops, YouTube, podcasts
    * Some contemporary tools are highly interactive: [Google Colab]<https://colab.research.google.com/>
    * Bottom line: programming is no different than any other skill--it's mostly just _practice_


## Trade-offs: Graphical User Interface (GUI) vs. Command Line Interface (CLI)

  * Tensions
    * What are the Skills, Knowledge, and Abilities of you?...your team?...non-team colleagues?...organization's decision-makers?
    * What is important? Reproducibility?...Scalability...Interoperability?

  * Transitions (Should You Learn to Code?)
    * : Pro (yes): [UK programming requirement]<https://www.gov.uk/government/publications/national-curriculum-in-england-computing-programmes-of-study/national-curriculum-in-england-computing-programmes-of-study>
    * : Con (no): [AI-assisted programming (GitHub Co-pilot)]<https://github.com/features/copilot>


## Trade-offs: Commerical Off-the=Shelf (COTS) vs. Free/Open Source Software (FOSS)

  * Tensions
    * MS-PowerBI (Business Intelligence), Tableau
    * R, Python, Julia, Observable

  * Transitions
    * [Open Source Adoption in the Pharmaceutical Industry]<https://www.r-bloggers.com/2025/02/open-source-adoption-in-pharma-opportunities-and-challenges/>


## Trade-offs: Relatively Platform-dependent vs. Relatively Platform-independent

  * Tensions
    * R, Python, Julia
      * Even within R there are choices- e.g., base R, tidyverse, data.table, DBI, polars
      * Even within Python there are choices- e.g., base Python, pandas, Relational DBMS, noSQL
      * Even within Julia there are choices- e.g., base Julia, DataFrames.jl, Query.jl, DataToolKit.jl

  * Transitions
    *


## Trade-offs: Text Editor (with or without some code help) v. Integrated Development Environments (IDE)

  * Tensions
    * R, Python, Julia
      * With R, users often use [R/Studio]<https://www.markdownguide.org/getting-started/>
      * With Python, users often use [Spyder]<https://www.spyder-ide.org/>, [PyCharm]<https://www.jetbrains.com/pycharm/features/>
      * Many Julia users use [Visual Studio (VS) Code]<https://code.visualstudio.com/>

  * Transitions
    * Some R and Python users are moving to [Positron]<https://positron.posit.co/start.html>


## Trade-offs: Need Application Programming Interfaces (APIs) or Microservices?

  * Tensions
    * You can't automate anything without non-interactive access to data
    * In fact, there is an entire field devoted to it: Data Engineering

  * Transitions
    * REST is common but SPARQL is slowly replacing it [GRAPHQL]<https://en.wikipedia.org/wiki/GraphQL>


## Trade-offs: Databases vs. (binary) Files vs. (human-readable) Flat Files

  * Tensions
    * Databases (structured access, ACID-compliance)
      * Row-oriented Databases (e.g., Postgres, MySQL, SQLite)
      * Column-oriented Databases (e.g., Amazon RedShift, Google Cloud BigTable, MonetDB, DuckDB)
    * (binary) file formats (e.g., xlsx, arrow, parquet)
    * (human-readable) file formats (e.g., csv, tsv, JSON, space-delimited)
    * some industries have highly unique file formats (some are decades old)

  * Transitions
    * small files: CSV files are still common but JSON files are slowly replacing them [JSON]<https://en.wikipedia.org/wiki/JSON>
    * bit files: CSV files are still common but Parquet files are slowly replacing them [Parquet]<https://parquet.apache.org/>


## Trade-offs: Verbose Documentation (large and explicit) vs. Terse Documentation (small and implicit)

  * Tensions
    * It takes time, energy, resources, and perhaps most important, motivation
    * It has to be part of the organization/engineering culture you create, craft, and nurture
    * It can be done by specialists but it is best done by the individual herself/himself

  * Transitions
    * Extensive In-line documentation, especially at the function level, can be done [e.g., ROXYGEN2]<https://roxygen2.r-lib.org/>
    * Extensive out-of-code documentation can be done elegantly and simply [e.g., markdown]<https://www.markdownguide.org/getting-started/>

