# Ericsson

- Melhoria de busca de documentação com sinônimos. co-ocorrência, tf-idf. 


- Q & A, hardware: data set previous answered tickets with problem and solutio, given a new one, what are the tickts more similiar? Speed up trouble shooting


Projeto de Q&A para Ajuda de Troubleshooting na Ericsson: "Na Ericsson, trabalhei em um projeto de Q&A voltado para auxílio em troubleshooting de hardware. Desenvolvemos um sistema que, ao receber uma nova pergunta, era capaz de identificar os tickets mais semelhantes em um banco de dados de perguntas e respostas previamente resolvidas. Utilizamos uma combinação de técnicas, incluindo Word2Vec, Doc2Vec para melhorar a precisão das correspondências. Esse trabalho envolveu uma análise detalhada do contexto das perguntas, e a escolha da técnica apropriada para cada cenário foi fundamental para alcançar resultados eficientes."


- anomaly detection of temperature: radio station several temperature sensor 50+, we had the temperature only there was an alert. How do you check a true problem with a biased single temperature sensor?
- Anomaly detection invoices: error in generating invoices, maybe a promotion should not be applied. 
- predict error in hardware: most likely to need human intervention. discretization in time and space. time series
- which test should we run? suggest which test to run in a CI pipeline
- Debt Manager: risk of non-payment, given the history, will this invoice be paid or not? when 2 days before the due date, later?
- Clusterization of customer per payment behavior, how to act?

- Estimativa de Esforço para Implementação de uma nova funcionalidade de software e módulos impactos: "Liderei um projeto que envolvia a estimativa de esforço para a implementação de novas features em sistemas. A base de dados continha cerca de 2 anos de requisitos (por volta de 1000 entradas) com seus respectivos tempos de implementação em sprints anteriores. Utilizamos o BERT para representar semanticamente as features e, a partir daí, aplicamos o k-NN (k-Nearest Neighbors) para estimar o esforço necessário para novas features, identificando as mais semelhantes. O pré-processamento envolveu a tokenização das descrições das features, remoção de stop words, e a normalização dos textos, garantindo que o modelo capturasse de forma precisa o contexto sem ruídos desnecessários."



# Article
- heart rate variability: classification
- twitter: NLP: 

Análise de Tweets Durante Eleições Presidenciais no Brasil: "Durante meu MBA, realizei uma análise de sentimentos e de palavras mais frequentemente utilizadas em tweets de políticos durante as eleições presidenciais no Brasil. Esse trabalho envolveu web scraping para coletar os tweets e técnicas de análise de sentimento para identificar padrões de discurso na esquerda e na direita política. com tf-idf, conseguimos ver as palavras mais utlizadas em cada lado"


# Shift
- claim alerts, score
- claim decision, with nlp


Classificação de Documentos e Análise de Sinistros na Shift: "Na Shift Technology, utilizei o OpenAI para a classificação automática de documentos relacionados a sinistros em seguros de viagem, onde o OCR dos documentos era realizado por um serviço da AWS. Além disso, utilizamos o OpenAI para analisar as notas dos sinistros, com foco em identificar padrões que indicassem a possibilidade de aprovação ou rejeição do pagamento. A integração de expressões regulares (regex) com os modelos de linguagem criou uma abordagem que pode ser considerada uma espécie de Retrieval-Augmented Generation (RAG), onde as regex eram usadas para pré-filtrar informações antes da análise mais profunda pelo modelo, garantindo uma maior precisão e eficiência no processo de decisão."



