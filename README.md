# EX-02: Cross Platform Prompting – Evaluating Diverse Techniques in AI Powered Text Summarization

**Reg No: 212223220049**

---

## AIM

To evaluate and compare the effectiveness of different prompting techniques such as Zero-shot, Few-shot, Chain-of-Thought, and Role-based across multiple AI platforms like ChatGPT, Gemini, Claude, and Copilot for the task of text summarization.

---

## SCENARIO

You are part of a content curation team for an educational platform that provides quick summaries of research papers for undergraduate students.  
Your task is to summarize a 500-word technical article titled **“The Basics of Blockchain Technology”** using multiple AI platforms and prompting strategies.

The goal is to determine which combination of platform and prompting method gives the best result based on:

- Accuracy  
- Coherence  
- Simplicity  
- Speed  
- User Experience  

---

## ALGORITHM / PROCEDURE

### 1. Article Selection

A technical article of approximately 500 words on Blockchain Technology was selected. The article covered:

- Definition of blockchain  
- Structure of blocks and cryptographic hashes  
- Consensus mechanisms  
- Applications in real-world domains  
- Challenges and limitations  

Article Selection
**Input Text (approx. 500 words):**
> *Blockchain technology is fundamentally a distributed, decentralized ledger that records transactions across a network of computers. Unlike traditional databases managed by a central authority (like a bank or government), a blockchain allows multiple parties to share a single, immutable history of information. The technology was first introduced in 2008 by Satoshi Nakamoto as the underlying infrastructure for Bitcoin, solving the "double-spending" problem without requiring a trusted intermediary.*
>
> *At its core, a blockchain consists of a chain of digital "blocks" that contain data. Each block holds a specific set of information: valid transaction records, a timestamp, and a cryptographic hash of the previous block. This hash acts like a digital fingerprint. If anyone attempts to alter the data in a block, the hash changes completely. Since the next block in the chain carries the previous block’s hash, any tampering breaks the chain, making the corruption immediately evident to the entire network.*
>
> *The security of the blockchain relies on a consensus mechanism, such as "Proof of Work" (used by Bitcoin) or "Proof of Stake." In Proof of Work, powerful computers (miners) compete to solve complex mathematical puzzles to validate transactions and create new blocks. This process requires significant energy but ensures that rewriting the ledger is computationally infeasible for any single attacker. Once a block is added, it cannot be changed, ensuring data immutability.*
>
> *Beyond cryptocurrencies, blockchain has potential applications in various sectors. In supply chain management, it provides end-to-end transparency, allowing consumers to trace the origin of products. In healthcare, it can securely store patient records that are accessible only to authorized providers. Smart contracts—self-executing contracts with the terms directly written into code—automate processes on platforms like Ethereum, reducing the need for lawyers or notaries.*
>
> *However, the technology faces challenges. Scalability is a major issue; public blockchains can be slow and expensive to use during peak times. Additionally, the regulatory environment remains uncertain in many jurisdictions. Despite these hurdles, blockchain represents a paradigm shift in how digital trust is established and maintained.*
---

### 2. Prompt Design

The following prompting strategies were used:

#### Zero-shot Prompt  
"Summarize the following text in simple terms for undergraduate students."

#### Few-shot Prompt  
Two example summaries on Cloud Computing and AI Ethics were provided before asking for the blockchain summary.

#### Chain-of-Thought Prompt  
"First identify the definition of blockchain, then list key components, next describe applications and challenges, and finally generate a coherent summary."

#### Role-based Prompt  
"You are a Computer Science professor explaining blockchain to freshman students using simple analogies."

---

### 3. Execution on Platforms

| Platform + Strategy | Observation |
|--------------------|-------------|
| ChatGPT – Zero-shot | Fast and simple summary but missed detailed explanation of hashes |
| Gemini – Few-shot | Well structured and followed example pattern |
| Claude – Chain-of-Thought | Highly logical flow with technical depth |
| Copilot – Role-based | Very engaging but slightly oversimplified |

---

## EVALUATION

**Rating Scale: 1 (Poor) – 5 (Excellent)**

| Platform | Strategy | Accuracy | Coherence | Simplicity | Speed | User Experience | Average |
|---------|----------|----------|-----------|------------|-------|-----------------|---------|
| ChatGPT | Zero-shot | 4 | 5 | 5 | 5 | 5 | 4.8 |
| Gemini | Few-shot | 5 | 4 | 4 | 4 | 4 | 4.2 |
| Claude | Chain-of-Thought | 5 | 5 | 4 | 3 | 4 | 4.2 |
| Copilot | Role-based | 3 | 5 | 5 | 4 | 5 | 4.4 |

---

## COMPARISON AND FINDINGS

- **Highest Accuracy:** Claude (Chain-of-Thought) and Gemini (Few-shot)  
- **Fastest Response:** ChatGPT (Zero-shot)  
- **Most Engaging:** Copilot (Role-based)  
- **Best Educational Balance:** Claude with Chain-of-Thought  

---

## CONCLUSION

The experiment proved that prompting strategies strongly influence AI summarization quality.

- Chain-of-Thought prompting on Claude produced the most accurate and well-structured summaries.  
- ChatGPT zero-shot was the fastest but lacked some technical depth.  
- Gemini few-shot gave good structured output but required more setup time.  
- Copilot role-based was highly engaging but reduced technical precision.

Therefore, **Claude with Chain-of-Thought prompting** was found to be the most effective approach for educational summarization.

---

## RESULT

The cross-platform prompting experiment was successfully performed.  
Different prompting techniques were tested on multiple AI tools and their outputs were analyzed based on accuracy, coherence, simplicity, speed, and user experience.  
The study confirmed that structured prompting significantly improves AI-generated text summarization.

---
