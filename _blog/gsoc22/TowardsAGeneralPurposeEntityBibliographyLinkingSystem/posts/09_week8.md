---
layout: page
title: Week 8
author: 'Circle Chen'
tags: ["week","gsoc","gsoc2022","towardsAGeneralPurposeEntityBibliographyLinkingSystem","week#8","eval#2"]
---

## Week Summary

This week we continue our work on publications and proveniences. I've also fixed issue [#1053](https://gitlab.com/cdli/framework/-/issues/1053).

The infrastructure for connecting entities and publications should be already in place. However, the biggest challenge is to actually find connections between publications and proveniences.

I tried to do some exploration on pdf mining (which inherits from AWCA). But a lot of them are in the transliteration format, so not sure what we can do with those here.

## Daily Work Update

|\#|Day|Date|A short description of the work done|  
|---	|---	|---	|---	|  
|1   	| Monday 	|   2022/08/01	| Issue 1053 fix. Discussion on further work on infrastructure code. |  
|2   	| Tuesday  	|   2022/08/02	| Exploration on pdf mining. |  
|3   	| Wednesday |  2022/08/03 	| Figured out that we should ditch ML-based mining. Just using regex might be better. |  
|4   	| Thursday  |   2022/08/04	| Ran provenience finding algorithms on existing text files of publications. |  
|5   	| Friday  	|   2022/01/01	|  |  
|6   	| Saturday  |  2022/01/01	|  |  
|7   	| Sunday  	|   2022/01/01	|  |  
