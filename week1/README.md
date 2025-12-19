## LLM Prompting Playground

Practice core LLM prompting techniques essential to using and understanding coding LLMs. The full assignment description
is provided at [assignment.md](./assignment.md)


### Solutions & Key Techniques

This week covered the foundational patterns for building effective LLM-powered applications:

#### 1. Chain of Thought (CoT)
- **Trick**: Instruction to "think step-by-step".
- **Goal**: Improved reasoning by breaking complex problems into intermediate logical steps.

#### 2. Few-Shot (K-Shot) Prompting
- **Trick**: Providing `n` examples of input/output pairs in the prompt.
- **Goal**: Teaching the model specific patterns, formatting, or niche rules without fine-tuning.

#### 3. RAG (Retrieval-Augmented Generation)
- **Trick**: Injecting relevant document chunks into the prompt context.
- **Goal**: Grounding answers in private or up-to-date data to eliminate hallucinations.

#### 4. Reflexion (Self-Correction)
- **Trick**: Feed the model its own errors + a "reflection" prompt to try again.
- **Goal**: Higher reliability by allowing the model to debug its own logic based on test failures.

#### 5. Self-Consistency (Majority Vote)
- **Trick**: Run the same prompt multiple times and pick the most frequent answer.
- **Goal**: Drastically reduces fluke errors in math or logical tasks.

#### 6. Tool Calling
- **Trick**: Forcing structured JSON output that maps to code functions.
- **Goal**: Connecting the LLM's brain to the real world (files, APIs, databases).

Website used to help me understand and finish this week's assignment: 
1. [https://www.promptingguide.ai/techniques](https://www.promptingguide.ai/techniques)
2. [Self-Reflection in LLM Agents: Effects on Problem-Solving Performance
](https://www.youtube.com/watch?v=VCPwYAQTcpE)
