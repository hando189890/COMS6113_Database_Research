# COMS6113_Database_Research

## Topics: Optimizing Text-to-SQL Models for Chinese Language Translation: A Cross-Evaluation of Single-Language and Multilingual Models

## Abstract:
Text-to-SQL converts natural language to structured SQL queries for retrieving desired information, enabling effective communication between users and databases. This is critical for modern database systems as users demand more natural and intuitive access. As regional integration increasingly serves as a development strategy globally, the demand for Text-to-SQL to support multiple languages has grown. However, current Text-to-SQL models are typically trained solely on English or on multiple languages but exhibit lower accuracy when applied to languages other than English. In this research paper, our goal is to optimize existing English models to achieve better performance on the Chinese language, which has the second-largest number of users worldwide. Specifically, we aim to optimize existing Seq2Seq, T5, and mBart-50 models to enhance their performance in Chinese translation tasks. Furthermore, we intend to conduct cross-evaluations to assess the effeciency of both single-language and multilingual models for translating the Chinese language.

## Group Members:
- Yizhen Zhang (yz4401)
- Dongbing Han (dh3071)
- Tao Yan (ty2481)

## Links:
- Github: [https://github.com/hando189890/COMS6113_Database_Research]
- Proposal Submission: [https://drive.google.com/file/d/1MELr3R93dKTgHo0gM400R6zqdVT1HVgS/view?usp=share_link]
- Final Paper Submission: [https://www.dropbox.com/s/uw66acogoxuoq4u/proposal%20Draft-Optimizing%20Text-to-SQL%20Models%20for%20Chinese%20Language%20Translation%20A%20Cross-Evaluation%20of%20Single-Language%20and%20Multilingual%20Models%20Dongbing%20han.pdf?dl=0]
- WikiSQL dataset: https://github.com/salesforce/WikiSQL
- Chinese WikiSQL dataset:https://drive.google.com/file/d/1GAUs6U3U3qrLX_53eqK_vlqUblqPr7j1/view?usp=share_link


## Files Description:
- English-Seq2seq-From_Scratch.ipynb: English version of seq2seq model in Text to SQL task
- English-T5-Fine_tuned_Pretrained.ipynb: English version of T5 model in Text to SQL task
- English-mbart-Fine_tuned_Pretrained.ipynb: English version of Multilingual mbart model in Text to SQL task  
- Chinese-schema-aware-denoising-mbart-Fine_tuned-Retrain.ipynb: Chinese version of Multilingual mbart model in Text to SQL task 
- Mixture-schema-aware-denoising-mbart-Fine_tuned-Retrain.ipynb: Mixed Chinese and English version of Multilingual mbart model in Text to SQL task 
- Chinese-mbart-Fine_tuned-Retrain.ipynb: Fine_tuned Chinese version of monolingual mbart model in Text to SQL task



