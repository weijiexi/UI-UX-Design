 # Module 3: User Control vs. Automation

This module explores the balance between user control and AI automation in interactive systems. It highlights key design patterns and strategies to manage the tension between giving users control versus letting AI automate tasks.

### **Direct Manipulation**
The user retains full control of the system’s actions, offering high precision and transparency.
- Opposes fully automated AI agents.

### **Interface Agents**
AI that proactively completes tasks on the user’s behalf.
- Examples: Email sorters, return processors.
- Risks: Can reduce user control, raise trust issues.

### **Mixed-Initiative Interaction**
A hybrid model where the AI dynamically chooses whether to act or defer to the user based on confidence level.
- High confidence → AI acts
- Medium confidence → AI asks user
- Low confidence → User acts
- Examples: Smartwatch workout detection, Gmail attachment reminder.

### **Accelerators**
AI systems that predict user intent and allow single-click or keystroke acceptance of suggestions.
- Examples: Gmail Smart Compose, GitHub Copilot, Google Maps route suggestions.
- Benefits: Speeds up tasks without removing user control.

### **Verifiers**
AI interfaces that pause user flow only when likely errors are detected.
- Examples: Healthcare AI flagged for doctor review, out-of-stock checks in ecommerce.
- Benefit: Prevents errors without over-automation.

### **Design Galleries**
Interfaces that present multiple AI-generated outputs side-by-side for the user to choose from.
- Examples: DALL·E, resume builders, e-commerce outfit generators.
- Benefits: Encourages user choice, exploration, and creative control.

## 💡 Design Strategy: Agency Plus Automation

According to Ben Shneiderman, designers should aim for systems that combine automation with strong user agency, rather than replacing one with the other. Ideal systems let AI assist but ensure users always feel in control.

## Conclusion

Designers must carefully decide how much control vs. automation is appropriate for their AI product. By using proven patterns—accelerators, galleries, verifiers, and mixed-initiative systems—we can ensure powerful, user-centered AI experiences.
