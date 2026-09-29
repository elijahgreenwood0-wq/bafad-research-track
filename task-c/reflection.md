# Task C — Research Reflection

> **BAFAD Accelerated Research Track · Fall 2026**
> Complete **after** finishing Tasks A and B.

---

## Instructions

Write your responses directly in this file (replace the placeholder text).
Aim for **150–200 words total** across both questions.
Be specific — reference your actual experience with the data and code.

---

## Question 1 — Connecting the Work to Research

*After completing Tasks A and B, how does hands-on data exploration relate to the research problem described in **Anomaly Detection in Tactical Sensor Streams** (the document you read before the Canvas quiz)?*

Consider: What patterns did you observe in the SMAP data? How might those patterns complicate or inform the design of an autoencoder-based anomaly detector?

**Your response (75–100 words):**

>In Task A, I noticed that most SMAP telemetry values followed regular patterns, while anomalies appeared as sudden or unusual changes in one or more channels. The heatmap made it easier to see that anomalies may not always affect every channel in the same way. This is important for an autoencoder-based anomaly detector because the model would need to learn the normal patterns across multiple channels. Large reconstruction errors could then help identify unusual behavior. The variety in the data also shows why the model should consider several signals together instead of relying on only one channel.
---

## Question 2 — Self-Assessment of Readiness

*What specific gaps in your current knowledge — Python skills, statistics concepts, or ML background — do you expect to encounter if you join the research group? What is your plan for addressing them?*

Be honest. There are no wrong answers — this helps us plan the onboarding schedule.

**Your response (75–100 words):**

>I think my biggest challenges would be improving my Python skills and learning more about machine learning concepts. I understand basic statistics and data analysis, but I still need practice with coding, interpreting models, and understanding how neural networks such as autoencoders work. My plan is to practice Python regularly, review statistics concepts, and work through examples using pandas and matplotlib. I would also ask questions when I am unsure and use tutorials or course resources to strengthen my understanding before working on more advanced research tasks.

---

*Submission: commit this file to your fork and include it in the GitHub repo URL you submit on Canvas.*
