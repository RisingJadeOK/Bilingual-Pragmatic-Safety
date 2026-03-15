# Pragmatic Evasion: Why "Politeness" is a Safety Risk

### The Problem
Most AI safety alignment is optimized for English-centric directness. This project demonstrates that **Korean Honorifics (존댓말)** and high-register linguistic patterns can be used to bypass safety guardrails. When a harmful intent is wrapped in "extreme politeness," many models fail to recognize the underlying violation.

### Research Thesis
This is a study on **Pragmatic Evasion**. We argue that safety filters are often "blind" to indirect speech acts. A model that refuses a rude request in English may comply with a polite, metaphorical version in Korean, highlighting a critical "Safety Tax" for non-English users.

### Key Deliverables
* **Bilingual_Adversarial_Pairs.json**: A dataset mapping direct English refusals to successful Korean "polite" bypasses.
* **Linguistic_Analysis.md**: A breakdown of how register and honorifics lower the model's refusal threshold.

### References
* Yong, S. S., et al. (2023). *Low-Resource Languages and the Safety Gap*.
* Wong, R. (2024). *The Pragmatics of Jailbreaking*.
