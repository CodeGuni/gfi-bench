# gfi-bench
Benchmark to resolve Real-world issues labelled with "good-first-issue". 

## Problem
On-boarding a new open-source repository/community is really difficult.  
The common approach to get started is to go though small issues for new commers.  
Maintainers tag easy-to-resolve issues with the following lavels; `good-first-issue` or `help-wanted`.  
OSS bounty platforms(e.g. [Quira.sh](https://quira.sh) and [OnlyDust.com](https://onlydust.com)) feature good-first-issues mostly.  
However, the actual compretion ratio of resolving the issues and submissing PRs by new commers is **less than 5%**.  
Most of the applicants who comminted to try resolving issues ghost without asking any questions.  

## Solution
Build a AI buddy to assist understing the code base, and suggest how to resolve the issues.  
To generate the right guide for each issues, the following step is required.  
1. LLM knows the answer.
2. LLM can break down the process of problem solving.
3. LLM can generate a step-by-step guidance for each issues.

## Goal
To raise the raio of PR completion to **50%**.

