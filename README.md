# Ex. No. 3 – Scenario-Based Report Development Using Prompting Techniques  

**Date:** 09.09.2025  
**Register Number:** 212223060224 

---

## Aim
To study and apply different **prompting techniques** for designing an AI-powered chatbot.  
The chatbot should assist customers with:  
- Troubleshooting products  
- Tracking orders  
- Answering general inquiries  

---

## Theory
**Prompting** is the process of guiding AI responses through carefully designed instructions.  
Different prompting strategies influence the **accuracy, tone, and clarity** of chatbot outputs.  

In this experiment, we explore the following prompting techniques:  
1. Direct Instruction Prompts  
2. Contextual Prompting  
3. Persona-Based Prompting  
4. Few-Shot Prompting  
5. Chain-of-Thought Prompting  
6. Instruction with Constraints  
7. Reflective Prompting  

Each method helps the chatbot handle customer queries in a unique way.  

---

## Algorithm
1. Identify common customer queries:  
   - Order status  
   - Technical issues  
   - General help  
2. Select a prompting technique.  
3. Frame a suitable prompt pattern (instruction to the AI).  
4. Test the chatbot’s response for each query.  
5. Record and evaluate responses based on clarity, helpfulness, and tone.  

---

## Examples of Prompting Techniques

### 1. Direct Instruction Prompt  
**Objective:** Provide simple and concise answers.  
**Example Prompt:**  
> “When a customer asks about their order, reply: ‘Your order is being processed and will be delivered by [date].’”  

---

### 2. Contextual Prompting  
**Objective:** Use conversation history for better answers.  
**Example Prompt:**  
> “If the customer said their order hasn’t arrived, reply: ‘I see your order hasn’t arrived yet. Let me check the details and get back to you.’”  

---

### 3. Persona-Based Prompting  
**Objective:** Make the chatbot sound like a friendly human agent.  
**Example Prompt:**  
> “Act like a helpful customer service representative. Say things like: ‘Hey there! I’m here to help. Let’s get this fixed!’”  

---

### 4. Few-Shot Prompting  
**Objective:** Learn from examples.  
**Example Prompt:**  
> Examples:  
> Q: “My phone isn’t charging.” → A: “Try another cable. If not, the port may be faulty.”  
> Q: “The screen flickers.” → A: “This looks like a display issue. Restart and check again.”  
> Now answer: “My app keeps crashing.”  

---

### 5. Chain-of-Thought Prompting  
**Objective:** Solve problems step by step.  
**Example Prompt:**  
> For laptop overheating:  
> - Ask if it’s on a soft surface.  
> - Suggest using a hard surface.  
> - Ask if vents are cleaned.  
> - Recommend restarting.  
> Now solve: “My laptop fan is noisy.”  

---

### 6. Instruction with Constraints  
**Objective:** Respond under set rules (short and simple).  
**Example Prompt:**  
> “Reply in under 50 words. Avoid technical terms. Example: ‘Your order is on the way and will arrive by [date].’”  

---

### 7. Reflective Prompting  
**Objective:** Confirm the query before answering.  
**Example Prompt:**  
> Q: “How do I reset my password?”  
> A: “You’re asking how to reset your password, correct? Here’s how…”  

---

## Observation
- **Direct prompts** → Fast but basic replies.  
- **Contextual & Reflective prompts** → Reduce misunderstandings.  
- **Persona-based prompts** → More engaging and user-friendly.  
- **Few-shot & Chain-of-Thought** → Improve problem-solving ability.  
- **Instruction with Constraints** → Keeps answers short and clear.  

---

## Conclusion
Different prompting strategies provide different strengths:  
- Use **direct prompts** for quick replies.  
- Use **contextual and reflective prompts** to ensure accuracy.  
- Use **persona-based prompts** for a friendly tone.  
- Use **few-shot and chain-of-thought prompts** for better troubleshooting.  
- Use **constraints** when short and simple responses are needed.  

This experiment shows that combining multiple prompting strategies can create a more effective and user-friendly chatbot.  
