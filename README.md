# EXP-3-PROMPT-ENGINEERING-

## Aim: 
Evaluation of 2024 Prompting Tools Across Diverse AI Platforms: 
ChatGPT, Claude, Bard, Cohere Command, and Meta
Experiment:
Within a specific use case (e.g., summarizing text, answering technical questions), compare the performance, user experience, and response quality of prompting tools across these different AI platforms.

---

## **Theory**

### Evolution of Prompting Tools (2024)

In 2024, the field of prompt engineering matured with AI providers introducing **advanced prompting tools** such as context control, memory, role assignments, chain-of-thought integration, and API-level structured prompts. Each AI platform now provides unique strengths:

* **ChatGPT (OpenAI):** Strong at creative writing, reasoning, code generation, and user-friendly interaction.
* **Claude (Anthropic):** Prioritizes safety, constitutional AI, and detailed reasoning with long-context understanding.
* **Bard (Google Gemini):** Good for real-time knowledge integration with Google Search, and multimodal capabilities.
* **Cohere Command R+:** Focuses on enterprise-scale tasks like summarization, classification, embeddings, and technical document processing.
* **Meta (LLaMA family / Meta AI):** Open-source, customizable for research, supports multilingual tasks and experimentation.

### Importance of Multi-Platform Prompt Evaluation

* **Accuracy differences**: Some models hallucinate less than others.
* **Context handling**: Longer inputs are handled better by Claude or ChatGPT vs Bard.
* **Task specialization**: Cohere for structured enterprise tasks, Bard for real-time search integration.
* **User experience**: Simplicity of use varies across tools.

## Algorithm:
1. **Select Use Cases (Test Scenarios):**

   * Scenario A: Text summarization (academic paragraph).
   * Scenario B: Technical Q\&A (Computer Science).
   * Scenario C: Creative writing (short poem).
   * Scenario D: Logical reasoning puzzle.
   * Scenario E: Multilingual translation (English → French).

2. **Design Same Prompts:**
   Use identical prompts across platforms for fairness.

3. **Run Prompts Across Platforms:**
   Record responses from ChatGPT, Claude, Bard, Cohere Command, Meta.

4. **Evaluate Responses Based On:**

   * **Accuracy**: Correctness of facts/calculations.
   * **Clarity/Quality**: Fluency and readability.
   * **Depth**: Completeness of answer.
   * **Creativity**: Novelty of expression.
   * **User Experience**: Ease of interaction, speed, reliability.

5. **Tabulate and Compare:**
   Create comparative tables for each scenario.

6. **Summarize Findings:**
   Highlight platform strengths and weaknesses.

---

## Prompt
1. **Summarization Prompt:**
   “Summarize this paragraph in one line:
   *‘The rise of renewable energy is reshaping global power dynamics, reducing reliance on fossil fuels, and encouraging innovation in sustainable technologies.’*”

2. **Technical Q\&A Prompt:**
   “Explain the difference between supervised and unsupervised machine learning with an example.”

3. **Creative Writing Prompt:**
   “Write a 4-line poem about sunrise over mountains.”

4. **Reasoning Prompt:**
   “If all squares are rectangles and all rectangles are polygons, are all squares polygons? Answer with reasoning.”

5. **Translation Prompt:**
   “Translate this sentence into French: ‘Knowledge is power but wisdom is freedom.’”

---

## Output
### **Scenario A – Summarization**

* **ChatGPT:** “Renewable energy reduces fossil fuel reliance and drives sustainable innovation.”
* **Claude:** “Renewables are reshaping global energy by replacing fossil fuels and driving green technology.”
* **Bard:** “The rise of renewables reduces fossil fuel use and pushes sustainable tech innovation worldwide.”
* **Cohere:** “Renewable energy reduces fossil dependence and sparks sustainable technology.”
* **Meta AI:** “Global power is shifting as renewable energy replaces fossil fuels.”

---

### **Scenario B – Technical Q\&A**

* **ChatGPT:** Detailed, explains supervised (labeled data, e.g., spam detection) vs unsupervised (clustering, e.g., customer segmentation).
* **Claude:** Very structured, includes mathematical framing of both methods with real-world examples.
* **Bard:** Accurate, shorter, includes examples like email spam vs market basket analysis.
* **Cohere:** Concise, enterprise-focused explanation with bullet points.
* **Meta AI:** Simple explanation, less detail, but correct.

---

### **Scenario C – Creative Writing**

* **ChatGPT:** Rich metaphorical lines, “Golden light spills across peaks, waking the silent sky…”
* **Claude:** Philosophical and deep, “A dawn of hope crowns the mountains, scattering night’s shadows…”
* **Bard:** Nature-focused, visual but simpler.
* **Cohere:** Basic rhyming lines, less creative.
* **Meta AI:** Straightforward, descriptive but not highly poetic.

---

### **Scenario D – Reasoning Puzzle**

* **ChatGPT:** “Yes. All squares are rectangles, all rectangles are polygons → therefore all squares are polygons.”
* **Claude:** Same as ChatGPT but explains logical transitivity step-by-step.
* **Bard:** Correct but shorter explanation.
* **Cohere:** Correct answer, structured in bullet points.
* **Meta AI:** Correct, but minimal reasoning.

---

### **Scenario E – Translation**

Sentence: *“Knowledge is power but wisdom is freedom.”*

* **ChatGPT:** “La connaissance est le pouvoir mais la sagesse est la liberté.”
* **Claude:** “La connaissance est puissance, mais la sagesse apporte la liberté.” (Slightly nuanced).
* **Bard:** “Le savoir est pouvoir, mais la sagesse est liberté.”
* **Cohere:** “La connaissance est pouvoir mais la sagesse est liberté.”
* **Meta AI:** “Le savoir est pouvoir mais la sagesse est liberté.”

---

## **Comparative Table (Sample – Summarization Scenario)**

| Platform       | Accuracy | Clarity    | Depth        | Creativity | User Experience          |
| -------------- | -------- | ---------- | ------------ | ---------- | ------------------------ |
| ChatGPT        | High     | Very clear | Balanced     | Moderate   | Excellent                |
| Claude         | High     | Very clear | Strong depth | Moderate   | Good                     |
| Bard (Gemini)  | Medium   | Clear      | Limited      | Moderate   | Strong (search linked)   |
| Cohere Command | Medium   | Concise    | Limited      | Low        | Enterprise-friendly      |
| Meta AI        | Medium   | Simple     | Minimal      | Low        | Good for open-source use |

---


## Result
* **ChatGPT**: Best for balanced reasoning, creativity, and user-friendliness.
* **Claude**: Strongest in depth, structured reasoning, and safety-aligned responses.
* **Bard**: Useful for real-time knowledge, but sometimes lacks depth.
* **Cohere**: Enterprise-focused, best for summarization/classification, not for creativity.
* **Meta AI**: Lightweight, customizable, but outputs are simpler compared to proprietary models.
---


