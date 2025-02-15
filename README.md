# **Automated Classification of IT Service Tickets Using OpenAI API**

## **Project Overview**
This project explores the use of **Large Language Models (LLMs)**, specifically **OpenAI's API**, to classify IT service tickets into predefined categories. The goal is to evaluate how well an LLM can perform text classification without extensive training data.

## **Project Objectives**
- Leverage **OpenAI's API** for **automated text classification** of IT service tickets.
- Compare the model's predictions with **pre-labeled categories** to assess accuracy.
- Gain insights into the effectiveness of **LLM-powered classification**.

## **Dataset**
- The dataset consists of **IT service tickets** with predefined categories.
- Each ticket contains **unstructured text** describing an issue and a corresponding **labeled category**.

## **Implementation Steps**

1. **LLM Classification using OpenAI API**
   - Sent ticket descriptions as **prompts** to the OpenAI API.
   - Extracted category predictions based on model output.

2. **Accuracy Evaluation**
   - Compared the **model’s predictions** against the **pre-labeled categories**.
   - Calculated accuracy as **53%**, though the true accuracy remains uncertain due to potential inconsistencies in the dataset.

## **Results & Insights**
✅ **53% Accuracy**: The model correctly classified 53% of the tickets when compared to predefined categories.  
✅ **Prompt Engineering Matters**: The accuracy could be improved by refining prompts or providing additional context.  
✅ **LLMs vs. Traditional Models**: LLMs can perform classification **without training** but may lack precision compared to **fine-tuned models**.  

## **Project Costs**
💰 **Total Cost**: ~$1.30 (due to re-running some queries on a small dataset).  

## **Technologies Used**
- **Python**  
- **OpenAI API**  
- **Pandas** (for data manipulation)  
- **Jupyter Notebook** (for development and testing)

## **Next Steps & Future Improvements**
🚀 **Improve Accuracy** by refining prompt structure and experimenting with temperature settings.  
📊 **Expand Dataset** to test model performance on a larger sample.  
🔄 **Compare with Traditional Models** like **Logistic Regression** or **Random Forest** for benchmarking.

**[Click to View the Code](https://github.com/Ainaganiu/Automated-Classification-of-IT-Service-Tickets-Using-OpenAI-API/blob/main/IT_Ticket_Classification.ipynb)**
