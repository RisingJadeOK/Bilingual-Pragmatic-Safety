# Bilingual-Pragmatic-Safety
Cross-Lingual Vulnerabilities in Safety Alignment: Pragmatic Evasion in Korean-English LLMs

#Title: Cross-Lingual Vulnerabilities in Safety Alignment: Pragmatic Evasion in Korean-English LLMs

#Abstract:
Current AI safety guardrails are predominantly trained on English datasets, leading to a "safety tax" or "alignment gap" in low-resource or morphologically complex languages. This research investigates Pragmatic Evasion, where harmful intent is disguised through Korean-specific linguistic features such as Honorifics (존댓말) and Euphemisms (완곡어법). We demonstrate that models which successfully refuse a harmful request in English often comply when the same intent is phrased with high-register politeness or indirect metaphors in Korean. This project provides a bilingual red-teaming dataset to evaluate the cross-lingual consistency of safety filters.

#Key Citations:
Yong et al. (2023), Low-Resource Languages and the Safety Gap: "Safety alignment does not always transfer across languages, leaving non-English users at higher risk."
Wong (2024), The Pragmatics of Jailbreaking: "Indirect speech acts are more effective at bypassing intent classifiers than direct commands."
