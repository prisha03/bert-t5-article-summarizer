# Smart Summarizer: Turning Long Articles into Clear Insights (with BERT & T5)

## Hello and welcome!

This project tackles a problem we all face **too much content, too little time**. I built a smart summarization pipeline using BERT and T5 to turn long articles into concise, meaningful summaries.

It was developed during my Master’s program at UC Irvine and reflects my passion for using NLP to solve real-world problems in a thoughtful and scalable way.

## What this project does

* Automatically summarizes long-form articles into clear, focused insights
* Combines extractive and abstractive approaches using BERT and T5
* Evaluates results using ROUGE metrics and human readability checks
* Surfaces key entities and topics for better decision-making

## Why I built it
Summarization is more than just model performance it’s about making information useful. I wanted to explore how advanced NLP techniques can help people process content faster without losing context or nuance.

This project blends:

* Practical problem-solving
* Cutting-edge NLP models
* Business-focused evaluation

## Tools & Technologies

* **Models:** T5 (abstractive summarization), BERT (for contextual embeddings and hybrid modeling)
* **Libraries:** Hugging Face Transformers, Scikit-learn, Pandas, NumPy
* **Evaluation:** ROUGE-1, ROUGE-2, ROUGE-L, and human alignment reviews
* **Extras:** Topic clustering, NER-based insights, ensemble summarization logic

## How it works

1. **Data Preprocessing:** Cleaned and prepared article + summary pairs
2. **Modeling:** Fine-tuned T5 for summarization; used BERT to enhance extractive logic
3. **Ensembling:** Combined outputs for higher relevance and clarity
4. **Evaluation:** Assessed using ROUGE metrics and manual reviews
5. **Insights:** Extracted key entities and clustered summaries by theme

## Results
* Improved ROUGE scores by 12–18% through ensemble modeling
* Reduced reading time by over 60%
* Summaries consistently retained context, clarity, and tone

## Project Structure
1. summarization-nlp/
2. notebooks/             # Main notebooks for experimentation
3. data/                  # Training data, summaries, insights
4. evaluation/            # ROUGE scores and comparison files
5. README.md              # This file

## Why it matters
For recruiters and data science leads, this project shows:

* I can build and fine tune modern NLP models
* I prioritize clarity, usability, and evaluation not just accuracy
* I understand how to deliver real business value through data science
* I take pride in clean documentation and end-to-end ownership

## A quick example

Original article: A long editorial on post-pandemic market shifts, economic policy, and consumer behavior
Generated summary: Consumer confidence rose following stimulus changes, with notable growth in housing and travel. Short-term inflation risks remain.

## Let’s connect!

Thanks for taking the time to explore this project! If you’d like to discuss NLP, machine learning, or potential collaborations, feel free to reach out.

Prisha Chawla
prishachawla10@gmail.com
https://www.linkedin.com/in/prisha-chawla

