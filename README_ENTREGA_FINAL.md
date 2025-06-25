# Classificação de Grãos de Café com HOG + SVM

## Equipe
- Gustavo Machado

## Descrição do Descritor Implementado
Foi utilizado o descritor HOG (Histogram of Oriented Gradients), que extrai características baseadas na distribuição de gradientes (bordas e contornos) das imagens. Esse descritor é eficiente para capturar a forma e a textura dos objetos na imagem, ideal para distinguir entre grãos de café arábica e robusta.

## Repositório do Projeto
Link: https://github.com/gustavosm1/pratica/tree/main

## Classificador e Acurácia
- Classificador: SVM (Support Vector Machine) com kernel linear
- Acurácia obtida: **100%**
- Precisão, Recall e F1-score: **1.00** para ambas as classes
- Matriz de Confusão:
  ```
  [[2, 0],
   [0, 2]]
  ```

## Instruções de Uso (opcional)
1. Acesse o notebook `Projeto_HOG_SVM_ENTREGA_FINAL_OK.ipynb` no Google Colab.
2. Execute a primeira célula para fazer o upload do arquivo ZIP `Projeto_HOG_SVM_ENTREGA.zip`.
3. Após a extração, execute as demais células do notebook.
4. O código irá:
   - Extrair características com HOG
   - Treinar o classificador SVM
   - Exibir a acurácia, relatório de classificação e matriz de confusão

