🚀 Projeto Final — Machine Learning & Deep Learning (Aula 01)
Preencha este arquivo seguindo o roteiro abaixo. Use linguagem simples e objetiva. Não envie dados grandes para o repositório. Coloque links para o dataset e mantenha apenas amostras pequenas se necessário.

1) Identificação do Projeto
Título do projeto: Ex.: Detecção de Pneumonia em Raios-X
Turma/Disciplina: Ex.: MLDL — 2025.2
Professor: Rodrigo Moreira
Grupo (até 5): Nome completo + e-mail/usuário GitHub
Integrante 1 — VINICIUS LEITE DA SILVA / Vinisilva1304
Integrante 2 — VICTOR PEREZ CARDOSO / VictorPerezCardoso
Integrante 3 — KLEBER ALVES SANTANA / kklebs
Integrante 4 — VINICIUS GARRETO CAVALCANTI / garretovini32
Integrante 5 — RODRIGO SANTOS BITTENCOURT / RodrigoBittencourt011
2) Pitch (2–3 linhas)
O objetivo do projeto otimizar o tempo e a fila de espera, fazer com que o paciente chegue no local com seu dispositivo móvel, sendo ele celular ou qualquer outro que leia QR Code, e ao ser lido, abra a aplicação ou por totem. Nela, o paciente poderá preencher os dados básicos de cadastro, informar seus principais sintomas e indicar se possui alguma comorbidade ou não.

3) Definição do Problema
Tema: Saúde.
Problema (pergunta mensurável): Excesso de pessoas por morosidade no cadastro e triagem.
Objetivo do modelo: Otimizar tempo
Variáveis (entrada/saída): Ex.: pixels (X), rótulo (y)
Relevância/Impacto: Agiliza a Triagem, e quem se beneficia a População.
4) Dataset* ( A DEFINIR )
Fonte e link: Kaggle/UCI/Hugging Face/Google Dataset Search 
Descrição resumida: #amostras, #features, tipo (tabular/imagem/texto/séries)
Tamanho aproximado: MB/GB
Licença: Ex.: CC BY 4.0
Alvo (target): coluna/arquivo de rótulos
Balanceamento: Classes balanceadas? Se não, como lidar? (SMOTE, pesos, etc.)
Como será carregado: Link direto/Download local/Drive/HF Datasets
5) Estratégia Inicial
Baseline ML: Ex.: Regressão Logística/Decision Tree com features simples
Modelo ML principal: Ex.: Random Forest, SVM, XGBoost (justifique)
Deep Learning: Ex.: MLP/CNN/RNN conforme tipo de dado (justifique)
Métricas principais: Accuracy, F1, AUC-ROC, MAE/MSE, etc., com justificativa
Critérios de sucesso (meta): Ex.: F1 ≥ 0.85 no conjunto de teste
6) Riscos e Considerações Éticas
Viés nos dados: Classes desbalanceadas? Representatividade?
Privacidade/LGPD: Contém dados pessoais? Quais cuidados?
Limitações conhecidas: Ex.: tamanho do dataset, ruído, generalização
7) Cronograma (alto nível)
Aula 01: Problema + Dataset ✅
Aula 02: EDA + Preparação de dados
Aula 03: Baseline + ML tradicional
Aula 04: DL (rede neural) + comparação
Aula 05: Avaliação final + Deploy + Apresentação
8) Estrutura do Repositório
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
9) Como rodar (Local ou Colab)
Colab: Abra notebooks/ e crie um notebook. Use o link do dataset para carregar os dados.
Local (opcional):
python -m venv .venv
source .venv/bin/activate  # (Windows: .venv\Scripts\activate)
pip install -r requirements.txt
10) Status
 Tema definido
 Problema e objetivo escritos
 Dataset escolhido e validado
 Justificativa concluída
 Issue “Aula 01 — Kickoff” aberta e preenchida
📌 Convenções
Nome do repositório: mldl-2025-grupoNN-tema-curto (ex.: mldl-2025-grupo03-pneumonia)
Não subir arquivos > 50 MB. Para dados grandes, use link externo.
Cada alteração relevante deve vir via Pull Request com descrição clara.
