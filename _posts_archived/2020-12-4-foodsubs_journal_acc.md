---
title: Journal Paper - Ingredient Substitution using FoodKG
categories: [personalization, health, knowledge_graph]
comments: true
---

My research paper, [Ingredient Substitutions Using a Knowledge Graph of Food](https://www.frontiersin.org/articles/10.3389/frai.2020.621766/),
was accepted by the Frontiers in Artificial Intelligence journal. 

This paper tackled the problem of automatically identifying and ranking plausible substitutions
of ingredients in a recipe, motivated by the need to make recipes "healthier" based on personal context.
Part of the problem here is to choose candidate ingredients based on whether they can be considered
"healthy", and another part is how to tell whether ingredients are substitutable versus similar. 
For example, garlic and olive oil are very similar in the sense that they are used together frequently,
but replacing olive oil with garlic probably doesn't make sense in a normal recipe.

In this paper, I take the approach of developing a substitutability heuristic 
(the Diet-Improvement Ingredient Substitutability Heuristic, or DIISH) by leveraging recipes
and linked information available in [FoodKG](https://foodkg.github.io/). To put it simply,
I combine a few word embedding models together with scores capturing the intuitions that (1) substitutable
ingredients are paired with similar ingredients, and (2) substitutable ingredients are used in similar recipes.

I evaluated the work by collecting a few datasets of substitutions from the web, and compared
the performance of DIISH and other baselines at ranking substitutions. I'm currently planning on
getting some of that data together for a proper release, hopefully to help serve as a baseline for 
other people working on similar tasks that investigate the substituability of items.
