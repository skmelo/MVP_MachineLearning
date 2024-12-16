# MVP_MachineLearning

Usando os [dados](https://archive.ics.uci.edu/dataset/267/banknote+authentication) de identificação de notas falsas e reais para avaliar a interferência de dados gerados por GAN no desempenho de uma [Random Forest](https://scikit-learn.org/1.5/modules/generated/sklearn.ensemble.RandomForestClassifier.html).

Com base no estudo feito o uso de dados gerados por GAN não afetou o desempenho do modelo na análise de dados reais. Contudo, um modelo treinado apenas com dados reais ao ser exposto a dados gerados por GAN no teste teve uma queda em perfomance, como já era esperado.
