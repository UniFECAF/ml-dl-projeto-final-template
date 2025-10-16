[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/d2enqy8e)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=20978592&assignment_repo_type=AssignmentRepo)
# 🚀 Projeto Final — Machine Learning & Deep Learning (Aula 01)

> Preencha este arquivo seguindo o roteiro abaixo. Use linguagem simples e objetiva.
> **Não envie dados grandes para o repositório.** Coloque links para o dataset e mantenha apenas amostras pequenas se necessário.

## 1) Identificação do Projeto
- **Título do projeto:** _Ex.: Detecção de Pneumonia em Raios-X_
- **Turma/Disciplina:** _Ex.: MLDL — 2025.2_
- **Professor:** Rodrigo Moreira
- **Grupo (até 5):** Nome completo + e-mail/usuário GitHub  
  - Integrante 1 — Viviane Santos / vivianesantos1998
  - Integrante 2 — Mariana Funari / marianafunari04
  - Integrante 3 — Carolina Santos / santoscarolinac
  - Integrante 4 — Luan Rodrigues / 
  - Integrante 5 — Isabel Lais Farias / Lais15

## 2) Pitch (2–3 linhas)
> Em poucas frases, diga o que o projeto faz e por que importa.
## 3) Definição do Problema
- **Tema:** _Saúde, Finanças, PLN, Visão Computacional, Séries Temporais, etc._
- **Problema (pergunta mensurável):** _O que queremos prever/classificar?_
- **Objetivo do modelo:** _Ex.: classificar imagens em saudável vs. pneumonia_
- **Variáveis (entrada/saída):** _Ex.: pixels (X), rótulo (y)_
- **Relevância/Impacto:** _Por que é útil? Quem se beneficia?_

## 4) Dataset
- **Fonte e link:** _Kaggle/UCI/Hugging Face/Google Dataset Search_
- **Descrição resumida:** _#amostras, #features, tipo (tabular/imagem/texto/séries)_
- **Tamanho aproximado:** _MB/GB_
- **Licença:** _Ex.: CC BY 4.0_
- **Alvo (target):** _coluna/arquivo de rótulos_
- **Balanceamento:** _Classes balanceadas? Se não, como lidar? (SMOTE, pesos, etc.)_
- **Como será carregado:** _Link direto/Download local/Drive/HF Datasets_

## 5) Estratégia Inicial
- **Baseline ML:** _Ex.: Regressão Logística/Decision Tree com features simples_
- **Modelo ML principal:** _Ex.: Random Forest, SVM, XGBoost (justifique)_
- **Deep Learning:** _Ex.: MLP/CNN/RNN conforme tipo de dado (justifique)_
- **Métricas principais:** _Accuracy, F1, AUC-ROC, MAE/MSE, etc., com justificativa_
- **Critérios de sucesso (meta):** _Ex.: F1 ≥ 0.85 no conjunto de teste_

## 6) Riscos e Considerações Éticas
- **Viés nos dados:** _Classes desbalanceadas? Representatividade?_
- **Privacidade/LGPD:** _Contém dados pessoais? Quais cuidados?_
- **Limitações conhecidas:** _Ex.: tamanho do dataset, ruído, generalização_

## 7) Cronograma (alto nível)
- **Aula 01:** Problema + Dataset ✅
- **Aula 02:** EDA + Preparação de dados
- **Aula 03:** Baseline + ML tradicional
- **Aula 04:** DL (rede neural) + comparação
- **Aula 05:** Avaliação final + Deploy + Apresentação

## 8) Estrutura do Repositório
```
.
├── .github/
│   ├── ISSUE_TEMPLATE/
│   │   └── aula01.yml
│   └── PULL_REQUEST_TEMPLATE.md
├── data/
│   ├── raw/            # dados brutos (não versionar arquivos grandes)
│   └── processed/      # dados processados (não versionar arquivos grandes)
├── docs/
│   ├── checklist_aula01.md
│   └── relatorio_template.md  # usaremos na entrega final
├── notebooks/          # notebooks Colab/Jupyter
├── src/                # código fonte (funções/utilitários)
├── .gitignore
├── LICENSE
└── README.md           # este arquivo
```

## 9) Como rodar (Local ou Colab)
- **Colab:** Abra `notebooks/` e crie um notebook. Use o link do dataset para carregar os dados.
- **Local (opcional):**
  ```bash
  python -m venv .venv
  source .venv/bin/activate  # (Windows: .venv\Scripts\activate)
  pip install -r requirements.txt
  ```

## 10) Status
- [ ] Tema definido
- [ ] Problema e objetivo escritos
- [ ] Dataset escolhido e validado
- [ ] Justificativa concluída
- [ ] Issue “Aula 01 — Kickoff” aberta e preenchida

---

### 📌 Convenções
- Nome do repositório: `mldl-2025-grupoNN-tema-curto` (ex.: `mldl-2025-grupo03-pneumonia`)
- Não subir arquivos > 50 MB. Para dados grandes, use link externo.
- Cada alteração relevante deve vir via Pull Request com descrição clara.
