# TikTok-Task
## Overview
In this project, we create an LLM "coder" that analyzes comments on a TikTok video and categorizes the comments to determine public opinion. The video we chose was a skit about a household conflict between a husband and a wife. Comments were coded according to two binary codes: Concept 1 (agreement with the wife’s mental-load perspective) and Concept 2 (agreement with the husband’s communication-focused perspective). 

## Methods
We created a detailed prompt and used an LLM to label each of 100 comments for Concept 1 and Concept 2. The two of us also manually coded the comments ourselves. To ensure the reliability of our LLM coder, we calculated Inter-Rate Reliability (IRR) scores between the two of us and also between us and the LLM coder.

## Findings
Across all coded comments, commenters tended to lean more toward the wife’s perspective than the husband’s. The (1,0) category (of agreement with the wife only) appeared more frequently than (0,1), suggesting that mental load and exhaustion resonated more strongly with the audience. Also notable is that a meaningful number of comments (10%) were coded (1,1) as well, suggesting that many viewers saw both partners as contributing to the issue at least somewhat equally.