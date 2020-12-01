---
title: DBpedia Hackathon - Shiritori KG 
categories: [knowledge_graph]
comments: true
---

I participated in DBpedia's Autumn 2020 [Hackathon](https://wiki.dbpedia.org/events/dbpedia-autumn-hackathon-2020). 
I joined as part of the [Diffbot](https://www.diffbot.com/) track, which granted access to Diffbot's knowledge graph
and its natural language api. 

For my submission, I scrapped together an app called KG Shiritori. This is a play on an age-old Japanese word game,
where players take turns saying words that match the last letter of the previous word (e.g., dog->gate->egg->...).

To spin this game to work on the kind of information available in a knowledge graph, in KG Shiritori you make
connections between entities using common facts about them. For example, "Barack Obama" and "George W. Bush" can
be connected by the fact that they had the employment title "president". 

![KG Shiritori App](https://raw.githubusercontent.com/solashirai/KGShiritori_diffbot/master/app_image.png) 

Diffbot's knowledge graph was used to identify entities as well as a large collection of "facts" about them.
I also used Diffbot's natural language API to parse input sentences to allow users to play the game.

My implementation is [open source](https://github.com/solashirai/KGShiritori_diffbot), but it requires an access token
to Diffbot's APIs so it unfortunately isn't available to try for yourself. You can watch a sloppy demo video
of me walking through the app [here](https://www.youtube.com/watch?v=BtSgWrNE7M8).  
