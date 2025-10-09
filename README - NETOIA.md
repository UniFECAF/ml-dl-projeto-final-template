🚀 Projeto Final — Machine Learning & Deep Learning (Aula 01)
Preencha este arquivo seguindo o roteiro abaixo. Use linguagem simples e objetiva. Não envie dados grandes para o repositório. Coloque links para o dataset e mantenha apenas amostras pequenas se necessário.

1) Identificação do Projeto
Título do projeto: Neto-IA
Turma/Disciplina: GTI.4NA
Professor: Rodrigo Moreira
Grupo (até 5): Nome completo + e-mail/usuário GitHub
Integrante 1 — DIEGO DOS ANJOS GOMES / Diego-Anjos
Integrante 2 — GUSTAVO RIBEIRO SANTOS / OvatsGGold
Integrante 3 — VICTORIA SANTANA LISBOA / VicSLisboa
Integrante 4 — IAN MEIRELLES SILVA / IanSMeirelles
Integrante 5 — @usuario5
2) Pitch (2–3 linhas)
O NetoIA foi criado para ajudar você a usar a tecnologia de um jeito fácil e simples. Pense em nós como um neto paciente, pronto para ensinar e tirar todas as suas dúvidas. Aqui, você vai encontrar guias passo a passo para as tarefas mais comuns do dia a dia digital.

3) Definição do Problema
Tema: Pessoas com dificuldades para usar tecnologia
Problema (pergunta mensurável): Como podemos facilitar a vida das pessoas com a tecnologia?
Objetivo do modelo: Ex.: Tirar dúvidas do usuário sobre tecnologia
Variáveis (entrada/saída): Texto / Resposta:Voz:Imagem
Relevância/Impacto: Pessoas com díficuldades de usar um computador, softwares e app tornando o dia-a-dia mais fácil.
4) Dataset
Fonte e link: Hugging Face — openai/ai-tutor-faq
Descrição resumida: 10 000 amostras / 2 features principais (pergunta e resposta). Tipo: texto.
Tamanho aproximado: ~25 MB
Licença: Ex.: MIT License
Alvo (target): coluna “answer” (resposta gerada pela IA)
Balanceamento: Classes balanceadas? Se não, como lidar? Classes não se aplicam (pares texto–resposta). Para mitigar viés linguístico, serão amostradas perguntas de diferentes temas (tecnologia básica, internet, celular etc.)
Como será carregado: Direto via biblioteca datasets do Hugging Face (load_dataset('openai/ai-tutor-faq'))
5) Estratégia Inicial
Baseline ML: Ex.: Regressão Logística ou Naive Bayes para classificação de intenção (texto → categoria da dúvida) com TF-IDF como features.
Modelo ML principal: SVM linear — escolhido por ser eficiente em dados de texto de alta dimensionalidade e por oferecer bom equilíbrio entre precisão e velocidade.
Deep Learning: Rede neural transformer pré-treinada (BERT ou DistilBERT em Português) para gerar respostas contextuais. Justificativa: melhor capacidade de compreender semântica e contexto de linguagem natural.
Métricas principais: F1-Score e Accuracy para classificação; BLEU e ROUGE para qualidade de resposta em texto. F1 é prioritária por avaliar precisão e abrangência em casos de classes desiguais.
Critérios de sucesso (meta): F1 ≥ 0.85 no conjunto de teste e BLEU ≥ 0.75 para geração de respostas coerentes.
6) Riscos e Considerações Éticas
Viés nos dados: Perguntas podem refletir apenas situações de usuários com maior nível digital. Planeja-se ampliar o dataset com exemplos de linguagem simples e erros comuns para incluir pessoas com menor alfabetização tecnológica.
Privacidade/LGPD: Não contém dados pessoais. Todo o conteúdo é de bases públicas ou sintéticas. Cuidados adotados: remoção de nomes próprios, e-mails ou URLs.
Limitações conhecidas: Dataset moderado em tamanho, sem áudio real de voz e com vocabulário limitado. A generalização para usuários mais velhos pode exigir fine-tuning adicional ou dados próprios em português.
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
