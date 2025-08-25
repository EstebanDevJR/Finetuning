# 🧠 Fine-tuning BERT en Español  

Este repositorio contiene un notebook para realizar **fine-tuning** del modelo [dccuchile/bert-base-spanish-wwm-uncased](https://huggingface.co/dccuchile/bert-base-spanish-wwm-uncased), un modelo BERT preentrenado en español, utilizando la librería **🤗 Hugging Face Transformers**.  

El objetivo es mostrar cómo adaptar un modelo de lenguaje general al dominio de un conjunto de datos específico (clasificación de texto en español).  

---

## 🚀 Características  
- Uso de **Transformers de Hugging Face**  
- Fine-tuning del modelo BERT para español  
- Pipeline completo: carga de datos → tokenización → entrenamiento → evaluación  
- Compatible con CPU y GPU (CUDA)  
- Ejemplo listo para reutilizar en otros datasets  

---

## 📂 Contenido del repositorio  
- 📓 `Finetuning.ipynb`: notebook principal con todo el proceso de entrenamiento  
- 📝 `README.md`: descripción del proyecto  

---

## ⚙️ Requisitos  
Instala las dependencias necesarias:  
```bash
pip install torch torchvision torchaudio
pip install transformers datasets evaluate
pip install scikit-learn
```
---

## ▶️ Uso
```bash
git clone https://github.com/EstebanDevJR/Finetuning.git
```
---

## 📊 Resultados esperados
- Un modelo fine-tuneado en español para clasificación de texto.
- Métricas de evaluación como accuracy, precision, recall y F1.
- Gráficas de pérdida y exactitud por época.

---
## 📌 Créditos
- Modelo base: dccuchile/bert-base-spanish-wwm-uncased
- Framework: Hugging Face Transformers
