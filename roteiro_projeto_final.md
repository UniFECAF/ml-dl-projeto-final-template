# 🧠 Projeto Final — Machine Learning e Deep Learning  
**Disciplina:** Machine Learning e Deep Learning — UniFECAF  
**Professor:** Rodrigo Moreira  
**Período:** 2025/2  

---

## 🎯 Objetivo Geral
Desenvolver uma solução prática utilizando **Machine Learning** e **Deep Learning**, aplicando todas as etapas do ciclo de modelagem de dados:  
desde a **definição do problema**, **preparo dos dados**, **modelagem**, **avaliação** e **demonstração final**.

Cada grupo deverá trabalhar colaborativamente neste repositório, documentando suas decisões e mantendo o histórico de commits atualizado.

---

## 👥 Organização dos Grupos
- Grupos de até **5 integrantes**
- Cada grupo deve preencher as informações no `README.md`
- Criar e manter a **Issue “Kickoff do Projeto Final”** atualizada

---

## 📆 Roteiro de Aulas / Checkpoints

### 📍 **Aula 08/10 – Kickoff do Projeto**
**Tema:** Definição do problema e planejamento inicial

📝 **Entregas obrigatórias:**
- Preencher o `README.md` com:
  - Nome do grupo e integrantes  
  - Tema e contexto do problema  
  - Justificativa da relevância  
  - Objetivos do projeto  
  - Fonte do dataset (Kaggle, UCI, Hugging Face etc.)
- Abrir a **Issue “Kickoff do Projeto Final”** (já configurada no template)
- Organizar o repositório nas pastas: `data/`, `docs/`, `notebooks/`, `src/`

💡 **Dica:** Escolha um tema realista e viável com dataset público.

---

### 📍 **Aula 15/10 – Coleta e Preparação dos Dados**
**Tema:** Análise exploratória e pré-processamento

🧪 **Tarefas:**
- Explorar o dataset em `notebooks/EDA.ipynb`
- Identificar:
  - Quantidade de registros e features  
  - Valores ausentes e inconsistências  
  - Distribuição das variáveis
- Realizar:
  - Limpeza dos dados  
  - Normalização ou padronização  
  - Balanceamento (se necessário)
- Separar dados em **treino**, **validação** e **teste**

📁 **Arquivos esperados:**
- `notebooks/EDA.ipynb`
- `data/processed/` com dataset tratado

---

### 📍 **Aula 22/10 – Modelagem com Machine Learning**
**Tema:** Aplicação de algoritmos tradicionais de ML

🧠 **Tarefas:**
- Criar `notebooks/ml_model.ipynb`
- Implementar ao menos **um algoritmo tradicional** (Random Forest, SVM, XGBoost etc.)
- Comparar com **modelo baseline**
- Avaliar com métricas:
  - `Accuracy`, `Precision`, `Recall`, `F1-Score`, `AUC-ROC`
- Plotar **matriz de confusão**
- Documentar resultados no `README.md`

📈 **Entrega:**
- Notebook com código e análises  
- Resultados e comparações anotados

---

### 📍 **Aula 29/10 – Modelagem com Deep Learning**
**Tema:** Implementação de redes neurais

🤖 **Tarefas:**
- Criar `notebooks/dl_model.ipynb`
- Implementar ao menos **uma rede neural**:
  - `MLP`, `CNN` ou `LSTM`
- Utilizar **TensorFlow** ou **PyTorch**
- Comparar desempenho com modelo de ML
- Documentar:
  - Arquitetura  
  - Parâmetros de treino (épocas, batch size, otimizador)  
  - Resultados e gráficos (loss, accuracy)
- Adicionar análise comparativa no `README.md`

---

### 📍 **Aulas 05 e 12/10 – Deploy**
**Tema:** Conclusão, análise crítica e apresentação

📋 **Tarefas:**
- Escolher o **melhor modelo** (ML ou DL)
- Justificar a escolha com base nas métricas
- Opicional Criar **interface simples**:
  - [Gradio](https://gradio.app/) ou [Streamlit](https://streamlit.io/)
  - Ou API com Flask/FastAPI
- Fazer deploy (opcional) no:
  - [Hugging Face Spaces](https://huggingface.co/spaces)
  - [Streamlit Cloud](https://streamlit.io/cloud)
- Produzir relatório final (5 a 8 páginas)
- Atualizar o `README.md` com:
  - Conclusões  
  - Principais aprendizados  
  - Link da demonstração (se houver)

🎥 **Apresentação final:**
- Duração: **5 a 10 minutos**
- Mostrar problema, solução, código, resultados e interface

---

## ✅ **Checklist Final de Entrega**
- [ ] `README.md` completo e atualizado  
- [ ] Pastas organizadas (`data/`, `docs/`, `notebooks/`, `src/`)  
- [ ] Notebook com ML tradicional (`ml_model.ipynb`)  
- [ ] Notebook com DL (`dl_model.ipynb`)  
- [ ] Relatório final (PDF) em `docs/`  
- [ ] Deploy funcionando (ou demonstração local)  
- [ ] Issue “Kickoff” encerrada com informações finais  

---

## 💡 **Sugestões de Temas**
- **Saúde:** Diagnóstico de doenças via imagens ou sintomas  
- **Finanças:** Detecção de fraudes ou previsão de crédito  
- **Visão Computacional:** Classificação de imagens (flores, animais etc.)  
- **PLN:** Análise de sentimentos em reviews  
- **Séries Temporais:** Previsão de consumo de energia ou preços  

---

## 📚 Recursos Recomendados
- [Kaggle Datasets](https://www.kaggle.com/datasets)  
- [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/index.php)  
- [Hugging Face Datasets](https://huggingface.co/datasets)  
- [Scikit-learn Documentation](https://scikit-learn.org/stable/)  
- [TensorFlow](https://www.tensorflow.org/) | [PyTorch](https://pytorch.org/)  
- [Gradio](https://gradio.app/) | [Streamlit](https://streamlit.io/)

---

🧭 **Importante:**  
Todo o progresso deve ser versionado via **commits** frequentes e mensagens claras.  
Use **issues** para organizar tarefas e documentar decisões.  
O histórico de colaboração será considerado na avaliação final.

