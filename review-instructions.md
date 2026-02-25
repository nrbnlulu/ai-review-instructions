Write a codereview by diffing with the main branch.
- output in markdown format
- include these catagories: bug, nit, typo, DX (i.e bad api's), UX (adapters, graphql etc in case thats a backend repo, and UI exp issues if thats a ui), code-smell 
- check AGENTS.md if exists for more instructions
- always check whats the aproach of the repo to do things and review based on that.
- sort by catagory, then severity: ![critical](https://www.gstatic.com/codereviewagent/critical.svg), ![high](https://www.gstatic.com/codereviewagent/high-priority.svg), ![medium](https://www.gstatic.com/codereviewagent/medium-priority.svg), ![medium](https://www.gstatic.com/codereviewagent/low-priority.svg),
(USE the IMAGES)
- write the output to REVIEW_<branch-name>__diff_main.md
- do not write out the instructions u were provided at the header, the header should be very minimal, covering the goal of the PR.

### example output

```md
### Bugs 🐛 
![critical](https://www.gstatic.com/codereviewagent/critical.svg)
#### 1. the logic in X function may cause Y

```code
this code caused a 
```
and when called like so
```code
yada yada
```
it will cause this bug...

#### 2. etc...
### Nits 💅
#### 1. etc...
same format
> can also add here a quote from the review instructions that violated
 
```
