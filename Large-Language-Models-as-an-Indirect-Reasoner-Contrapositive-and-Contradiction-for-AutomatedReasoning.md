
---
# Paper-2
## Large Language Models as an Indirect Reasoner: Contrapositive and Contradiction for Automated Reasoning

**Publication Link**: [Link](https://arxiv.org/pdf/2402.03667.pdf)
**Publication Date**: February, 2024

### Abstract
Recently, increasing attention has been drawn to improve the ability of Large Language Models (LLMs) to perform complex reasoning. However, previous methods, such as Chain-of-Thought and  SelfConsistency, mainly follow Direct Reasoning (DR) frameworks, so they will meet difficulty in solving numerous real-world tasks which can hardly be solved via DR. Therefore, to strengthen the reasoning power of LLMs, this paper proposes a novel Indirect Reasoning (IR) method that employs the logic of contrapositives and contradictions to tackle IR tasks such as factual reasoning and mathematical proof. Specifically, our methodology comprises two steps. Firstly, we leverage the logical equivalence of contrapositive to augment the data and rules to enhance the comprehensibility of LLMs. Secondly, we design a set of prompt templates to trigger LLMs to conduct IR based on proof by contradiction that is logically equivalent to the original DR process. Our IR method is simple yet effective and can be straightforwardly integrated with existing DR methods to further boost the reasoning abilities of LLMs. The experimental results on popular LLMs, such as GPT-3.5-turbo and Gemini-pro, show that our IR method enhances the overall accuracy of factual reasoning by 27.33% and mathematical proof by 31.43%, when compared with traditional DR methods. Moreover, the methods combining IR and DR significantly outperform the methods solely using IR or DR, further demonstrating the effectiveness of our strategy.

---

### Summary:
#### Abstract:

##### Problem: 
LLMs often struggle in complex reasoning tasks, to overcome this problem couple of **Direct Reasoning(DR)** frameworks were used. But these frameworks still struggled with real world tasks. 
##### Proposed Solution: 
Authors have proposed **Indirect reasoning(IR)** method that utilizes the logic of contrapositives and contradictions to tackle IR tasks like factual reasoning and mathematical proofs.
##### Methodology:
To improve the comprehensibility of LLMs, the authors have added rules and data using the logical equivalency of contrapositive.

Also,
They create a set of prompt templates that, when used in conjunction with proof by contradiction, logically equates to DR and prompts LLMs to perform IR.

##### Experiment and Result:
The proposed method is simple to use and seamlessly combined with existing DR methods to further boost the reasoning performance of LLMs.
The experiment have been performed on models such as '_GPT-3.5-turbo_' and '_Gemini-pro_', which shows IR method enhances the overall accuracy of _factual reasoning by 27.33%_ and _mathematical proof by 31.43%_ compared to DR method.
*The method combining both IR and DR significantly outperforms methods solely based on IR or DR*.




