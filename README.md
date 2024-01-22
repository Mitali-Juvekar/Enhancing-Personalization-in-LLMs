# Enhancing-Personalization-in-LLMs
This repository contains the code and resources for our Information Retrieval project conducted during Semester 1. Collaborating with my teammate Isha, we aimed to enhance personalization in large language models using two LaMP datasets: "Personalized Tweet Paraphrasing" and "Personalized News Headline Generation." Our focus was on leveraging query paraphrasing and profile-based retrieval.


Key Features:

Datasets Used: Personalized Tweet Paraphrasing, Personalized News Headline Generation

Language Models: XLNet and Sentence BERT

Paraphrasing Model: Humarin ChatGPT paraphraser based on the T5 model

Retrieval Models: RoBERTa and Sentence BERT

Objective: Compare the effectiveness of XLNet and Sentence BERT in generating personalized outputs when combined with query paraphrasing and profile-based retrieval.

Abstract Summary:
Our research hypothesis posited that query paraphrasing, facilitated by the Humarin ChatGPT paraphraser, generates diverse user queries. Retrieval models (RoBERTa and Sentence BERT) then extract varied articles from individual profiles. This approach aimed to increase diversity and tailor outputs to user interests and contexts. Our experiments compared XLNet and Sentence BERT on evaluation metrics, considering paraphrasing and profiles as augmentative prompts.


In our quest to generate compelling headlines for articles, we harnessed the power of PaLM, an innovative language model available through Google's generative AI. This process began with the importation of PaLM using google.generativeai, followed by the creation of an API key. A well-constructed prompt serves as the guiding input for the language model, influencing the relevance and coherence of generated responses. The prompt we crafted for PaLM  is carefully structured to instruct the model effectively. In essence, it introduces the model to its role as a helpful and informative bot, specifying the task of answering questions using text from a provided reference passage.


Insights and Contributions:

Demonstrated the effectiveness of query paraphrasing in generating diverse user queries.
Evaluated the performance of XLNet and Sentence BERT in the context of personalized information retrieval.
Provided insights into leveraging query augmentation and profile diversity to improve personalization across natural language tasks.

How to Use:

Clone the repository: git clone https://github.com/your-username/your-repository.git

Navigate to the project directory: cd your-repository

Run the code on your preffered platform.
