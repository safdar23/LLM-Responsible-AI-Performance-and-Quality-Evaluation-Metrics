# LLM-Responsible-AI-Performance-and-Quality-Evaluation-Metrics

# Introduction

We will use promptflow SDK to implement the above stated Performance, Quality, and Responsible AI metrics. This repo has two json files with responsible ai and quality data and a notebook to run through the process.

# Prerequisites

1) The Performance and Quality metrics will need access to Azure Open AI models, please provide the model related configuration in the notebook
2) The Responsible AI metrics will need access to Azure AI Studio, please provide the configuration in the notebook

# Puprpose
The purpose of this notebook is to run the LLM evaluations across quality and responsible AI metrics for QA and chat session scenarios

Large language models metrics can be measured using the below measurement methods for question-answering and conversation generative AI applications:

**Traditional Machine Learning Metrics**

**AI-Assisted Metrics:** These metrics evaluate AI-generated output, even when there is no predefined ground truth. These metrics are further  segregated into two types

-- **Performance and Quality Metrics**

 -- **Responsible AI metrics**
 
# Traditional Machine Learning Metrics

These metrics, such as the F1 score, measure precision and recall by comparing AI-generated responses to expected answers. The F1-score measures the number of shared words between the generated response and the ground truth and calculated precision and recall. Precision is the ratio of the number of shared words to the total number of words in the generated response, and recall is the ratio of the number of shared words to the total number of words in the ground truth.

# AI Assisted: Performance and Quality metrics

These metrics assess the quality and coherence of the generated content, including coherence, fluency, groundedness, relevance, retrieval score, and similarity.

# AI Assisted: Responsible AI Metrics
Azure AI identifies content and security risks, including contents related to hateful, unfair, sexual, violent, self-harm, and jailbreak defects. Azure responsible AI scores these contents severity across (very Low (0–1), Low (2–3), Medium (4–5) and High (6–7). High (6–7) is the extremely rated content. For detailed information, please visit Evaluation and monitoring metrics for generative AI - Azure AI Studio | Microsoft Learn






