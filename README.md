```markdown
# 📊 EstudaData Transpetro — Ênfase 8: Ciência de Dados

Plataforma web open source de estudos, resolução de questões e geração de exercícios inéditos com Inteligência Artificial, estruturada 100% sobre o edital verticalizado para o cargo de **Ciência de Dados (Ênfase 8) da Transpetro**.

---

## 🚀 Funcionalidades

- **Resolução Interativa de Questões:**
  - Acervo inicial com questões reais e comentadas das principais bancas (Cesgranrio, Cebraspe e FGV) cobrindo os 12 blocos do edital.
  - Gabarito detalhado alternativa por alternativa e **Pílula de Conteúdo** resumindo o conceito teórico exigido na questão.
  - Navegação fluida com suporte a clique direto e atalhos de teclado (`A`–`E` ou `1`–`5` para selecionar, `Enter` para confirmar, `←` / `→` para navegar).
- **Tutor IA Integrado (Google Gemini):**
  - Botão sob demanda em cada questão resolvida para gerar uma microaula explicativa aprofundada, exemplos práticos e alertas sobre pegadinhas recorrentes de banca.
- **Gerador de Questões Inéditas com IA:**
  - Permite selecionar qualquer um dos **12 blocos e subtópicos do edital**, a banca alvo (**Cesgranrio**, **Cebraspe** ou **FGV**) e o nível de dificuldade.
  - Salva automaticamente cada nova questão gerada no banco de dados local (`LocalStorage`) do navegador, expandindo continuamente o acervo.
- **Edital Verticalizado & Métricas de Desempenho:**
  - Acompanhamento de progresso por bloco temático, taxa de acerto geral e filtro rápido por disciplina.
- **Portabilidade & Padrões Abertos:**
  - Exportação e backup completo do banco de questões e histórico de estudo em formatos abertos (**JSON** e **CSV**).

---

## 📚 Cobertura do Edital (12 Blocos)

1. **I — Matemática:** Cálculo Básico (limites, derivadas, integrais, máximos/mínimos) e Álgebra Linear (vetores, matrizes, normas, autovalores/autovetores, Cholesky, SVD).
2. **II — Probabilidade e Estatística:** Axiomas, Teorema de Bayes, distribuições discretas e contínuas, inferência, testes de hipóteses ($z$, $t$, $\chi^2$, F), teste A/B e correlação.
3. **III — Dados e Bases de Dados:** Tidy Data, formatos (CSV, JSON, XML, Parquet, Avro), Data Warehouse, Data Lake, Data Lakehouse, SQL, NoSQL e Big Data (Spark, Hadoop, HDFS).
4. **IV — Gestão de Projetos de Ciência de Dados:** Ciclo de vida, CRISP-DM, TDSP, OSEMN, SEMMA e Métodos Ágeis (Scrum/Kanban).
5. **V — Qualidade e Preparação de Dados:** Metadados, linhagem de dados, web scraping, limpeza, imputação, encoding, feature engineering e cross-validation.
6. **VI — Modelagem:** Pipelines de treinamento, otimização de hiperparâmetros, AutoML, métricas de regressão/classificação, regularização, dados desbalanceados (SMOTE) e Data-Centric AI.
7. **VII — Classes de Modelos:** Redução de dimensionalidade (PCA, LDA, t-SNE), clusterização (K-Means, DBSCAN, GMM), classificação, regressão, ensembles (Random Forest, XGBoost, LightGBM, CatBoost), séries temporais (ARIMA/ARIMAX), inferência causal e Deep Learning (CNNs, RNNs, LSTM, GRU, GANs).
8. **VIII — Processamento de Linguagem Natural (NLP):** Pré-processamento, TF-IDF, embeddings (Word2Vec, GloVe, BERT), topic modeling (LDA, NMF) e Transformers.
9. **IX — Programação e Ferramentas:** Python (Pandas, NumPy, Scikit-Learn, PyTorch, TensorFlow, PySpark, Beautiful Soup, Streamlit), SQL e Microsoft Power BI.
10. **X — Visualização, Storytelling e Comunicação Corporativa:** Gráficos, design visual, dashboards, acessibilidade e storytelling com dados.
11. **XI — Governança e Segurança de Dados:** DMBOK, qualidade/integridade de dados, privacidade e LGPD.
12. **XII — Governança, Segurança e Aplicação Responsável de IA:** Gestão de riscos em IA, vieses algorítmicos, ataques adversariais, *data poisoning*, alucinações, XAI (SHAP/LIME) e compliance.

---

## 🛠️ Stack Tecnológica (Open Source)

- **Frontend:** HTML5 Semântico, Tailwind CSS e JavaScript (ES6+ Vanilla) em arquitetura *single-file* sem dependências de build.
- **Persistência:** Web Storage API (`LocalStorage`) com importação/exportação em `JSON` e `CSV`.
- **Inteligência Artificial:** Integração client-side via REST API com o **Google Gemini** (`generativelanguage.googleapis.com`).

---

## 💻 Como Executar

### 1. Uso Local (Offline / Navegador)
1. Clone este repositório ou baixe o arquivo `index.html`:
   ```bash
   git clone [https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git](https://github.com/SEU-USUARIO/SEU-REPOSITORIO.git)

```

2. Abra o arquivo `index.html` diretamente em qualquer navegador moderno (Chrome, Firefox, Edge, Brave).

### 2. Configurando a IA (Opcional)

Para habilitar o **Gerador de Questões Inéditas** e o **Tutor IA**:

1. Gere uma chave gratuita no [Google AI Studio](https://aistudio.google.com/).
2. Na interface do **EstudaData**, abra a aba de configuração e cole sua chave de API.
3. A chave fica salva **exclusivamente no `LocalStorage` do seu navegador** e nunca é enviada para servidores terceiros além da API oficial do Google.

> **Nota de Segurança:** Caso hospede o site publicamente (GitHub Pages, Cloudflare Pages, Vercel ou Netlify), nunca insira sua chave de API diretamente no código-fonte `index.html`. Utilize apenas o campo de configuração na interface e restrinja o domínio da chave via *HTTP Referrer* no Google AI Studio.

---

## 📄 Licença

Este projeto é distribuído sob a licença **MIT** — sinta-se livre para usar, adaptar e compartilhar em seus estudos.

```

---

### Como adicionar ao seu repositório
1. No GitHub, clique em **Add file** $\rightarrow$ **Create new file**.
2. Digite `README.md` no nome do arquivo.
3. Cole o conteúdo acima e clique em **Commit changes**.

```
