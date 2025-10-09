# 🚀 Projeto Final — Machine Learning & Deep Learning (Aula 01)

> Preencha este arquivo seguindo o roteiro abaixo. Use linguagem simples e objetiva.
> **Não envie dados grandes para o repositório.** Coloque links para o dataset e mantenha apenas amostras pequenas se necessário.

## 1) Identificação do Projeto
- **Título do projeto:** Neto-IA
- **Turma/Disciplina:** GTI.4NA
- **Professor:** Rodrigo Moreira
- **Grupo (até 5):** Nome completo + e-mail/usuário GitHub  
  - Integrante 1 — DIEGO DOS ANJOS GOMES / Diego-Anjos
  - Integrante 2 — GUSTAVO RIBEIRO SANTOS / OvatsGGold
  - Integrante 3 — VICTORIA SANTANA LISBOA / VicSLisboa
  - Integrante 4 — IAN MEIRELLES SILVA / IanSMeirelles
  - Integrante 5 — @usuario5

## 2) Pitch (2–3 linhas)
> O NetoIA foi criado para ajudar você a usar a tecnologia de um jeito fácil e simples. Pense em nós como um neto paciente, pronto para ensinar e tirar todas as suas dúvidas. Aqui, você vai encontrar guias passo a passo para as tarefas mais comuns do dia a dia digital. 

## 3) Definição do Problema
- **Tema:** Pessoas com dificuldades para usar tecnologia
- **Problema (pergunta mensurável):** Como podemos facilitar a vida das pessoas com a tecnologia?
- **Objetivo do modelo:** Tirar dúvidas do usuário sobre tecnologia
- **Variáveis (entrada/saída):** Texto / Resposta:Voz:Imagem
- **Relevância/Impacto:** Pessoas com díficuldades de usar um computador, softwares e app tornando o dia-a-dia mais fácil.

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
