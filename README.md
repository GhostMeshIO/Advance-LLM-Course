### **Advanced Prompting Techniques: Quick Reference Sheet**

**Core Philosophy:** Move from giving commands to designing **thought processes** for the AI.

| Technique | Best For | Core Action | Quick Template |
| :--- | :--- | :--- | :--- |
| **1. Meta-Cognitive** | Debugging reasoning, teaching thinking. | Ask AI to reflect on its **process & assumptions**. | *"Before answering, outline your reasoning approach and identify potential biases."* |
| **2. Recursive Self-Reference** | Iterative refinement, idea evolution. | Use the **output as input** for the next prompt. | *"Generate X. Critique it. Now, rewrite it based on that critique."* |
| **3. Constraint-Based** | Boosting creativity, precision, analogies. | **Limit** format, length, perspective, or vocabulary. | *"Explain [TOPIC] in a [FORMAT] for [AUDIENCE] without using the words [X, Y, Z]."* |
| **4. Multi-Layer Context** | Professional, nuanced, audience-aware outputs. | **Stack** role, domain, goal, audience, constraint, format. | *"As a [ROLE] with expertise in [DOMAIN], create [GOAL] for [AUDIENCE] within [CONSTRAINT] in [FORMAT]."* |
| **5. Perspective Shifting** | Critical thinking, comprehensive analysis, debate. | Examine the topic through **multiple, contrasting lenses**. | *"Analyze [TOPIC] from the perspectives of: 1) [STAKEHOLDER A], 2) [STAKEHOLDER B], 3) [STAKEHOLDER C]."* |
| **6. Iterative Refinement** | Quality control, achieving specific standards. | **Loop**: Generate → Evaluate (vs. criteria) → Improve. | *"Draft [OUTPUT]. Score it 1-10 on [CRITERIA]. Rewrite elements scoring below 8."* |
| **7. Simulation Frameworks** | Exploring dynamics, scenario planning, systems thinking. | Model a **system** with rules, actors, and interactions. | *"Simulate a [SCENARIO] with [ACTORS] who have [MOTIVATIONS]. Show 3 rounds of interaction."* |
| **8. Chain-of-Thought (Advanced)** | Complex problem-solving, transparent logic. | Force **step-by-step reasoning** with verification or branching. | *"Solve this step-by-step. After each step, verify its correctness. Explore alternative steps if stuck."* |

---

### **Ethical Imperatives (To Teach & Practice)**
*   **Do:** Be transparent, verify facts, use for beneficial creation.
*   **Don't:** Circumvent safety filters, generate misinformation, violate privacy, or use for academic dishonesty.

### **Best Practices Checklist**
- [ ] **Start Simple, Then Scale:** Nail the basic prompt first.
- [ ] **Define Success:** Know what a good output looks like *before* you prompt.
- [ ] **Iterate and Document:** Treat prompting as an experiment. Keep notes.
- [ ] **Match Technique to Task:** Use the table above to select the right tool.
- [ ] **Verify Critical Outputs:** Never blindly trust AI-generated facts or analysis.

### **Next Steps for Using This Guide:**
1.  **Teach It:** Use each section as a 15-minute mini-lesson with hands-on prompting exercises.
2.  **Prompt Journal:** Pick one technique per day. Apply it to a real task and record the result.
3.  **Create Templates:** Build reusable prompt templates from the examples for your specific work (e.g., "Blog Post Ideation with Perspective Shifting").
4.  **Workshop Design:** Structure a session: Intro (1-2), Core Techniques (3-8), Ethics (9), and Practice Lab (10).

This guide provides the **theory**. The **mastery** comes from structured practice and ethical application.

## Top 24 Novel & Useful Prompts for Development

Based on the advanced techniques in your guide, here are 24 practical prompts specifically crafted for software development, product development, and technical work:

### **Meta-Cognitive Prompts**
1. **Architecture Reflection:** "Before proposing a solution architecture, first explain: 1) What assumptions are you making about scalability needs? 2) What alternative patterns did you consider and reject? 3) What specific trade-offs does your chosen approach make?"
   
2. **Code Review Self-Audit:** "Review this code. Before listing issues, document: 1) Your code review checklist 2) Which standards you're prioritizing (security vs. readability vs. performance) 3) What biases might influence your assessment (like familiarity with certain patterns)."

### **Recursive Self-Reference Prompts**
3. **API Design Evolution:** "Design a REST API endpoint for user management. Then critique your own design for RESTful principles adherence. Then redesign it. Repeat this process twice, each time addressing a different concern: versioning, error handling, documentation."

4. **Prompt Self-Improvement:** "Write a prompt that generates excellent commit messages. Then use that prompt to generate a commit message for a feature. Then write a new prompt that would generate even better commit messages based on what was lacking. Iterate 3 times."

### **Constraint-Based Innovation Prompts**
5. **Minimalist Explanation:** "Explain Kubernetes in exactly 100 words, using only analogies from city planning and transportation systems."

6. **Taboo Architecture:** "Design a microservices communication pattern without using message queues, REST APIs, or gRPC. What alternative communication paradigms could work?"

7. **Extreme Audience Adaptation:** "Explain CI/CD pipelines to a medieval blacksmith. Use only analogies from forging, tool-making, and workshop organization."

### **Multi-Layer Context Building Prompts**
8. **Comprehensive Tech Spec:** "As a Principal Engineer specializing in distributed systems, create a technical specification for a new cache layer, targeting mid-level backend engineers, within the constraints of our existing AWS infrastructure, in the format of a decision document with alternatives analysis."

9. **Stakeholder-Aligned Proposal:** "As a Product Manager for developer tools, draft a proposal for a new debugging feature for: 1) Engineering leadership (focus on ROI and velocity) 2) Frontend developers (focus on usability) 3) DevOps (focus on maintenance burden)."

### **Perspective Shifting Prompts**
10. **Triple Perspective Analysis:** "Analyze implementing TypeScript in a large JavaScript codebase from: 1) A senior engineer focused on long-term maintenance 2) A junior developer worried about learning curve 3) A product manager concerned about delivery timelines."

11. **Temporal Decision Analysis:** "Evaluate choosing React Native for a new mobile app as if it were: 2018 (early adoption), today (mature ecosystem), and 2028 (looking back). What factors change in each timeframe?"

### **Iterative Refinement Loop Prompts**
12. **User Story Refinement:** "Write a user story for a 'forgot password' feature. Score it 1-10 on: INVEST criteria (Independent, Negotiable, Valuable, Estimable, Small, Testable). Rewrite any aspect scoring below 8. Repeat until all criteria score 8+."

13. **API Documentation Loop:** "Generate OpenAPI documentation for a payment endpoint. Evaluate it for: completeness, clarity, and example quality. For each deficiency, rewrite that section. Iterate until you have professional-grade documentation."

### **Simulation Framework Prompts**
14. **Incident Response Simulation:** "Simulate a production outage scenario where database latency spikes by 300%. Model: 1) Monitoring alerts 2) Engineer investigation steps 3) Team communication 4) Mitigation actions. Show 3 escalation levels over 60 minutes."

15. **Architecture Trade-off Simulation:** "Simulate a design review meeting with 4 personas: The Performance-Obsessed Engineer, The Budget-Conscious Manager, The Security Architect, and The UX Advocate. Have them debate between serverless vs. containers for a new service."

### **Chain-of-Thought Variation Prompts**
16. **Tree-of-Thought Debugging:** "I'm getting a race condition in this distributed system. Explore 3 parallel debugging approaches simultaneously: 1) Analyzing logs chronologically 2) Examining resource contention 3) Reviewing synchronization logic. Compare which approach identifies the root cause fastest."

17. **Self-Consistent Code Review:** "Review this Python function for security vulnerabilities. Generate 3 independent analysis chains using: 1) OWASP checklist 2) Peer code review heuristics 3) Automated tool simulation. Do all three converge on the same issues?"

### **Ethical Development Prompts**
18. **Bias Audit Prompt:** "Audit this machine learning dataset for potential biases. First, identify what protected categories might be affected. Then, propose specific statistical tests to detect bias. Finally, suggest mitigation strategies that don't simply remove the sensitive attributes."

19. **Privacy-by-Design:** "Design a feature that collects user analytics while maximizing privacy. Apply privacy principles: data minimization, purpose limitation, storage limitation. Document each design decision's privacy trade-off."

### **Best Practices Synthesis Prompts**
20. **The "Explain Like I'm 5, 25, and 45":** "Explain Docker containers three ways: 1) To a 5-year-old (simple analogy) 2) To a new computer science graduate (technical but foundational) 3) To a seasoned sysadmin (advanced, focusing on implementation details)."

21. **Anti-Pattern Catalog:** "For the microservices pattern I'm about to implement, generate: 1) The ideal implementation 2) The most likely anti-pattern we'll accidentally create 3) Early warning signs we're creating the anti-pattern 4) How to refactor from anti-pattern to ideal."

### **Cross-Technique Hybrid Prompts**
22. **Constraint + Perspective Hybrid:** "Design a feature flag system using only 500 words total, but address three audiences: developers (implementation), product managers (usage), and executives (business value). Allocate words proportionally to importance."

23. **Simulation + Iteration Hybrid:** "Simulate 3 sprint cycles of building an authentication service. Each sprint: 1) Show what gets built 2) What technical debt accumulates 3) How team velocity changes. After 3 sprints, propose refactoring based on accumulated issues."

24. **Meta-Cognitive + Chain-of-Thought:** "Solve this algorithm problem. At each step: 1) Explain your reasoning 2) Note any assumptions 3) Identify alternative approaches considered and rejected. After solving, reflect on whether a different initial approach would have been better."

---

## **How to Use These Prompts:**

1. **Template Adaptation:** Replace the bracketed concepts with your specific technology, problem, or context.
2. **Progressive Difficulty:** Start with single-technique prompts (#5, #8) before advancing to hybrids (#22-24).
3. **Team Exercises:** Use simulation prompts (#14, #15) for team training or architecture workshops.
4. **Documentation:** Apply iterative refinement prompts (#12, #13) to improve existing docs.
5. **Code Review:** Use meta-cognitive prompts (#1, #2) to establish better review practices.

These prompts move beyond basic "write code for X" to develop critical thinking, comprehensive analysis, and higher-quality outputs—exactly what distinguishes senior developers from junior ones.
