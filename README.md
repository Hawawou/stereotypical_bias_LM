# Study of Stereotypical Biases in LLMs for Medical Assistance

## Authors
**Pin-Xun HUANG,Hawawou O. TCHAPCHET ,N.Hedwig NAAVA, Reyanne ROMAIN**   

---

## Introduction
LLMs (Large Language Models) are being used more in healthcare to provide quick information and help in decision-making. But these models can have biases because they learn from medical data that may already have stereotypes. Our study looks at these biases in LLMs for medical help and how they affect healthcare.

### **Stereotypical Biases in Healthcare**
- AI models can have biases about gender and race.
- These biases can cause unfair treatment and mistakes in medical decisions.

### **Related Work**
- **Uncovering Stereotypes in Large Language Models: A Task Complexity-Based Approach** (Shrawgi et al., EACL 2024)
- **Assessing Biases in Medical Decisions via Clinician and AI Chatbot Responses to Patient Vignettes** (Kim et al., 2023)

---

## **Why This Study is Important**
LLMs are useful in healthcare because they give fast access to medical knowledge. But if they use biased information, they might make unfair decisions. Our study aims to:
- Find and measure biases in medical language models.
- Compare general and medical AI models to see which are more biased.
- Suggest ways to reduce bias in AI medical assistance.

---

## **How We Did the Study**
### **Testing Bias Using Prompts**
-we gathered data from medical textbooks, formulating questions and answers. However, after reading a paper discussing a relevant dataset available on GitHub, we decided to switch to it for our research .

### **Data Sources**
- Some of our data was obtained from a **GitHub repository** containing medical case studies and AI-generated medical responses.
- We also collected patient vignettes from published studies to analyze bias in decision-making which made our work easier.

### **Models We Used**
- **General Models:** Llama, Mistral
- **Medical Models:** BioMistral, JSL-MedLlama

---

## **Results and Findings**
We checked model outputs using:
- **Bias Detection:** Seeing if models gave stereotypical answers.
- **Fairness Tests:** Checking if answers were fair for different groups.
- **Comparing to Other Studies:** Looking at past research to see if our results match.


---

## **Thanks for Reading!**
We appreciate your interest in our study! If you have any questions or feedback, feel free to reach out.

**Contact:** Email us.

---

## **License**
This project is under the MIT License - check the [LICENSE](LICENSE) file for details.
