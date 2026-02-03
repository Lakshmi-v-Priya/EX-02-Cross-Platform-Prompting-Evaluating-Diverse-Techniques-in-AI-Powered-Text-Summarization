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
