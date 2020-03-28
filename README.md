# Previsão do sucesso do telemarketing bancário
Abstrato:
Os dados estão relacionados com campanhas de marketing direto (telefonemas) de uma instituição bancária portuguesa. O objetivo da classificação é prever se o cliente assinará um depósito a prazo (variável y)

# Sobre o problema:
Recebemos os dados de campanhas de marketing direto (telefonemas) de uma instituição bancária portuguesa. O objetivo da classificação é prever se o cliente assinará um depósito a prazo (variável de destino y). Este estudo de caso é inspirado neste trabalho de pesquisa, onde os pesquisadores usaram um conjunto de dados muito semelhante ao que usaremos ao longo deste estudo de caso para determinar o sucesso do Telemarketing Bancário. Os pesquisadores em seu artigo mencionaram que o melhor resultado obtido foi uma pontuação na AUC de 0,8 e um ALIFT de 0,7. Portanto, como objetivo, tentaremos produzir um resultado semelhante em nosso estudo de caso.

# Sobre o conjunto de dados:
Como mencionado acima, o conjunto de dados consiste em dados de campanhas de marketing direto de uma instituição bancária. O conjunto de dados foi escolhido no UCI Machine Learning Repository, que é uma fonte incrível de conjuntos de dados disponíveis ao público. Havia quatro variantes dos conjuntos de dados dentre as quais escolhemos “bank-additional-full.csv”, que consiste em 41188 pontos de dados com 20 variáveis ​​independentes, das quais 10 são características numéricas e 10 são características categóricas.

# Tipo de problema de aprendizado de máquina:
Como você já deve ter adivinhado, esse é um problema de classificação binária. Nossas duas classes são "sim" denotando que o cliente assinou um depósito a prazo e "não" denotando que o cliente não assinou.

# Métrica de desempenho usada:
A métrica de desempenho usada para este estudo de caso é a pontuação ROC da AUC, também conhecida como AUROC (Área sob as características operacionais do receptor).
