# GEN AI TRAINING – FOUNDATIONS

## 1️⃣ Human Intelligence
Human intelligence is the ability to:
- Learn from experience
- Reason and make decisions
- Solve problems
- Understand abstract ideas
- Adapt to new situations

It includes cognitive functions such as:
- Memory
- Perception
- Language
- Planning
- Creativity

There is no single agreed definition. IQ measures only certain aspects. Other theories include multiple intelligences like emotional, spatial, and logical intelligence.

---

## 2️⃣ Artificial Intelligence (AI)

Artificial Intelligence refers to machines designed to perform tasks that normally require human intelligence, such as:
- Learning
- Reasoning
- Problem solving
- Pattern recognition
- Decision making

AI systems do **not** have:
- Emotions  
- Consciousness  
- Self-awareness  

They simulate intelligence using algorithms and data.

---

## 3️⃣ Generative AI (GenAI)

Generative AI is a **subfield of AI** focused on **creating new content** rather than just analyzing data.

### Examples of Generated Content:
- Text (ChatGPT)
- Images (DALL·E, Midjourney)
- Audio (voice synthesis)
- Video
- Code
- Documents

**Traditional AI** → Classification, prediction, analysis  
**Generative AI** → Creation

---

## 4️⃣ Neural Networks (NN)

A Neural Network is a computational system inspired by the human brain.

It consists of **neurons (nodes)** connected in layers.

Each neuron:
1. Receives input  
2. Performs a mathematical calculation  
3. Passes the result forward  

Example: House Price Prediction
Inputs:
- Area  
- Bedrooms  
- Location  

The network learns patterns like:
> “Larger houses in better locations usually cost more.”

---

## 5️⃣ Deep Learning (DL)

Deep Learning is a **subset of Neural Networks** that uses **many layers**.

Why we need deep learning:
- Images contain millions of pixels
- Speech contains wave patterns
- Language contains context and meaning

A shallow network struggles with this complexity.

How layers work:
| Layer Type    | Learns |
|---------------|--------|
| Early layers  | Simple patterns (edges, sounds) |
| Middle layers | Shapes, structures |
| Deep layers   | Meaning, objects, concepts |

---

## 6️⃣ Relationship Between Concepts

Another way to think:

**Neuron → Neural Network → Deep Learning → Machine Learning → Artificial Intelligence**

---

## 7️⃣ Tokens

A token is a small unit of text that a model processes.

Examples:
- Words
- Sub-words
- Characters (in some models)

Models convert tokens into numbers before processing.

### Important:
Different LLMs use different tokenization methods.  
Token counts are **approximate**, not exact.

---

## 8️⃣ Transformations (in Transformers)

A transformation changes data from one form into another.

Example:
Sentence → Tokens → Numbers → Internal representations → Output text

Transformations allow models to:
1. Generate human-like language  
2. Build internal meaning representations  

The output text is only the surface — the real intelligence is in these internal transformations.

---

## 9️⃣ Context Window (Token Limit)

Each LLM has a **maximum token limit** (context window).

Example: 32K tokens

| Prompt | Output | Result |
|--------|--------|--------|
| 20K    | 12K    |  Works |
| 30K    | 5K     |  Exceeds limit |

Prompt + Response must stay within the limit.

---

## 🔟 Parallelism

Parallelism = Doing many operations at the same time.

### Everyday Example
Sequential:
- Cook rice
- Then cut vegetables
- Then boil water

Parallel:
- Rice cooking
- Vegetables cutting
- Water boiling

Faster because tasks run simultaneously.

---

## Parallelism in AI

### Neural Networks
- Many neurons compute at once  
- Matrix multiplications run in parallel  

### Deep Learning Training
- Millions of parameters updated simultaneously  
- GPUs process tensors in parallel  

### Transformers vs RNNs

| Model | Processing Style | Speed |
|------|------------------|-------|
| RNN/LSTM | One word at a time | Slow |
| Transformer | All tokens at once | Fast |

This parallelism is why large models like ChatGPT are possible.

---

## 1️⃣1️⃣ Attention

Attention helps the model decide:
> “Which words matter most right now?”

It allows models to focus on relevant tokens instead of treating all words equally.

---

## 1️⃣2️⃣ Embeddings

An embedding converts data into numbers where **similar meaning → similar numbers**.

Used for:
- Text
- Images
- Audio
- Video

Embeddings are the bridge between:
**Human meaning → Machine numbers**

### Typical Dimensions
- 384
- 512
- 768
- 1024
- 1536
- 2048

Too many dimensions cause:
- High storage cost
- Slower search
- Noise (curse of dimensionality)

---

## Summary Connection

| Concept | Role |
|--------|------|
| Tokens | Units being processed |
| Transformations | How data is changed |
| Attention | What the model focuses on |
| Parallelism | How computation is sped up |
| Embeddings | How meaning becomes numbers |


