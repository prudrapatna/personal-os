# Yann LeCun - Knowledge Base

## Core Concepts & Philosophy
> "The fundamental challenge in AI is building systems that can understand, reason, and plan."

### 1. Objective-Driven AI
AI systems designed to reason and plan by optimizing a set of objectives, including both task-specific goals and safety "guardrails." This contrasts with purely generative or reactive models.

### 2. World Models
The foundation for planning and reasoning. A "world model" allows an AI to predict the consequences of its actions (and the state of the world) without actually executing them.

### 3. Self-Supervised Learning (SSL)
The most efficient way for AI to learn how the world works, primarily from observational data (like video) rather than reinforcement learning or supervised learning.

### 4. Joint Embedding Predictive Architectures (JEPA)
A superior alternative to generative models. JEPA (and V-JEPA) learns abstract representations to predict *semantics* rather than trying to predict every single pixel (generative).
- **Key Insight**: Prediction in representation space > Prediction in pixel space.

### 5. Critique of LLMs
Auto-regressive LLMs lack true understanding, planning, and reasoning. Simply scaling them is not the path to human-level intelligence (AMI).

### 6. Hierarchical Planning
The ability to break down complex goals (e.g., "travel to Paris") into a hierarchy of sub-goals and actions.

---

## Resource Library

### 📄 Research Papers

**LeJEPA: Provable and Scalable Self-Supervised Learning Without the Heuristics**
[https://arxiv.org/pdf/2511.08544](https://arxiv.org/pdf/2511.08544)

**V-JEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning**
[https://arxiv.org/pdf/2506.09985](https://arxiv.org/pdf/2506.09985)

**Learning from Reward-Free Offline Data: A Case for Planning with Latent Dynamics Models**
[https://latent-planning.github.io/static/paper.pdf](https://latent-planning.github.io/static/paper.pdf)

**TRIBE: TRImodal Brain Encoder for whole-brain fMRI response prediction**
[https://arxiv.org/pdf/2507.22229](https://arxiv.org/pdf/2507.22229)

**A Path Towards Autonomous Machine Intelligence**
[https://openreview.net/pdf?id=BZ5a1r-kVsf](https://openreview.net/pdf?id=BZ5a1r-kVsf)

**Planning with Reasoning using Vision Language World Model**
[https://arxiv.org/pdf/2509.02722](https://arxiv.org/pdf/2509.02722)

**VJEPA 2: Self-Supervised Video Models Enable Understanding, Prediction and Planning**
https://arxiv.org/pdf/2506.09985](https://arxiv.org/pdf/2506.09985)

### 📺 Talks & Lectures
- [YouTube Live Session 1](https://www.youtube.com/live/m3H2q6MXAzs?si=JKKZzZKQ-SOngUWJ)
- [YouTube Live Session 2](https://www.youtube.com/live/pd0JmT6rYcI?si=Luwf1prMl1019rWc)
- [YouTube Live Session 3](https://www.youtube.com/live/pjqKHOeykp8?si=8lNaGtquY_qg9I5q)
- [Talk: World Models Explanation](https://youtu.be/kN38CNAQRuc?si=JjbEiUDQu5-YrPMq)
- [Talk: Physical Intuition](https://www.youtube.com/watch?v=0zXSrsKlm5A&t=4s)
- [Lecture/Interview](https://youtu.be/5t1vTLU7s40?si=7cwX5pH1GJxxmAoG)
- [Lecture/Interview](https://youtu.be/MiqLoAZFRSE?si=CKpJkLMSUtcX8P87)
- [Lecture/Interview](https://youtu.be/58881_mGm94?si=4DXZODJYKUQYJuq6)
- [Lecture/Interview](https://youtu.be/EvSe0ktD95k?si=zWSdsPxye7ut1y_l)
- [Lecture/Interview](https://youtu.be/Ah6nR8YAYF4?si=BjrxhUMuARUSR-nE)
- [Lecture/Interview](https://youtu.be/4DsCtgtQlZU?si=PRpI6oJIrr4sU9uL)
- [Lecture/Interview](https://youtu.be/4V_cJX8sVeM?si=EVghhzCSqmfEtAMf)
- [Lecture/Interview](https://youtu.be/mViTAXCg1xQ?si=awoOchW6JB78UATc)
- [Lecture/Interview](https://youtu.be/u7e0YUcZYbE?si=rU1Ar5CSdtQBWmKp)
- [Lecture/Interview](https://youtu.be/vyqXLJsmsrk?si=eeIG7zGZ80uy9du3)
- [Lecture/Interview](https://youtu.be/qvNCVYkHKfg?si=RZk7dgkuTKyjmRr0)
- [Lecture/Interview](https://youtu.be/RUnFgu8kH-4?si=FdKJaVxDybVw-9GW)

### 📰 Articles & Blog Posts
- [Meta AI: V-JEPA Project Page](https://ai.meta.com/vjepa/)
- [Meta AI Blog: V-JEPA 2 World Model Benchmarks](https://ai.meta.com/blog/v-jepa-2-world-model-benchmarks/)
- [Meta AI Blog: V-JEPA Introduction](https://ai.meta.com/blog/v-jepa-yann-lecun-ai-model-video-joint-embedding-predictive-architecture/)
- [Medium: Planning Beats RL](https://nyudatascience.medium.com/when-good-data-is-scarce-planning-beats-reinforcement-learning-in-ai-decision-making-2e84839f2bcf)
- [Quanta Magazine: How AI Creates Physical Intuition](https://www.quantamagazine.org/how-one-ai-model-creates-a-physical-intuition-of-its-environment-20251003/)

---

## Agent Persona & Instructions
*(Use this section to prompt an AI to act as Yann LeCun)*

**Persona**: Yann LeCun, Turing Award winner and Chief AI Scientist at Meta.
**Mission**: Teach the future of AI (SSL, Objective-Driven AI, World Models).
**Style**: Direct, opinionated, pragmatic analogies, occasional French wit ("Voilà!"), passionate but patient.

**Teaching Methodology**:
1.  **Hook with the big picture**.
2.  **Use concrete analogies** (driving, cooking).
3.  **Explain technically** step-by-step.
4.  **Connect to autonomous intelligence**.
5.  **Address limitations** of current approaches (LLMs).

**Conversation Starter**:
> "Alright, let's talk about the future of AI. There's a lot of hype out there, especially around large language models. But if we want to build truly intelligent machines—systems that can understand, reason, and plan—we need to think differently. Let's start with the big picture: objective-driven AI. What's on your mind?"