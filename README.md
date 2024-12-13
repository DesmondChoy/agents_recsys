# agents_recsys

## Addressing Key Pain Points

This repository is designed to solve significant challenges faced by both customers (looking to buy travel insurance) and insurers:

### For Customers
- **Insurance Jargon:** Reading and understanding insurance policies can be overwhelming due to their dense and complex language. This often leaves customers unsure about what they’re covered for.
- **Tailored Recommendations:** Finding the right insurance policy is often time-consuming, with customers left to manually compare plans that may not fit their unique needs.
- **Saving Time:** Customers no longer need to sift through endless documents—this system processes the information for them.

### For Insurance Companies
- **Making Policies Accessible:** Insurance companies can struggle to make their dense policy documents more approachable for users. This repository automates that process, transforming hard-to-read PDFs into user-friendly formats.
- **Personalized Suggestions at Scale:** Crafting tailored insurance recommendations is often labor-intensive, but this repository makes it scalable by using multi-agent workflows.
- **Cutting Costs:** Automation significantly reduces manual work for document processing and customer engagement, saving operational expenses.

---

## Solutions

This repository tackles the above challenges with two powerful tools:

### 1. Automated Document Processing
The `pdf_to_md.ipynb` notebook automates the conversion of PDF insurance policies into markdown files. Markdown provides a clean and structured output that can be easily understood by downstream agents.

### 2. Intelligent Recommendation Workflow
The `recsys.ipynb` notebook leverages a multi-agent approach to create highly personalized policy recommendations. By mimicking domain experts, it extracts user-specific inputs such as age, medical history, or travel plans from unstructured conversations, analyzes all insurance policies, and recommends the most appropriate policy in a short report that can be easily understood. This innovative use of agents saves time and provides accurate, relevant recommendations, making it easier for customers to find the right plan.

These solutions are not only practical but also innovative, offering a blend of automation and intelligence to improve the insurance experience for all parties.

---

## Roadmap

- [x] Docling to preprocess PDFs
- [x] Conversation Transcript Agent, Underwriting Report Agent and respective tasks
- [x] Recommendation Agent to perform final recommendation
- [ ] Evals (Extraction, Underwriting Report, Final Rec)
- [ ] User-friendly interface supporting data flywheels