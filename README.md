# Crafted LLMs Portfolio

![Python](https://img.shields.io/badge/Python-3.10%2B-blue?style=for-the-badge&logo=python&logoColor=white)
![PyTorch](https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white)
![HuggingFace](https://img.shields.io/badge/HuggingFace-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black)

## 📖 About This Collection

These are a showcase of the LLMs I have finetuned, manipulated or otherwise trained that I am most proud of. I enjoy applying new techniques to older models, such as my series of models applying reasoning to the OPT based Galactica by Meta/Facebook.

My goal is to exploration, with the hope that something turns out useful.

## 🚀 Model Showcase

Below is a curated list of my trained models. Click the badges to visit the respective HuggingFace repositories.

| Model Name | Short Description | Repository |
| :--- | :--- | :---: |
| **HomeGem4Bn** | A finetune of 4-bit Gemma 3n-e4b against the acon96/Home-Assistant-Requests, designed for use as a local LLM to control your Home Assistant environment. | [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Open_Repo-blue)](https://huggingface.co/TitleOS/HomeGem4Bn) |
| **Galactic Reasoning LoRA Adapters** | A collection of the Galactic Reasoning adapters, finetuned to provide chain of thought and reasoning to Meta's OPT-based Galactica models. | [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Open_Repo-blue)](https://huggingface.co/collections/TitleOS/galactic-reasoning-lora-adapters) |
| **Coming Soon** | Phi4-mini-reasoning tuned for Home Assistant using the acon96/Home-Assistant-Requests dataset. | [![HuggingFace](https://img.shields.io/badge/%F0%9F%A4%97-Open_Repo-blue)](https://huggingface.co/TitleOS/HomePhi4_4B)) |

## 🧪 Featured Project: Galactic Reasoning LoRA Adapters aka Modernizing Galactica

One of my primary areas of research has been revitalizing Meta's **Galactica** (based on OPT). Despite being an older architecture, Galactica possesses unique scientific knowledge such as science paper citation.

By applying modern reasoning datasets and fine-tuning techniques, I have been able to:
* Reduce hallucination in scientific queries.
* Induce step-by-step reasoning capabilities previously absent in the base model.
* Bridge the gap between older architectures and modern reasoning/thinking standards.

## 💻 Usage

You can load most of these models using the standard `transformers` library:

```python
from transformers import AutoTokenizer, AutoModelForCausalLM
import torch

model_id = "your-username/your-model-name"

tokenizer = AutoTokenizer.from_pretrained(model_id)
model = AutoModelForCausalLM.from_pretrained(
    model_id,
    torch_dtype=torch.float16,
    device_map="auto"
)

input_text = "Do androids dream of electric sheep?"
input_ids = tokenizer(input_text, return_tensors="pt").to("cuda")

outputs = model.generate(**input_ids, max_new_tokens=200)
print(tokenizer.decode(outputs[0]))
```

## 📫 Contact

If you have questions about the training methodologies or datasets used for these models, feel free to reach out or open an issue in this repository.

HuggingFace: https://huggingface.co/TitleOS

Personal Blog: https://blog.titleos.dev

BlueSky: https://bsky.app/profile/titleos.dev
