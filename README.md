## Self-Reflection-in-LLMs-MLLMs-A-Lifecycle-Oriented-Repository

### Introduction

Self-reflection in large language models (LLMs) has recently gained attention as a form of metacognitive capability, enabling models to examine, evaluate, and revise their own generated content, reasoning processes, or knowledge boundaries. Current studies broadly categorize such self-reflection into intrinsic and external forms: the former arises autonomously during a model’s internal reasoning process, while the latter is triggered by external signals such as human feedback or automated tools. Several [works](https://oatllm.notion.site/oat-zero#192dba9c0091811a8793e4715fb6f035) have shown that self-reflection has already appeared in the base model that are not explicitly aligned with human preferences. For example, words like "Wait" often appear in the responses of LLMs. They speculate that this might be a manifestation of the LLM's intrinsic self-reflection capability. 

In this repository, we collect some recent LLM self-reflective related papers and roughly classified them according to the following themes (there are no strict category boundaries among these papers, so this classification is for reference only and does not represent the actual attribution).



### Papers

#### Model-Level Reflection: Construction and Alignment

**Post-Training and Alignment**



**Pre-Training**



#### Inference-Time Reflection for Reasoning and Behavioral Control

**Prompting**



**Reasoning Techniques**



**Retrieval-Augmented Methods**



#### Reflection in LLM-Based Agent System




| Time | Title                                                                                              | Venue         | Paper/Code                                                                                   |
|------|----------------------------------------------------------------------------------------------------|---------------|----------------------------------------------------------------------------------------------|
| 2511 | Think Before You Retrieve: Learning Test-Time Adaptive Search with Small Language Models           | arXiv         | [Paper](https://arxiv.org/abs/2511.07581v1)                                                  |
| 2511 | MathSE: Improving Multimodal Mathematical Reasoning via Self-Evolving Iterative Reflection and Reward-Guided Fine-Tuning | AAAI'26       | [Paper](https://arxiv.org/abs/2511.06805v1)                                                  |
| 2511 | You Need Reasoning to Learn Reasoning: The Limitations of Label-Free RL in Weak Base Models       | NeurIPS'25    | [Paper](https://arxiv.org/pdf/2511.04902v1)                                                  |
| 2511 | REVISOR: Beyond Textual Reflection, Towards Multimodal Introspective Reasoning in Long-Form Video Understanding | arXiv         | [Paper](https://arxiv.org/abs/2511.13026v1)                                                  |
| 2511 | An Analysis of Architectural Impact on LLM-based Abstract Visual Reasoning: A Systematic Benchmark on RAVEN-FAIR | arXiv         | [Paper](https://arxiv.org/pdf/2511.11916v1)                                                  |
| 2511 | ChainV: Atomic Visual Hints Make Multimodal Reasoning Shorter and Better                          | arXiv         | [Paper](https://arxiv.org/abs/2511.17106v1)                                                  |
| 2511 | Incorporating Self-Rewriting into Large Language Model Reasoning Reinforcement                     | AAAI'26       | [Paper](https://arxiv.org/pdf/2511.16331v1)                                                  |
| 2506 | From Emergence to Control: Probing and Modulating Self-Reflection in Language Models              | arXiv         | [Paper](https://arxiv.org/pdf/2506.12217v1)                                                  |
| 2504 | VL-Rethinker: Incentivizing Self-Reflection of Vision-Language Models with Reinforcement Learning | arXiv         | [Paper](https://arxiv.org/abs/2504.08837v3)                                                  |
| 2504 | MASR: Self-Reflective Reasoning through Multimodal Hierarchical Attention Focusing for Agent-based Video Understanding | arXiv         | [Paper](https://arxiv.org/abs/2504.17213v2)                                                  |
| 2503 | Understanding R1-Zero-Like Training: A Critical Perspective                                    | COLM'25       | [Paper](https://arxiv.org/pdf/2503.20783v2)                                                  |
| 2502 | There May Not be Aha Moment in R1-Zero-like Training — A Pilot Study                               | arXiv         | [Paper](https://oatllm.notion.site/oat-zero#192dba9c0091811a8793e4715fb6f035)                |
| 2502 | Demystifying Long Chain-of-Thought Reasoning in LLMs                                               | ICLR'25       | [Paper](https://arxiv.org/abs/2502.03373v1)                                                  |
| 2502 | Two Heads Are Better Than One: Dual-Model Verbal Reflection at Inference-Time                     | EMNLP'25      | [Paper](https://arxiv.org/pdf/2502.19230v2)                                                  |
| 2501 | Self-reflecting Large Language Models: A Hegelian Dialectical Approach                            | arXiv         | [Paper](https://arxiv.org/abs/2501.14917v6)                                                  |
| 2501 | Modularized Self-Reflected Video Reasoner for Multimodal LLM with Application to Video Question Answering | ICML'25       | [Paper](https://proceedings.mlr.press/v267/song25g.html)                                     |
| 2406 | TasTe: Teaching Large Language Models to Translate through Self-Reflection                        | ACL'24        | [Paper](https://arxiv.org/abs/2406.08434v1)                                                  |
| 2406 | Self-Reflection Makes Large Language Models Safer, Less Biased, and Ideologically Neutral          | arXiv         | [Paper](https://arxiv.org/abs/2406.10400v2)                                                  |
| 2406 | Re-ReST: Reflection-Reinforced Self-Training for Language Agents                              | arXiv         | [Paper](https://arxiv.org/abs/2406.01495v3)                                                  |
| 2406 | Self-Reflection Outcome is Sensitive to Prompt Construction                                        | arXiv         | [Paper](https://arxiv.org/abs/2406.10400v1)                                                  |
| 2405 | Self-Reflection in LLM Agents: Effects on Problem-Solving Performance                              | FLLM'24       | [Paper](https://arxiv.org/abs/2405.06682v3)                                                  |
| 2404 | COPPER: Reflective Multi-Agent Collaboration based on Large Language Models                       | NIPS'24       | [Paper](https://proceedings.neurips.cc/paper_files/paper/2024/hash/fa54b0edce5eef0bb07654e8ee800cb4-Abstract-Conference.html) |
| 2404 | When Hindsight is Not 20/20: Testing Limits on Reflective Thinking in Large Language Models        | NAACL'24      | [Paper](https://arxiv.org/abs/2404.09129v1)                                                  |
| 2403 | Reinforcement Learning from Reflective Feedback (RLRF): Aligning and Improving LLMs via Fine-Grained Self-Reflection | arXiv         | [Paper](https://arxiv.org/abs/2403.14238v1)                                                  |
| 2402 | Mirror: A Multiple-perspective Self-Reflection Method for Knowledge-rich Reasoning                | ACL'24        | [Paper](https://arxiv.org/abs/2402.14963v2)                                                  |
| 2401 | Self-Contrast: Better Reflection Through Inconsistent Solving Perspectives                        | ACL'24        | [Paper](https://arxiv.org/abs/2401.02009v3)                                                  |
| 2401 | Self-BioRAG: Improving Medical Reasoning through Retrieval and Self-Reflection with Retrieval-Augmented Large Language Models | arXiv         | [Paper](https://arxiv.org/abs/2401.15269v3)                                                  |
| 2310 | Self-RAG: Learning to Retrieve, Generate, and Critique through Self-Reflection                    | ICLR'24       | [Paper](https://arxiv.org/abs/2310.11511v1)                                                  |
| 2310 | Large Language Models Cannot Self-Correct Reasoning Yet                                            | ICLR'24       | [Paper](https://arxiv.org/abs/2310.01798v2)                                                  |
| 2310 | Towards Mitigating LLM Hallucination via Self Reflection                                          | EMNLP'23      | [Paper](https://arxiv.org/abs/2310.06271v1)                                                  |
| 2310 | GPT-4 Doesn’t Know It’s Wrong: An Analysis of Iterative Prompting for Reasoning Problems          | NIPS'23       | [Paper](https://arxiv.org/abs/2310.12397v1)                                                  |
| 2309 | Teaching Large Language Models to Self-Debug                                                       | ICLR'24       | [Paper](https://openreview.net/pdf?id=KuPixIqPiq)                                           |
| 2308 | Reinforced Self-Training (ReST) for Language Modeling                                              | arXiv         | [Paper](https://arxiv.org/abs/2308.08998v2)                                                  |
| 2308 | SelfCheck: Using LLMs to Zero-Shot Check Their Own Step-by-Step Reasoning                         | arXiv         | [Paper](https://arxiv.org/pdf/2308.00436v3)                                                  |
| 2308 | Solving Challenging Math Word Problems Using GPT-4 Code Interpreter with Code-based Self-Verification | ICLR'24       | [Paper](https://openreview.net/forum?id=c8McWs4Av0)                                           |
| 2308 | Shepherd: A Critic for Language Model Generation                                                   | arXiv         | [Paper](https://arxiv.org/pdf/2308.04592v1)                                                  |
| 2306 | Self-Verification Improves Few-Shot Clinical Information Extraction                               | arXiv         | [Paper](https://arxiv.org/pdf/2306.00024)                                                    |
| 2305 | AlpacaFarm: A Simulation Framework for Methods that Learn from Human Feedback                     | NIPS'23       | [Paper](https://arxiv.org/abs/2305.14387v4)                                                  |
| 2305 | Self-Refine: Iterative Refinement with Self-Feedback                                               | NIPS'23       | [Paper](https://arxiv.org/pdf/2303.17651v2)                                                  |
| 2305 | CRITIC: Large Language Models Can Self-Correct with Tool-Interactive Critiquing                   | ICLR'24       | [Paper](https://arxiv.org/abs/2305.11738v4)                                                  |
| 2303 | Reflexion: Language Agents with Verbal Reinforcement Learning                                      | arXiv         | [Paper](https://arxiv.org/abs/2303.11366v4)                                                  |
| 2212 | Constitutional AI: Harmlessness from AI Feedback                                                   | arXiv         | [Paper](https://arxiv.org/pdf/2212.08073v1)                                                  |
| 2211 | Generating Sequences by Learning to Self-Correct                                                   | ICLR'23       | [Paper](https://arxiv.org/abs/2211.00053v1)                                                  |
| 2210 | Large Language Models Can Self-Improve                                                             | EMNLP'23      | [Paper](https://arxiv.org/abs/2210.11610v2)                                                  |
| 2203 | STaR: Bootstrapping Reasoning With Reasoning                                                       | NeurIPS'22    | [Paper](https://arxiv.org/abs/2203.14465v2)                                                  |
| 2203 | Self-Consistency Improves Chain of Thought Reasoning in Language Models                            | ICLR'23       | [Paper](https://arxiv.org/abs/2203.11171v4)                                                  |


### Other Related Awesome Repository

[awesome-llm-self-reflection](https://github.com/rxlqn/awesome-llm-self-reflection)

[self-correction-llm-papers](https://github.com/teacherpeterpan/self-correction-llm-papers)
