# GenZ-emotion-analysis

📌 Overview

This repository contains a CSV dataset of ~6,000 Reddit comments focused on Gen-Z discourse, annotated with probability scores for 28 emotions.

The dataset is intended for emotion analysis, affective NLP, and behavioral research, capturing emotional intensity rather than binary sentiment.

📂 Dataset Summary

Total comments: ~6,000

Platform: Reddit

Target group: Gen-Z related discussions

Language: English

Minimum comment length: More than 5 words

Format: CSV

Emotion labels: 28 (probabilistic, multi-label)

All URLs, hyperlinks, and external references were removed during preprocessing.

🧠 Emotion Labels (28)

Each comment is associated with 28 emotion probability scores ranging from 0.0 to 1.0.

Examples include:

Joy

Sadness

Anger

Fear

Anxiety

Love

Loneliness

Hope

Guilt

Shame

Pride

Gratitude

Disappointment

Neutral

(and others — total 28)

Emotion values represent model confidence, not absolute emotional truth.

🛠️ Data Collection

Data was scraped using PRAW (Python Reddit API Wrapper)

Only public Reddit comments were collected

No usernames, IDs, or personal identifiers are included

Links and URLs were removed

Comments shorter than 5 words were excluded

🤖 Emotion Annotation Method

Emotion probabilities were generated using RoBERTa-based emotion classification model

The model outputs a probability distribution across 28 emotions

No manual labeling was performed

🚀 Use Cases

This dataset can be used for:

Emotion classification & analysis

Gen-Z behavioral pattern research

NLP experimentation & benchmarking

Feature engineering for ML models

Emotional trend visualization

Social media psychology studies

⚠️ Limitations & Ethical Considerations

Emotion labels are model-generated, not human-verified

Predictions may reflect model bias or ambiguity

Emotional scores do not imply mental health diagnosis

Data should be used responsibly and respectfully

📜 License & Usage

This dataset is shared for educational and research purposes.

Please ensure compliance with:

Reddit’s content policies

Ethical research standards

Commercial use is not recommended without independent review.

🙌 Acknowledgements

Reddit communities for publicly available discussions

Open-source NLP and transformer research

HuggingFace ecosystem for pretrained models

✨ Closing Note

This dataset aims to explore emotional patterns — not to reduce human expression to fixed labels.
