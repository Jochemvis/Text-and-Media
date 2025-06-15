# Text-and-Media
## Analysis of #ExtinctionRebellion Tweets (2019–2022)

In this project, we explored how effectively topic modeling and sentiment analysis can support the identification and prediction of events related to the climate movement #ExtinctionRebellion on Twitter. We analyzed five datasets, each representing a different time period between 2019 and 2022. In total, 288,300 tweets were examined, all corresponding to key XR protest moments.

Each dataset was processed using the same analysis pipeline, with slight adjustments to hyperparameters and time-specific filtering. The core methods involved Latent Dirichlet Allocation (LDA) for topic modeling, K-means clustering to group related tweets, and VADER for sentiment analysis. This allowed us to track how the content and tone of online discussions evolved over time.

The results show that it is indeed possible to detect real-world XR events through these techniques. For instance, in April 2019, the model picked up themes around George Monbiot’s videos, in October 2019 it captured the preemptive arrests of protesters, in 2020 it identified the newspaper blockades, in 2021 protests against banks funding fossil fuels, and in 2022 actions targeting oil companies. While this demonstrates the usefulness of topic modeling for event detection, we also encountered limitations, such as the presence of high-frequency generic words and overlapping topics that made interpretation more difficult.

Sentiment analysis revealed a growing trend of negative sentiment over the years, possibly reflecting increasingly disruptive actions or shifting public opinion. However, the VADER model used here struggled with detecting nuance or irony, and since neutral tweets were excluded, the sentiment trends may be somewhat oversimplified.
