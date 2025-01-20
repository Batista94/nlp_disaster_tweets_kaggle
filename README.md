# Análise de Sentimento em Tweets sobre Desastres
## Descrição do Projeto
Este projeto implementa um modelo de análise de sentimento para classificar tweets relacionados a desastres. Utilizando técnicas avançadas de processamento de linguagem natural (NLP) e aprendizado profundo, o modelo é capaz de determinar se um tweet está relacionado a um desastre real ou não.

## Motivação
O problema base é o de análise de sentimentos para tweets de desastres (https://www.kaggle.com/competitions/nlp-getting-started/overview), proposto pelo Kaggle. Nosso desafio é classificar textos curtos (tweets) em duas categorias:
1 (relacionado a desastres);
0 (não relacionado a desastres).

## Metodologia
O projeto utiliza o modelo DistilBERT, uma versão otimizada do BERT, para realizar a classificação de sentimentos. A implementação inclui:
Pré-processamento de dados textuais
Tokenização específica para o modelo DistilBERT
Fine-tuning do modelo pré-treinado para a tarefa de classificação
Treinamento com otimização de hiperparâmetros
Avaliação do modelo usando métricas padrão de classificação

## Arquivos utilizados
Os arquivos utilizados para Treino, Testes e o arquivo cru 'sample_submission.csv'estão presentes na pasta: files_analise_sentimento.zip

# Resultado
Na etapa de aprendizado , foi alcançado uma acurácia de 83.76% no melhor caso.

## Próximos Passos se fosse seguir com o projeto
Implementar técnicas de data augmentation para melhorar a generalização do modelo
Explorar outros modelos de linguagem pré-treinados para comparação de desempenho
Desenvolver uma API para integração com sistemas de monitoramento em tempo real
