## Prompt Engineering Audit: A Case Study in AI Response Optimization

This project explores how different prompt styles influence the quality of AI-generated responses in a legal support context. Inspired by the Analyst, AI Operations role at Clio, it simulates a real-world task of evaluating AI tools to improve customer experience.

I tested three common legal support questions using three distinct prompt styles — Direct, Formal, and Friendly — and analyzed the resulting responses based on accuracy, tone, and clarity. The goal was to identify tradeoffs between response readability and legal precision, and to recommend prompt strategies that balance empathy, usefulness, and compliance.

### Scoring Criteria

Each AI response was rated on a scale of 0–5 across three dimensions:

**Clarity**
- 5 – Very clear, concise, and easy to understand for non-experts
- 3 – Understandable with some effort; slightly long-winded or awkward
- 1 – Confusing, dense, or filled with legal jargon

**Accuracy**
- 5 – Fully accurate, complete, and legally precise
- 3 – Mostly accurate but missing key steps or context
- 1 – Vague, incomplete, or partially incorrect

**Tone**
- 5 – Empathetic, professional, and user-friendly
- 3 – Neutral or robotic but acceptable
- 1 – Cold, overly formal, or not appropriate for customer-facing contexts

## Insights


The analysis revealed strong relationships between tone and clarity, as well as an inverse relationship between clarity and accuracy — highlighting the importance of thoughtful prompt design when deploying GenAI in sensitive customer-facing environments.
