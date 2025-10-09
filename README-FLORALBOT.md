# 🚀 Projeto Final — Machine Learning & Deep Learning (Aula 01)

> Preencha este arquivo seguindo o roteiro abaixo. Use linguagem simples e objetiva.
> **Não envie dados grandes para o repositório.** Coloque links para o dataset e mantenha apenas amostras pequenas se necessário.

## 1) Identificação do Projeto
- **Título do projeto:**: FloralBOT
- **Turma/Disciplina:**: MLDL — 2025.2_
- **Professor:** Rodrigo Moreira
- **Grupo (até 5):** Nome completo + e-mail/usuário GitHub  
  - Integrante 1 — Rhafael da Silva Marques/estudos.rhafael@gmail.com/RhafaelMarques
  - Integrante 2 — Gisele Santos Pereira/supabasepostgres@gmail.com/mindreminds
  - Integrante 3 — Giulia Santos Pereira/giulia.santos0505@hotmail.com/Giulia-SP
  - Integrante 4 — Gustavo Costa Marinho/gustavocostamarinho750@gmail.com/Questuy
  - Integrante 5 — Fabia Lima Santos/fabia.santos.127875@a.fecaf.com.br/Fabia174 
 

## 2) Pitch (2–3 linhas)
> Em poucas frases, diga o que o projeto faz e por que importa.
> R: A floralterapia utiliza essências florais para equilibrar emoções e promover bem-estar. Ela atua de forma sutil, ajudando a lidar com sentimentos como medo, ansiedade, insegurança, etc. É importante porque favorece o autoconhecimento e o equilíbrio emocional, contribuindo para uma vida mais harmoniosa e saudável.

## 3) Definição do Problema
- **Tema:** Saúde
- **Problema (pergunta mensurável):** _O que queremos prever/classificar?_
 R:
- Estados emocionais predominantes (ansiedade, medo, tristeza etc.);
- Respostas ao uso das essências (melhora, estabilidade, resistência);
- Perfis emocionais dos participantes;
- Padrões de evolução ao longo do tratamento (tempo de resposta, intensidade dos efeitos).

- **Objetivo do modelo:**:
R: Desenvolver um chatbot inteligente que utilize técnicas de aprendizado de máquina e análise de sentimentos para oferecer informações personalizadas sobre floralterapia. Com base nas informações fornecidas pelo usuário, o chatbot poderá sugerir essências florais de Bach adequadas ao estado emocional identificado, sempre ressaltando a importância de consultar um profissional qualificado para a indicação e acompanhamento adequados. Além disso, o sistema encaminhará a conversa para um atendente humano quando necessário, garantindo um suporte mais completo e empático.
  
- **Variáveis (entrada/saída):**
R:
Variáveis de entrada (input):
- Texto das mensagens do usuário;
- Emoções detectadas (por meio de análise de sentimento);
- Palavras-chave relacionadas a estados emocionais (ex.: “ansioso”, “triste”, “inseguro”);
- Informações contextuais do diálogo (histórico da conversa, intensidade emocional).

Variáveis de saída (output):
- Resposta do chatbot (informativa, empática ou orientadora);
- Classificação do estado emocional do usuário (positivo, neutro ou negativo, ou categorias específicas como medo, tristeza, raiva etc.);
- Sugestão de essências florais de Bach;
- Indicação para procurar um profissional ou encaminhamento para atendente humano.
  
- **Relevância/Impacto:** _Por que é útil? Quem se beneficia?_
R: É útil porque facilita o acesso a informações sobre floralterapia e ajuda o usuário a compreender melhor seu estado emocional, oferecendo uma experiência personalizada e acolhedora.
Os principais beneficiados são:
- Usuários, que recebem orientações iniciais e sugestões de florais de forma rápida e empática;
- Profissionais da área, que podem atender pessoas mais conscientes sobre suas emoções e necessidades;
- Instituições ou projetos de bem-estar, que ganham uma ferramenta automatizada para apoio emocional e triagem inicial.

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
- [x] Tema definido
- [x] Problema e objetivo escritos
- [ ] Dataset escolhido e validado
- [ ] Justificativa concluída
- [ ] Issue “Aula 01 — Kickoff” aberta e preenchida

---

### 📌 Convenções
- Nome do repositório: `mldl-2025-grupoNN-tema-curto` (ex.: `mldl-2025-grupo03-pneumonia`)
- Não subir arquivos > 50 MB. Para dados grandes, use link externo.
- Cada alteração relevante deve vir via Pull Request com descrição clara.
