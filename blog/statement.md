Measuring and Mitigating Alignment Risks of Language Models

Roma Patel


My research uses language to understand and mitigate the socioaffective risks of language model interaction to humans. As language model products are increasingly—and sometimes unknowingly—integrated into people’s lives, the need to measure and mitigate unsafe behaviors is increasingly more urgent. Moreover, it needs to be done in principled academic ways—in collaboration with, but without industry influence and competing incentives.
Although humans are natural communicators and can detect subtle biases (e.g., persuasion or flattery), the harm posed by language models that exhibit such behaviors is too high to ignore.
Separately, existing post-training and alignment paradigms incentivize preference agreement with brittle behavioral guardrails that time and again fail under adversarial pressure.

My work so far has focused on three aspects of this problem:
How can we detect and understand occurrences of safety issues in human language model conversations? [gpt-bias, values]
How can we improve RLHF/alignment pipelines to make them better? [sycophancy, sct-rewards, game theory]
How can we create systems to attack and investigate models? [leagues, probing, sycophancy]

The work that I have done has taken several steps towards answering the above questions. 
We identify subtle ways in which language model generations can influence human behaviors, both in short interactions and along very long time scales [gpt-bias].
We detect and control for sycophantic behaviors of models—situations where preference optimization pipelines reward agreeableness and flattery—and how this can pose dangers to humans [control-syc].
We update the reinforcement learning reward formulation using social choice theory aggregation methods to allow for better aggregation of different rewards [sct-rlhf].
We show how intransitivity in human preferences can be better handled by alignment pipelines that handle game-theoretic objectives, and show how this can recover and handle erasure of minority preferences better. [intransitivity].
We create self-improving adversarial red-teaming systems to uncover dangerous capabilities of models [leagues].
We create datasets for evaluating differing safety perspectives, build models that can handle this better, and also work towards longitudinal measurements of data. [dices, pluralis, long-term].
Building off of this work, my future research will work on answering the following:
How can alignment objectives be grounded in frameworks that allow for fairer representation of conflicting values and stakeholder preferences?
How can we design self-improving multi-agent language systems that can surface emerging failure models and evolving risks in models?
How can we measure and mitigate long-term risks through targeted controlled studies?



Papers:
Controlling sycophancy
Improving RLHF
Red-teaming leagues
Other work: 
gemini model behavior, log monitoring
Grounding language
Game theory
