# Lab 05 — Conclusion

<!--
Read this before you write.

This file is graded by your instructor, by hand, and it is worth 6 of the 15 points.

- Type it yourself. Do not use a chatbot, an AI assistant, an AI autocomplete or a "rewrite my
  text" tool for any part of it, not even for grammar. English that is plain and a little
  clumsy but yours is better than polished text that is not.
- Use your own numbers. Every number you quote must be one your own notebook printed. Copy
  the number exactly as it appeared. A number your notebook did not print is marked as wrong.
- Answer in your own words, about 80-200 words per question. A short answer that uses your
  numbers beats a long answer that could have been written by anyone.
- Delete these comment lines if you like. Keep the three headings and the last line.
-->

## 1. Which layer changed your results the most?

Give the numbers before -> after for that layer (correct / wrong / no answer, out of 20) and say
whether it changed what the agent *can do* or only what it *admits*. If no layer changed the
number of correct answers, say so and explain what the layers did change instead.

the biggest improve for all results it was layer 3 agent without addition give 16 correct answer 4 cons answer and 4 without reason and with full set function layer 3 give 18 correct answer 4 cons and 2 without reason and counts of correct answer 2x  a counts of cons answer -2x and layer 3 changed agent approach to answer checking it improved reliability but not errors

## 2. One failure the full harness did not fix

Pick one question that the full harness (layer 3) still gets wrong or refuses. Give its id
(q01 ... q20). Open its trace in the notebook: at which step did it go wrong, and what did
the model do instead? Name one thing you would add to the harness, and what it would cost
(extra model calls, tokens, time, or a new way to fail).

question 11 is still wrong even using full setup tool gave correct result but model answered Almaty REgion when answer was Almaty city error happened when model read tool result i would add oe more check it would check if chosen region had the highest or the lowest value in the result but this needs more work and maybe it takes more time in addition more tokens 

## 3. Workflow or agent for the monthly ranking?

Dala Insight wants to publish, every month, "which region is highest and which is lowest on one
indicator in one year". Would you ship the fixed workflow or the agent? Use the accuracy, the
number of model calls, the tokens and the time you measured in Part 1. Then say in one sentence
what kind of question would make you choose the other one.

for monthly rankings i would choose fixed workflow it gave 13 of 15 correct answers compared 9 of 15 usinig sample agent it also made 15 call instead 26 used 3852 tokens instead 19835 and 15,7 second instead 49,1 second workflow accurate faster cheaper for rankings tasks for open question require using some tools for flexible and hard analysis i would choose agent

---

I wrote this file myself, without any AI tool.
