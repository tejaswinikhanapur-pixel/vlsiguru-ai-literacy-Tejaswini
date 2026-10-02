Yes. Below is a **newly worded version** of the Week 01 assignment. It keeps the same **Q1–Q10 and A-E-V-R structure** from your provided assessment, but uses different wording and examples. 

# Week 01 – The AI Landscape

## Q1 – AI, ML, DL, GenAI and AI Agents

### A – Answer

**Artificial Intelligence (AI):** AI is the broad area of computing that aims to create systems capable of performing tasks that normally require human-like intelligence.

**Machine Learning (ML):** ML is a part of AI in which systems learn patterns from data and use those patterns to make predictions or decisions.

**Deep Learning (DL):** DL is a type of machine learning that uses neural networks with multiple layers to learn complicated patterns from data.

**Generative AI (GenAI):** Generative AI creates new content such as text, programs, images, audio, or other data based on patterns learned during training.

**AI Agent:** An AI agent is a system that can use an AI model together with tools, memory, and a sequence of actions to accomplish a particular objective.

### Concept Relationship

```text
Artificial Intelligence
        |
        └── Machine Learning
                |
                └── Deep Learning
                        |
                        └── Generative AI

AI Agent
   |
   └── Uses AI models + Tools + Memory + Actions
```

### Examples

1. **AI:** A computer system that plays chess.
2. **ML:** A spam detector that learns from previous emails.
3. **DL:** A neural-network-based image recognition system.
4. **GenAI:** ChatGPT generating an explanation from a prompt.
5. **AI Agent:** A system that searches information, uses tools, and completes a multi-step task.

### E – Evidence

The definitions were compared with standard AI and machine-learning educational resources.

### V – Verification

The differences between AI, ML, DL, GenAI, and agents were checked against technical learning resources and course material.

### R – Reflection

I learned that these terms should not be used interchangeably. AI is the larger field, while ML and DL describe approaches for building intelligent systems. Generative AI focuses on creating content, whereas an agent is a complete system capable of performing actions toward a goal.

---

# Q2 – Is Everything Intelligent Actually AI?

### A – Answer

| Example                         | Type                 | Explanation                                          |
| ------------------------------- | -------------------- | ---------------------------------------------------- |
| Calculator performing `25 × 16` | Traditional software | Uses a fixed mathematical operation.                 |
| Temperature alarm above 80°C    | Rule-based system    | Follows a predefined condition.                      |
| Spam email detector             | ML-based system      | Uses patterns learned from previous data.            |
| AI summarization tool           | Generative AI        | Generates a shorter version of provided information. |
| Navigation time prediction      | ML-based system      | Uses data to estimate travel time.                   |

Traditional software normally follows instructions explicitly written by programmers. Machine-learning systems instead learn useful patterns from examples or datasets.

### E – Evidence

The classification was based on whether each system uses fixed rules or learned patterns.

### V – Verification

The examples were compared with standard definitions of rule-based computing and machine learning.

### R – Reflection

I learned that an application does not become AI simply because it produces a useful or intelligent-looking result. The method used internally is important.

---

# Q3 – What Happens When You Ask an LLM a Question?

### A – Answer

When a user sends a question to an LLM, the process can be understood as follows:

1. **Tokenization** – The input is divided into tokens.
2. **Context creation** – The tokens are placed into the available context together with relevant instructions.
3. **Neural network processing** – The model processes the information using its learned parameters.
4. **Probability calculation** – The model estimates possible next tokens.
5. **Token selection** – One token is selected according to the generation process.
6. **Repeated generation** – The process continues until the response is complete.

```text
User Prompt
     ↓
Tokenization
     ↓
Context
     ↓
Model Processing
     ↓
Next-token probabilities
     ↓
Token Selection
     ↓
Generated Response
```

Training and inference are different. Training develops the model's parameters using large datasets, while inference uses the trained model to generate an answer.

### E – Evidence

The explanation follows the basic operation of transformer-based language models.

### V – Verification

The process was compared with technical explanations of transformer and language-model inference.

### R – Reflection

I learned that an LLM does not simply search a stored answer. It generates a response based on learned patterns and the information available in its context. Therefore, a fluent answer can still contain incorrect information.

---

# Q4 – Can AI Sound Confident and Still Be Wrong?

### A – Answer

Yes. An AI system can produce an answer that sounds professional even when some information is incorrect.

For example, I compared AI answers for:

**Question:** What is the speed of light in vacuum?

The approximate answer is:

**299,792,458 metres per second**, or approximately **186,282 miles per second**.

The important lesson is that the confidence or quality of wording does not prove that an answer is factually correct.

### E – Evidence

The numerical value can be checked against established physical constants.

### V – Verification

The result was compared with a reliable reference for physical constants.

### R – Reflection

This exercise showed me that I should verify important information instead of trusting an answer only because it sounds confident.

---

# Q5 – AI Assistant vs Search Engine vs Authoritative Source

### A – Answer

| Feature      | AI Assistant                       | Search Engine                  | Authoritative Source                       |
| ------------ | ---------------------------------- | ------------------------------ | ------------------------------------------ |
| Explanation  | Usually easy to understand         | Depends on the result          | Usually technical and precise              |
| Speed        | Fast                               | Fast for finding sources       | Can take more time to read                 |
| Traceability | May require checking citations     | Provides links                 | Usually has formal references              |
| Risk         | Can generate incorrect information | Search results vary in quality | Generally intended as the formal reference |
| Best use     | Learning and explanation           | Finding information            | Final technical verification               |

AI can be useful for understanding a difficult concept quickly. Search engines are useful for locating websites and documents. Authoritative documentation should be consulted when exact technical information is important.

### E – Evidence

The three approaches were compared using technical information-search tasks.

### V – Verification

Important information from AI responses was checked against source documentation.

### R – Reflection

I learned that these tools have different purposes. AI can help me understand a topic, but I should use reliable documentation when making an important technical decision.

---

# Q6 – What Is an AI Agent?

### A – Answer

An **LLM** is the language model that generates and processes text.

An **LLM application** is software that provides an interface around the model.

A **RAG system** retrieves external information and provides it to the model as additional context.

A **tool-using assistant** can call functions such as calculators, databases, or search systems.

An **AI agent** combines an AI model with tools and an execution process to work toward a goal.

```text
User Goal
    ↓
AI Agent
    ↓
AI Model
    ↓
Decision / Planning
    ↓
Tool
    ↓
Tool Result
    ↓
Further Action
    ↓
Final Result
```

### Example

A travel-planning agent could:

1. Receive the user's travel requirements.
2. Search available options.
3. Calculate costs.
4. Compare the results with the budget.
5. Modify the plan if necessary.
6. Present the final itinerary.

### E – Evidence

The explanation follows common architectures used in AI-agent systems.

### V – Verification

The difference between an LLM, an application, a RAG system, and an agent was reviewed using AI engineering concepts.

### R – Reflection

The main difference I learned is that an LLM mainly generates information, while an agent can use that model as part of a larger workflow involving tools and actions.

---

# Q7 – Where Should Humans Make the Final Decision?

### A – Answer

| Situation                | Possible AI Problem               | Human Verification               |
| ------------------------ | --------------------------------- | -------------------------------- |
| Safety-critical software | Undetected software errors        | Engineering review and testing   |
| Medical information      | Incorrect recommendation          | Qualified medical review         |
| Legal documents          | Incorrect interpretation          | Legal professional review        |
| Financial decisions      | Incorrect risk assessment         | Financial analysis and approval  |
| Hiring decisions         | Possible unfair or biased results | Human review and fairness checks |

AI can assist with analysis, but important decisions should have suitable human review when incorrect results could cause significant harm.

### E – Evidence

AI systems can produce incorrect outputs, so verification becomes more important in high-impact applications.

### V – Verification

The principle was compared with responsible-AI and risk-management guidance.

### R – Reflection

I learned that using AI does not remove human responsibility. A suitable verification step should exist before important AI-assisted decisions are finalized.

---

# Q8 – Finding AI Around Me

### A – Answer

| Application                 | AI Used?   | Main Function          | Possible Simpler Method                 |
| --------------------------- | ---------- | ---------------------- | --------------------------------------- |
| Video recommendations       | Yes        | Recommendation         | Fixed popularity list                   |
| Smartphone face recognition | Yes        | Recognition            | Traditional image-processing methods    |
| Basic thermostat            | Usually no | Threshold control      | Rule-based logic                        |
| Voice assistant             | Yes        | Speech recognition     | Fixed keyword detection in simple cases |
| Fraud detection             | Often yes  | Anomaly/classification | Fixed transaction rules                 |

### E – Evidence

The classification depends on the actual implementation of each system.

### V – Verification

Product documentation and technical descriptions can be used to determine whether machine-learning components are involved.

### R – Reflection

I learned that the word "AI" should not automatically be accepted as proof that a system uses machine learning. The underlying implementation needs to be considered.

---

# Q9 – Prediction, Classification and Generation

### A – Answer

1. **Estimating the price of a house** → Prediction
2. **Determining whether an image contains a cat** → Classification
3. **Creating an email from instructions** → Generation
4. **Estimating whether a customer may leave a service** → Prediction / Classification
5. **Creating a short summary of a paper** → Generation
6. **Determining whether a transaction is fraudulent** → Classification
7. **Creating an image from a text prompt** → Generation
8. **Estimating the next token in a sentence** → Prediction

### Difference

**Prediction:** Estimates an unknown value or outcome.

**Classification:** Assigns an input to a category.

**Generation:** Produces new content.

```text
Prediction      → What is likely to happen?
Classification  → Which category does it belong to?
Generation      → What new content can be produced?
```

### E – Evidence

The examples were categorized according to the type of output produced by the system.

### V – Verification

The classifications were compared with standard machine-learning terminology.

### R – Reflection

I learned that different AI applications may appear very different but can still be described using common concepts such as prediction, classification, and generation.

---

# Q10 – Personal AI Verification Protocol

### A – Answer

I will use the following **7-step verification process** when working with AI:

### Step 1 – Define the Problem

Clearly identify what I need from the AI.

### Step 2 – Check the Assumptions

Look for assumptions made by the AI that may not be correct.

### Step 3 – Verify Important Facts

Check important information against reliable documentation or primary sources.

### Step 4 – Test the Output

For code, formulas, or technical designs, actually test the result whenever possible.

### Step 5 – Check Edge Cases

Try unusual, boundary, or unexpected inputs.

### Step 6 – Review and Modify

Decide whether the output should be accepted, changed, or rejected.

### Step 7 – Record the Verification

Maintain a record of important prompts, outputs, sources checked, and modifications.

### Example

If AI provides a Verilog module:

```text
AI generates Verilog
        ↓
Check syntax
        ↓
Compile the code
        ↓
Run testbench
        ↓
Check expected outputs
        ↓
Test corner cases
        ↓
Review final code
```

### E – Evidence

The protocol is based on general software verification and validation practices.

### V – Verification

The steps were compared with standard engineering practices involving testing, review, and documentation.

### R – Reflection

The biggest lesson from Week 01 is that AI should be treated as a useful assistant rather than an unquestionable source of truth. In VLSI work especially, generated code and technical explanations should be checked through simulation, documentation, and human review. 
