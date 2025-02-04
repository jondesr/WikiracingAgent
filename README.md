# Background and Motivation
The experience of building AI agents taught me insights that I want to share with you, the reader, on what they are *actually* good for and how to effectively build them.

While I include code in my storytelling, my goal is to prove high-level concepts, not create technical how-tos, hence the code and sample output. While it's possible to download and run the code for yourself there's no need to as I've included run results whereever appropriate.

## Key Takeaways

### Models hallucinate, but agents kill.
Ask a model to summarize a document and you're running the risk of getting a polished but grossly incorrect summary. 

By comparison, if you're trusting an agent to actually take an action on your behalf through it's internal reasonig and now you're running the risk of using whichever tools and access you gave it to kill you. Okay, that "kill" is a hyperbole, but absolutely you should expect the agent, at a minimum, to maliciously comply with any ambiguous instructions.

As a lighthearted example, and a tribute to dads everywhere, here's a video demonstrating malicious compliance as it relates to... making a sandwich:
https://youtu.be/FN2RM-CHkuI?t=37

# Table of contents
1. [Naive Wikiracing Agent](https://github.com/jondesr/WikiracingAgent/blob/main/01_naive_agent.ipynb)