# Taglish-Translation

This repository contains code, prompts, and test data for the thesis project on machine translation of English to Taglish using large language models. The project explores the effect of fine-tuning, prompting strategy, and prompt language on translation quality and syntactic behavior in a low-resource, code-switched setting.

---

## 📂 Repository Structure

- `test-tweets-english.csv` – Test datasets
- `prompts/` – Prompt templates for few-shot and zero-shot configurations
- `notebooks/`
  - `sea_lion_inference.ipynb` – Runs inference on Sea Lion v3 9B IT (base model)
  - `sea_lion_finetune_lora.ipynb` – Lightweight fine-tuning using synthetic Tweet Taglish data
  - `finetuned_sea_lion_inference.ipynb` – Inference using the fine-tuned Sea Lion model

---

## 🚀 Setup Instructions

This project is designed for **Google Colab** using files stored in **Google Drive**.

### Dependencies

Install required Python packages (only needed if running outside Colab):

```bash
pip install -r requirements.txt
```

---

## 📊 Data Sources

- `test-tweets-english.csv`: From Kaggle  
  **Citation**:  
  Amirhossein Naghshzan (2022). *Twitter 2022 Dataset*.  
  [https://www.kaggle.com/datasets/amirhosseinnaghshzan/twitter-2022](https://www.kaggle.com/datasets/amirhosseinnaghshzan/twitter-2022)  
  *Accessed: 2025-06-06*

- Fine-tuning data: Based on **Tweet Taglish Dataset** (not publicly shared due to Twitter’s TOS).  
  **Acknowledgment**: Megan Herrera, Ankit Aich, Natalie Parde (2022)

---

## 🧠 Base Model

This project uses the **Sea Lion v3 9B IT** model as the base.  
**Citation**:
> SEA-LION: Southeast Asian Languages in One Network  
> Raymond Ng et al. (2025)  
> [arXiv:2504.05747](https://arxiv.org/abs/2504.05747)

---

## 📈 How to Run

- Open the desired `.ipynb` notebook in **Google Colab**
- Mount Google Drive
- Follow the notebook instructions to run inference or fine-tuning

---

## 📌 Citation

If using this repository or associated findings, please cite:

> Charlotte Puopolo. (2025). *Analyzing LLM Performance on Taglish Translation*. Master’s Thesis, University of the Basque Country (UPV/EHU).

---

## ⚠️ License & Terms

This repository is shared under the MIT License.  
The fine-tuning dataset cannot be distributed due to Twitter's Terms of Service.

---

## 🔗 Links

- Thesis (coming soon)
- [SEA-LION paper](https://arxiv.org/abs/2504.05747)
