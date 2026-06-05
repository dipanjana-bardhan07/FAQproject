
# IIT Ropar FAQ Search System
A robust, semantic FAQ search system tailored for the IIT Ropar dataset. This project leverages state-of-the-art Natural Language Processing (NLP) to match user queries with official FAQs, ensuring highly accurate and context-aware responses rather than simple keyword matching. It features a secure user authentication layer and an intuitive web interface.
## 🚀 Features
 * **Semantic Search Engine:** Utilizes Sentence-Transformers (all-MiniLM-L6-v2) to map queries and FAQs into a vector space, measuring cosine similarity to find the most accurate match—even if different words are used.
 * **Threshold-Based Fallbacks:** Includes built-in confidence checking. If a user query scores below a certain similarity threshold, the system gracefully responds with a fallback message rather than providing irrelevant information.
 * **Secure Authentication:** Integrated user login and signup functionality to restrict access to authorized personnel and students.
 * **Optimized Dataset:** Includes pre-processed, clean FAQ datasets (clean_faqs.json) ready for semantic indexing.
## 🛠️ Tech Stack
 * **Language:** Python
 * **NLP & Machine Learning:** Sentence-Transformers, PyTorch, Util (Cosine Similarity)
 * **Version Control:** Git & GitHub
## 📦 Project Structure
```text
FAQproject/
│
├── semantic_search.py     # Main NLP backend and query matching logic
├── clean_faqs.json        # Pre-processed IIT Ropar FAQ dataset
├── honor_code.pdf         # Academic integrity compliance document
└── signed_offerletter.pdf  # Project onboarding reference

```
## 📖 Step-by-Step Implementation Guide
If you want to understand the foundational logic or need a step-by-step tutorial on building semantic search systems with authentication, check out these excellent tutorial resources:
 * **Semantic Search Concepts:** Building Semantic Search with Sentence Transformers - YouTube Tutorial
 * **Authentication Systems:** User Authentication and Login Systems in Python - YouTube Tutorial
## 📄 License & Acknowledgements
### Acknowledgements
 * **IIT Ropar:** Heartfelt thanks to the institute for providing the baseline FAQ data and guidelines necessary to structure this system.
 * **Hugging Face:** For hosting and maintaining the pre-trained all-MiniLM-L6-v2 transformer model used in this architecture.
### License
This project is licensed under the **MIT License**.
```text
MIT License

Copyright (c) 2026 Dipanjana Bardhan

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

```
