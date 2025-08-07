# Gender & Academic Language

**Authors**: Jia Lin, Linghan Zheng, Marco Boso  
**Date**: August 2025  
**Course**: Text Mining & NLP  

## Overview

This project investigates gender-based differences in academic writing on **bullying culture in the United States**. Using text mining techniques on ten academic papers (5 by male authors, 5 by female authors), we analyze vocabulary, narrative structure, and thematic focus.

The analysis covers:
- TF-IDF term comparison by gender
- N-gram frequency analysis (bigrams and trigrams)
- Topic modeling using LDA
- Sentiment analysis with negation handling
- Word co-occurrence networks and correlation patterns

## Dataset

The dataset includes:
- 10 academic papers (PDF format) on bullying in U.S. schools
- Manual annotation of author gender (5 male, 5 female)
- Text split into `abstract`, `introduction`, `body`, and `conclusion` sections
- Preprocessed and converted into tidy text format

## Key Libraries Used

- `pdftools` – PDF text extraction  
- `dplyr`, `tidyverse`, `tidyr`, `tibble` – data manipulation  
- `stringr`, `tidytext` – text preprocessing and tokenization  
- `ggplot2`, `forcats`, `grid` – visualizations  
- `purrr` – functional programming  
- `topicmodels` – topic modeling (LDA)  
- `igraph`, `ggraph`, `widyr` – network analysis and co-occurrence mapping  

## Text Mining Techniques

- **TF-IDF Analysis**: Highlights terms that are particularly characteristic of male or female authors  
- **N-Gram Modeling**: Identifies common two- and three-word phrases used by each gender group  
- **Sentiment Analysis**: Measures emotional tone, with attention to negated terms (e.g., "not happy")  
- **Topic Modeling**: Reveals thematic focus using Latent Dirichlet Allocation  
- **Word Networks**: Constructs co-occurrence graphs to visualize word associations

## Key Findings

- **Female authors** emphasize identity, gender, LGBTQ+ topics, and social justice  
- **Male authors** focus more on mental health, behavior, and structural framing  
- Vocabulary and narrative structure vary notably between genders  
- Topic modeling confirms differing thematic focus across the corpus  
- Sentiment and correlation analysis show stylistic and emotional divergence

## Visual Outputs

Visualizations include:
- Bar plots and word clouds of TF-IDF terms  
- Frequency graphs for bigrams and trigrams  
- Topic distributions per document  
- Word co-occurrence networks by gender  
- Sentiment contribution charts with negation

## How to Run

1. Clone the repository using SSH:
   ```bash
   git clone git@github.com:MarcoBoso/Gender-Academic-Language.git
   cd Gender-Academic-Language
