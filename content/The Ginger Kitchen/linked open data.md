---
title:
draft: true
tags:
date:
---
- metadata management (managing all the different streams of metadata)
- entity management (consolidating all the same subject into 1 entity)
- discovery project (linked data ; schma.org)

==
Beyond simple search
- search finds, discovery uncovers
- current search is reliant on keyword search

Contextual relationship
- within the current batches of metadata, no common data points for linked discovery

Challenges
- data quality (naming, missing, incomplete, duplicate, diff standards)
- technical complexity (technical pipelines)

transforming discovery
- systems that can understand their users' language and provides them steps
	- natural language 
	- intent & direct answers
	- comprehensive 
	- everything you need in 1 interaction - 
- "offloading labour to the machine"

search engine trends are shifting as well
- ai as a front door to the internet
- businesses -impetus  "...to become **primary sources** for the ai to 'choose' to platform you"
	- "making the AI trust you and cite you" - grounded in trust, expertise and reliability
	- AI Overviews
	- https://www.searchenginejournal.com/2025-ai-serp-changes-dac-spa/553864/
- Summarising conversation online
- Agentic - delegate entire tasks to AI

Linked Data
- relationality: mapping out relationship between records and entities
- simple statements:
	- Forrest Gump stars Tom Hanks
	- Subject, predicate, object
- to become part of the wider web (how would that work? are there any examples of library systems globally that have intentionally done so; vis a vis crawling and search engine)
- machine readable

![[Pasted image 20251120105959.png]]
![[Pasted image 20251120110027.png]]
Library knowledge graphs
- bibframe -> transforms records into semantic rs
- mutiple entry-points 


AI - ability to parse unstructured text

https://www.oclc.org/en/linked-data.html

Transformation focus (with the inclusion of AI)
- entity-based search engines 

Bibframe - building blocks for web discovery
- treats lib data as entities w relationships abut people, works, concepts
- bibframe data can be indexed by bots, and searched by internet search engines
- bibframe aims to increase visibility and usage of library data on the web
- usually invisible to modern web infrastructure

making our collections are semantically searchable
entity data service, infopedia widget

entity-based search engine
- https://eresources.nlb.gov.sg/linkeddata


- WARC file
- produce a title, abstract and SingHeritage label using the machine (generating metadata)
- explore an automated solution:
	- (1)Data reduction strategy
		- using heuristics, like the about page, using the shortest url, using the 
	- (2) prompt engineering
		- zero shot; chain of thought etc etc
	- (3) Performance management
		- levenshtein - measures characters dissimilarity between generated and manually curated titles
		- BERTscore - semantic similarity between generated abstracts and manually curated abstract
		comparing also against manual datasets
		- graph neural networks
		- https://catboost.ai/

named entity recognition
- look at tokens in bidirection

limitations
- context - manual data labelling
- same prompt, but different outcomes

https://colab.research.google.com/drive/192IG0QFLK1sNDxYp4Sh_c1kViJ1SGm_T
