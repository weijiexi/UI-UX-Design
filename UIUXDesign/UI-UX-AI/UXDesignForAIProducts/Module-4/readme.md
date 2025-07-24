# MODULE 4: User Trust and Explainability in AI Systems

### Key Concepts:
- **Algorithm Aversion**: People tend to lose trust in AI after observing errors, often more so than they would with human errors.
- **Complementarity**: A human-AI collaboration that yields better results than either working alone.
- **LIME (Local Interpretable Model-agnostic Explanations)**: Explains individual decisions by showing what input changes would alter the output.
- **Mechanistic Interpretability**: Explains AI behavior by analyzing neuron activations to identify meaningful patterns.
- **Overreliance**: Excessive dependence on AI outputs, often without adequate scrutiny.

### Trust in AI Systems
- Human-AI interaction aims to boost results through **intelligence augmentation**.
- Designers must define when AI should automate (e.g. airbags), verify (e.g. email edits), or present options (e.g. design galleries).
- **Trust is enhanced when AI systems project competence aligned with user expectations**.

### Achieving Complementarity
- AI helps novices more than experts.
- Complementarity is most effective in ideation and creative domains.
- Misuse of AI in complex tasks may reduce performance due to misleading suggestions.

### Mitigating Aversion and Overreliance
1. **Provide Multiple Suggestions**: As in design galleries (e.g. DALL-E), helps users validate AI outputs.
2. **Raise the Stakes**: Users scrutinize AI more when consequences of mistakes are higher.
3. **Explainable AI (XAI)**: Integrate explanations into interfaces to make AI reasoning visible.

### Explainability Techniques
#### 1. **Natural Language**
- Explains suggestions using **commonsense reasoning**.

#### 2. **Example-Based**
- Uses adversarial/counterfactual examples to show how slight changes impact results.

#### 3. **Feature Attribution**
- Shows which input features had the greatest influence (e.g. via **Shapley values**).

#### 4. **Attention-Based**
- Visualizes how attention is distributed in the model (e.g. transformer attention heads).

#### 5. **Simplified Models**
- Restrict complexity to achieve higher intelligibility. Tradeoff: reduced performance.

#### 6. **LIME**
- Builds a local linear model to approximate AI decisions.
- Tells users what input tweaks would change the outcome.

#### 7. **Mechanistic Interpretability**
- Tracks neuron activations to decode learned patterns.
- E.g., Amplifying the "Golden Gate Bridge" feature to see the model act obsessed with it.

### The Intelligibility Dilemma
- **Precise Explanation**: Accurate but complex; hard for most users to understand.
- **Simplified Explanation**: Accessible but less faithful to the model’s internal logic.
- Ongoing challenge: balancing fidelity vs. intelligibility for different audiences.

### Summary
Module 4 emphasizes how brittle trust in AI can be, how explainability supports trust calibration, and the role of complementary AI-human collaboration. Explainability strategies like LIME, mechanistic interpretability, and natural language outputs help users validate and understand AI behavior—provided the right balance between clarity and accuracy is maintained.

